# Wallmart
Walmart
Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas.
Task is to analyze the sales of walmart with the data given. (eg: anaglysing weekly sales, which store or department sells most etc.)
DATA ANALYSIS AND VIUALIZATION
Importing all the required libraries and packages.
Reading all the csv files as dataframes using pd.read_csv method.
Aanalyzing Each imported data frames.
Viewing the data in train_df
We can see that the dataframe has weekly sales data in accordance with store department and date.
Describe the data in train_df, that is mean count etc of the numerical columns in the data frame.
This shows how many null values each column in the data frame has, we can see that there are no null values in any columns of the data frame.
Viewing the test_df
Describing the data in the test dataframe.
Analysing null values in each column.
Viewing the features dataframe.
Viewing the Info of each column in the features dataframe.
Finding out about the null values in each column.
Viewing the stores data frame.
Finding the null values in each column.
Create a new data frame by merging (inner) features data frame to stores data frame on Store for analysis purpose.
Gathering info regarding the columns of the new data frame.
Convering date to date time object.
Creating a new df by merging (inner) the train_df and the new data frame dataset_m on store, date and IsHoliday columns and sorting the values by Store, department and date.
VISUALIZATIONS
Defining a function scatter to plot the scatter plot with the data of the column specified as the function parameter in x axis and weekly sales as the y values.

**NOTE**: I have attached the googlecolab file named (walmart data analysis and visualization.ipynb) where u can download and open it on the google colab to access it.
Also i have attached the code i have used on this project in a python code file.
1) scatter plot
2) 3 line plots for weekly sales for eact year
3) Combined line plots for each year (2010,2011,2012)
Plotting the weekly sales for years 2010,2011,2012 on a single plot to compare the sales values with respect to week on each of these specified year for comparing the weekly sales in each year.
We can see from the combined line lot that on week 51 of 2010 we have the maximum sale
4) Histogram / Normal Distribution
5) Box Plot
6) Bar Chart On Data Frame
Grouping the train_df by store and computing the mean of weekly_sales for each store.
Converting the data to a pandas dataframe
Sorting the data frame with respect to weekly sales in Descending order and plotting a var graph on the data frame itself to get a idea about the data.
We can see that Store number 20 has the highest weekly sales (20508.301592)
Sorting the data frame with respect to weekly sales in Ascending order and plotting a var graph on the data frame itself to get a idea about the data.
We can see that Store number 5 has the least weekly sales (5053.415813)
7) Bar graph for mean weekly sales for each store.
Plotting a bar graph with store number as x values and mean weekly sales for that store as the y values.
Grouping the train_df by Department and computing the mean of weekly_sales for each Department.
8) Bar chart on Data Frame.
Sorting the data frame with respect to weekly sales in Descending order and plotting a var graph on the data frame itself to get a idea about the data.
We can see that Department number 92 has the largest weekly sales.
Sorting the data frame with respect to weekly sales in Ascending order and plotting a var graph on the data frame itself to get a idea about the data.
We can see that department 47 has a cumulative negative value for weekly sales followed by department 43 which has a very low weekly sale of 1.193333.
9) Bar graph fpr mean weekly sales for each Department.
Plotting a bar graph with Department number as x values and mean weekly sales for that store as the y values.
10) Series of line plots for mean sales with respect to Departments.
Creating line plots of mean weekly sales for each department in the dataframe.
11) Histogram / Normal Distribution -Plotting the normal distribution where sales is greater than zero.
12) Heatmap - Plotting a heatmap to determine the correlation between columns in the data frame.
