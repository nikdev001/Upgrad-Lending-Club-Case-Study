# README: Loan Data Analysis
This README file provides an overview of the Python notebook used for analyzing loan data. The notebook includes various exploratory data analysis (EDA) tasks, visualization techniques, and the creation of derived columns to better understand the dataset.

Table of Contents
1.Introduction
2.Data Loading
3.Data Cleaning
4.Exploratory Data Analysis (EDA)
5.Derived Columns
6.Additional Test Cases
7.Conclusion

1.) Introduction:-
The purpose of this notebook is to perform a detailed analysis of a loan dataset. This includes understanding the distribution of various features, identifying relationships between different variables, and creating derived columns for deeper insights.

2.) Data Loading:-
The notebook begins by loading the necessary libraries and the loan dataset. The data is read from a CSV file and an Excel file containing the data dictionary.

3.) Data Cleaning:-
Data cleaning steps include:

4.) Handling missing values.
Converting data types (e.g., stripping percentage signs from interest rates and converting them to numeric types).

5.) Exploratory Data Analysis (EDA):-
The EDA section includes various visualizations to understand the distribution and relationships between key variables. Some of the key analyses include:

Distribution of loan amounts.
Interest rates.
Loan grades.
Annual income.

6.) Derived Columns:-
The notebook creates derived columns to provide additional insights:

Loan to Income Ratio: The ratio of loan amount to annual income.
Interest Rate Categories: Categorizing interest rates into bins (e.g., low, medium, high).
Debt-to-Income (DTI) Ratio Categories: Categorizing DTI ratios.
Annual Income Bins: Binning annual income into categories.

7.) Additional Test Cases:-
Additional test cases include:

Employment Length vs. Loan Amount: Analyzing the relationship between employment length and loan amount.
Loan Amount vs. Loan Term: Analyzing the relationship between loan amount and loan term.
Loan Amount by State: Analyzing the distribution of loan amounts across different states.
Distribution of DTI Categories: Analyzing the distribution of different DTI categories.
Distribution of Annual Income Bins: Analyzing the distribution of different annual income bins.
Correlation Matrix for Derived Columns: Creating a correlation matrix including the derived columns.
Loan Amount vs. Loan Purpose: Analyzing the distribution of loan amounts across different loan purposes.
Heatmap of Correlation between Numerical Variables: Visualizing the correlation between key numerical variables using a heatmap.

8.) Conclusion:-
The notebook concludes with visualizations and analyses that provide a comprehensive understanding of the loan dataset. By creating derived columns and performing various EDA tasks, the notebook helps identify key patterns and insights that can be useful for further analysis or decision-making processes.
