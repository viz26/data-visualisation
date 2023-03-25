# data-visualisation
getting student data from external file using csv and making charts based on that data


The code imports the required libraries: pandas for data manipulation and matplotlib for data visualization. It also imports the date class from the datetime module.

It reads a CSV file containing student data into a pandas DataFrame using the read_csv() function.

The code converts the marks column to an integer data type using the astype() function.

The code calculates the highest and lowest marks for each subject by calling the max() and min() functions on the DataFrame.

The code calculates the average marks across all subjects by calling the mean() function on the DataFrame with the axis argument set to 1 (to calculate the mean across columns).

The code prints the highest, lowest, and average marks.

The code creates a bar chart of the lowest marks using the bar() function from matplotlib.

The code creates a bar chart of the highest marks using the bar() function from matplotlib.

The code creates a histogram of the average marks using the hist() function from matplotlib.

The code creates a pie chart of the distribution of marks in each subject using the pie() function from matplotlib.

The code creates a scatter plot of physics marks vs. maths marks using the scatter() function from matplotlib.

The code creates a line chart of computer marks over time using the plot() function from matplotlib. It first creates a new column in the DataFrame called "Date" using the date_range() function from pandas, and then calls the plot() function on this new column and the "COMP" column from the DataFrame.

Finally, the code shows all the plots using the show() function from matplotlib.
