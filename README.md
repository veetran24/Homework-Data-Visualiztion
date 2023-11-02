# Interaction Plots

[View Interactive Chart](https://veetran24.github.io/Homework-6//survivor.html)

  The interactive chart utilizes encodings to insightfully visualize the survivors information from Titanic dataset. The scatter plot effectively visualizes the relationships between the 'Age' and 'Fare' variables, using the x and y-axis encodings. The choice of symlog scaling for both axes accommodates datasets with a wide range of data values, including extreme or near-zero values, making it a versatile and effective choice. The "color" encoding based on "Pclass" helps distinguish different passenger classes within the scatter plot. The use of tooltips, including "Name," "Age," "Fare," and "Survived," provides detailed information when hovering over data points. This enhances the plot's effectiveness in presenting individual data point attributes as allows users to see the distribution of ages and fares across classes for survivors. Moving to the bar chart that visualizes the distribution of 'Pclass,' it effectively utilizes a horizontal bar for each class to represent the count of data points (number of passengers) on the x-axis. This straightforward choice is a useful summary of the data distribution. The y-axis encodes the 'Pclass' variable, enabling users to swiftly perceive the distribution of passengers across different passenger classes. Consistency in color encoding with the scatter plot maintains visual coherence between the two charts, while tooltip encoding offers precise count information for each 'Pclass,' delivering specific data details to the users.

  The selection interaction enhances the plot by enabling user-driven investigation. By brushing over points of interest, users can filter and isolate specific data subsets.  When dragging a selection box, the scatter plot dynamically filters to just the highlighted points, coloring them by 'Pclass' and graying out the unselected.  This immediately reveals relationships between the subset and passenger class. Furthermore, brushing coordinates the views, causing the bar chart to display 'Pclass' distributions for only the selected data. The linked selection propagates across both views, dynamically updating the bar chart to show only the passenger class breakdown for points within the current selection. By driving linked highlighting and filtering, the brush empowers discovery through flexible, interactive querying of the multi-dimensional data. Users can dynamically select subsets to uncover and analyze relationships between passenger class, age, fare, and more. This ability to interactively explore via selection and see the coordinated updates across views makes brushing invaluable for deeper data insight.
