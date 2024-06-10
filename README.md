## Walmart
Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas.
The task is to analyze the sales of Walmart with the data given. (e.g., analyzing weekly sales, which store or department sells the most, etc.)

## DATA ANALYSIS
1)Importing all the required libraries and packages.

2)Reading all the CSV files as dataframes using the pd.read_csv method.

3)Analyzing each imported dataframe.

4)Viewing the data in train_df.

5)We can see that the dataframe has weekly sales data in accordance with store, department, and date.

6)Describe the data in train_df, that is mean, count, etc., of the numerical columns in the dataframe.

7)This shows how many null values each column in the dataframe has. We can see that there are no null values in any columns of the dataframe.

8)Viewing the test_df.

9)Describing the data in the test dataframe.

10)Analyzing null values in each column.

11)Viewing the features dataframe.

12)Viewing the info of each column in the features dataframe.

13)Finding out about the null values in each column.

14)Viewing the stores dataframe.

15)Finding the null values in each column.

16)Create a new dataframe by merging (inner) the features dataframe to the stores dataframe on Store for analysis purposes.

17)Gathering info regarding the columns of the new dataframe.

18)Converting date to datetime object.

19)Creating a new df by merging (inner) the train_df and the new dataframe dataset_m on Store, date, and IsHoliday columns and sorting the values by Store, department, and date.

## VISUALIZATIONS
NOTE: I have attached the Google Colab file named walmart_data_analysis_and_visualization.ipynb where you can download and open it on Google Colab to access it.
Also, I have attached the code I have used on this project in a Python code file.

1)Scatter plot

2)Three line plots for weekly sales for each year.

3)Combined line plots for each year (2010, 2011, 2012)

4)Plotting the weekly sales for the years 2010, 2011, 2012 on a single plot to compare the sales values with respect to week on each of these specified years for comparing the weekly sales in each year.

5)We can see from the combined line plot that in week 51 of 2010, we have the maximum sale.

6)Histogram / Normal Distribution

7)Box Plot

8)Bar Chart On Data Frame

9)Grouping the train_df by store and computing the mean of weekly sales for each store.

10)Converting the data to a pandas dataframe.

11)Sorting the dataframe with respect to weekly sales in descending order and plotting a bar graph on the dataframe itself to get an idea about the data.

12)We can see that Store number 20 has the highest weekly sales (20508.301592).

13)Sorting the dataframe with respect to weekly sales in ascending order and plotting a bar graph on the dataframe itself to get an idea about the data.

14)We can see that Store number 5 has the least weekly sales (5053.415813).

15)Bar graph for mean weekly sales for each store.

16)Plotting a bar graph with store number as x values and mean weekly sales for that store as the y values.

17)Grouping the train_df by department and computing the mean of weekly sales for each department.

18)Bar chart on Data Frame.

19)Sorting the dataframe with respect to weekly sales in descending order and plotting a bar graph on the dataframe itself to get an idea about the data.

20)We can see that Department number 92 has the largest weekly sales.
Sorting the dataframe with respect to weekly sales in ascending order and 
plotting a bar graph on the dataframe itself to get an idea about the data.

21)We can see that department 47 has a cumulative negative value for weekly sales followed by department 43 which has a very low weekly sale of 1.193333.

22)Bar graph for mean weekly sales for each department.

23)Plotting a bar graph with department number as x values and mean weekly sales for that department as the y values.

24)Series of line plots for mean sales with respect to departments.

25)Creating line plots of mean weekly sales for each department in the dataframe.

26)Histogram / Normal Distribution - Plotting the normal distribution where sales are greater than zero.

27)Heatmap - Plotting a heatmap to determine the correlation between columns in the dataframe.
