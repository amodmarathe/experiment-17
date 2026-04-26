🔹 Introduction

This experiment demonstrates the use of Python for data analysis and visualization using libraries like Pandas, Matplotlib, NumPy, and Seaborn.

The main objective is to understand how different types of plots help in interpreting data effectively. The dataset includes variables such as:

Study Hours
Marks
Attendance
Sleep Hours
Assignment Completion

Various visualization techniques such as line charts, bar graphs, histograms, and scatter plots are used to analyze trends, comparisons, distributions, and relationships within the data.

🔹 Libraries Used
Pandas – Data manipulation and DataFrame creation
Matplotlib.pyplot – Basic plotting and graph customization
Seaborn – Advanced statistical visualization
NumPy – Mathematical operations (e.g., mean calculation)
🔹 Functions and Commands Used
📌 Pandas Functions
pd.DataFrame(data)

Creates a DataFrame from dictionary data.

df['column_name']
Accesses a specific column in the DataFrame.

print(df)
Displays the dataset.
📌 Matplotlib Functions

Basic Plotting
plt.plot(x, y, marker=...)
Creates a line chart.

plt.bar(x, y, color=...)
Creates a bar chart.

plt.hist(data, bins=..., edgecolor=..., alpha=...)
Creates a histogram.

plt.scatter(x, y, color=...)
Creates a scatter plot.
Customization

plt.title()
Adds a title to the graph.

plt.xlabel() / plt.ylabel()
Labels the axes.

plt.legend()
Displays legend for multiple plots.

plt.grid()
Adds grid lines.

plt.figure(figsize=(w,h))
Sets figure size.
Advanced Features

plt.text(x, y, text, ha=..., va=...)
Adds text labels on bars.

bar.get_height()
Retrieves height of each bar.

plt.axvline(x, ...)
Draws a vertical line (used for mean).

plt.show()
Displays the plot.

📌 NumPy Functions
np.mean(data)
Calculates the mean of values.

📌 Seaborn Functions

sns.lineplot(x=..., y=..., data=...)
Creates a line plot with better aesthetics.

sns.barplot(x=..., y=..., data=...)
Creates a bar plot.

sns.histplot(data, bins=...)
Creates histogram.

sns.scatterplot(x=..., y=..., data=...)
Creates scatter plot.

📌 Python Concepts Used
List comprehension:
['red' if condition else 'green' for item in list]
Used to assign colors dynamically.
Dictionary data structure for dataset creation.

🔹 Types of Graphs Implemented
Line Chart – Shows trends over days

Advanced Line Chart – Comparison between study hours and marks

Bar Graph – Comparison of marks

Histogram – Distribution of marks

Scatter Plot – Relationship between study hours and marks

Colored Scatter Plot – Pass/Fail visualization

Seaborn Visualizations – Enhanced versions of plots

🔹 Conclusion

This experiment successfully demonstrates how Python can be used for effective data visualization.

Key learnings:

Different graphs serve different analytical purposes
Visualization makes data easier to understand
Libraries like Matplotlib and Seaborn simplify complex plotting
Data relationships (like study hours vs marks) become clearer visually
