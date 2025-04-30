# Movie-Correlation-Python-Project
## Overview

The objective of this project is to analyze a dataset of movies to uncover insights related to missing data, data types, outliers, correlations, and revenue trends among movie companies. The analysis involves data cleaning, visualization, and statistical analysis using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib.

## Correlation Analysis
The central objective of this project was to identify correlations between the variables for the following purposes:

**1.Understanding Relationships:** 
To uncover significant relationships between key features such as budget, gross earnings, and movie scores, providing insights into how different factors influence movie success.

**2.Feature Selection:**
To guide the selection of relevant features for predictive modeling and analysis, ensuring that the chosen variables contribute meaningfully to the project's objectives.

**3.Data Visualization:**
To visualize data patterns and relationships using heatmaps, facilitating better decision-making and a deeper understanding of the dataset's structure and dynamics.



## Steps Involved:
**1.Importing Libraries:**
Import essential libraries for data manipulation and visualization

**2.Reading the Data:**
Load the movie dataset from a CSV file:

**3.Initial Data Inspection:**
Display the dataset to understand its structure

**4.Missing Data Analysis:**
Calculate and print the percentage of missing data for each column

**5.Data Types Inspection:**
Print the data types of each column

**6.Outlier Detection:**
Visualize outliers in the 'gross' column using a boxplot

**7.Data Cleaning:**
Remove duplicate entries from the dataset

**8.Data Sorting:**
Sort the dataset by the 'gross' column in descending order

**9.Regression Analysis:**
Create regression plots to analyze relationships between 'gross' and 'budget', and 'score' and 'gross'

**10.Correlation Matrix:**
Calculate and visualize the correlation matrix for numeric columns using different methods (Pearson, Kendall, Spearman)

**11.Categorical Data Factorization:**
Assign numeric values to categorical data and calculate the correlation matrix

**12.Correlation Pairs Analysis:**
Unstack and sort correlation pairs to identify strong correlations

**13.Revenue Analysis by Company:**
Analyze and visualize the top 15 companies by gross revenue

**14.Yearly Revenue Analysis:**
Extract the year from the 'released' column and analyze yearly revenue trends

**15.Budget vs Gross Earnings Visualization:**
Create a scatter plot to visualize the relationship between budget and gross earnings

**16.Numerical Data Factorization:**
Factorize categorical columns and visualize the correlation matrix
