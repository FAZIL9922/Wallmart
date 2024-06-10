## Walmart
Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas.
The task is to analyze the sales of Walmart with the data given. (e.g., analyzing weekly sales, which store or department sells the most, etc.)

NOTE: I have attached the Google Colab file named walmart_data_analysis_and_visualization.ipynb where you can download and open it on Google Colab to access it.
Also, I have attached the code I have used on this project in a Python code file. The data files in CSV format have been uploaded separately in the repository. 

*While running the code in colab, make sure to download and import the csv files before running the codes.
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
1)Scatter plot

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/9fbd3f8c-049b-4e65-81ef-9a2545a77e28)

2)Three line plots for weekly sales for each year.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/30f17d00-09f3-4e55-9da5-1a084253cde7)

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/07e0d10b-1acb-41dd-86f6-3d1c8d8a138d)

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/f9b75c1a-face-4e30-adc9-9b93792997de)

3)Combined line plots for each year (2010, 2011, 2012)

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/5c873cea-6fdf-4be6-9d48-cb632e86423e)

We can see from the combined line plot that in week 51 of 2010, we have the maximum sale.

4)Histogram / Normal Distribution

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/fc4fefa9-6042-462f-8ef7-63c4d9a4a10c)

5)Box Plot

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/dadbea9e-87b9-4a3d-918a-668615b6c402)

6)Bar graph for mean weekly sales for each store.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/64a8dccc-fa8c-4f19-bd72-416f5f024038)

7)Bar graph of mean weekly sales for each department.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/cd3c0e90-bb1c-40a8-9292-ab9d0a188f7e)


8)Series of line plots for mean sales with respect to departments.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/a0068386-eafc-4fd4-adef-e7fbb200c303)


9)Histogram / Normal Distribution - Plotting the normal distribution where sales are greater than zero.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/13677949-0cda-4dfd-8d0b-dc17b76f7761)


10)Heatmap - Plotting a heatmap to determine the correlation between columns in the dataframe.

![image](https://github.com/FAZIL9922/Wallmart/assets/138848536/23c8cb50-2188-4392-84c5-8e3fcc9143ef)
