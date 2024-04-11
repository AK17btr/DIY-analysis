# India-Rainfall analysis
Data visualization on india rainfall in months of JUNE, JULY, AUGUST and SEPTEMBER from the year 1905 to 2019

This code is an example of how to analyze and visualize rainfall data using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. 
The code does the following:

Imports necessary libraries: Pandas, NumPy, Matplotlib, and Seaborn.
Reads in a CSV file containing rainfall data for all of India from 1901 to 2019 using Pandas' read_csv() function.
Prints the first few rows of the data using the head() method and provides basic information about the data using the info() and describe() methods.
Checks for missing values and data types of columns using isnull().sum() and dtypes.
Visualizes the yearly rainfall data for different months of the year using plt.plot(), plt.legend(), plt.title(), and plt.xlabel() and plt.ylabel() methods.
Visualizes the distribution of June-September rainfall using a histogram with sns.histplot().
Visualizes the distribution of June-September rainfall using a boxplot with sns.boxplot().
Plots a boxplot of the yearly rainfall data for the June-September period using sns.boxplot().
Computes and prints the month with the most and least rainfall using Pandas' idxmax() and idxmin() methods.
Visualizes the correlation matrix of the data using sns.heatmap().
Plots histograms of all the variables using df.hist().
Sets the index of the DataFrame to the year column using set_index().
Plots the time series of rainfall data using plt.plot().
Converts the year column to a datetime object using pd.to_datetime().
Plots the time series of rainfall data with the area under the curve filled using plt.fill_between().
Computes the total rainfall for each year and creates a new column in the DataFrame called "Total".
Melts the DataFrame to create a new DataFrame with a column for each month's rainfall data and a new column for the month name.
Plots a stacked area chart showing the contribution of each month to the total yearly rainfall over the years using plt.stackplot().

Based on the analysis of the All India Rainfall dataset, the following findings can be highlighted:
June-September is the period during which India receives the most rainfall.
There has been a significant variation in the rainfall pattern over the years.
The distribution of rainfall during the months of June-September is not normal and is positively skewed.
The year 1917 had the highest rainfall during the June-September period, while the year 1951 had the lowest.
The month of August contributes the most to the total rainfall, while June contributes the least.
There is a high positive correlation between the rainfall in the months of June, July, August, and September.
The rainfall during the June-September period has increased in recent years.
The contribution of each month to the total rainfall varies over the years.
