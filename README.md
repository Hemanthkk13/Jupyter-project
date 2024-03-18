# Jupyter-project
Exploratory Data Analysis of the dataset containing details of employees in ABC company.

Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers you need, making it easier for data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumption. I carried EDA on the dataset containing details of employees in ABC company.

step1- Pre-processing of data

Step2- Analysis of data

Step3- Creation of visuals

Steps Followed in Pre-processing of the above data

1.Imported the necessary libraries: Before starting the preprocessing, make sure to import the necessary libraries such as pandas, numpy, matplotlib, and seaborn.

2.Loaded the dataset: Loaded the dataset into a pandas DataFrame using the read_csv() function.

3.Understand the dataset: Used the following functions to get an understanding of the dataset.

df.head() # Returns the first 5 rows of the dataset

df.tail() # Returns the last 5 rows of the dataset

df.info() # Returns the information about the dataset such as data types and null values

df.describe() # Returns the statistical summary of the datase

4.Handled missing values: Checked for missing values in the dataset and handled them appropriately. I used the isnull() function to check for missing values and the fillna() function to fill them.

5.Handled duplicate values: Checked for duplicate values in the dataset.If there is any use drop() function to drop such values.

6.Handled outliers: Checked for outliers in the dataset. You can use the boxplot and scatterplot to visualize the outliers and if any remove them using the drop() function.

Analysis of data is carried out
Visuals are created for each analysis and insights are drawn from it.
