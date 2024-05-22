# Lending Club Case Study
> This project involves analyzing loan data to identify likely defaulters based on various financial and demographic factors. The analysis uses Python and its data analysis libraries, primarily focusing on univariate and bivariate analyses to derive business insights and recommendations.

<br>

>## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

>## General Information
**Background:**
  There is a consumer finance company which specializes in lending various types of loans to urban customers. This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 

**Business Problem:**
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

**Business Objective:**
The objective of the company is to understand the driving factors (or driver variables) behind loan default by identifying patterns which indicate if a person is likely to default, which may be used for taking actions such as:
- Denying the loan
- Reducing the amount of loan
- Lending (to risky applicants) at a higher interest rate

**Dataset Used:**
Loan data set of a consumer finance company is provided which contains the complete loan data for all loans issued through the time period 2007 t0 2011.

>## Approach
 - Identify likely defaulters using univariate and bivariate analyses.
 - Provide business recommendations to mitigate default risks.
 - Visualize key relationships between loan variables to derive actionable insights.


>## Analysis Steps and Observations

>### Univariate Analysis

#### 1. Loan Purpose:

 - Small Business loans have the highest default rate (~25.98%).
 - Renewable Energy and Educational loans also show significant default rates (~18.45% and ~17.23%, respectively).
 - Recommendation: Monitor and apply stricter approval criteria for high-risk loan purposes.

#### 2. Home Ownership:

 - "Other" ownership has the highest default rate (~18.37%), followed by Renters (~15.02%).
 - Recommendation: Apply higher scrutiny to renters and non-standard home ownership statuses.

#### 3. Debt-to-Income (DTI) Ratio:

 - Higher DTI ratios correlate with higher default likelihood.
 - Recommendation: Set strict DTI limits for loan approvals and provide financial counseling to high-DTI borrowers.

#### 4. Loan to Income Ratio:

  - Higher loan to income ratios indicate a higher default risk.
  - Recommendation: Implement caps on loan amounts relative to income.

>### Bivariate Analysis
#### 1. Loan Amount vs. Annual Income:

 - Positive correlation between loan amount and annual income.
 - Charged Off loans are frequent in lower income brackets with higher loan amounts.
 - Recommendation: Limit loan amounts for low-income borrowers to reduce risk.

#### 2. Debt-to-Income Ratio vs. Interest Rate:

 - Higher interest rates associate with higher DTI ratios and higher defaults.
 - Recommendation: Adjust interest rates based on DTI ratios and implement risk-based pricing.
#### 3. Annual Income vs. Debt-to-Income Ratio:

 - Higher DTI ratios correlate with a higher presence of Charged Off loans.
 - Recommendation: Regular monitoring of high-DTI borrowers regardless of income level.
#### 4. Employment Length vs. Loan Amount:

- Median loan amounts are consistent across employment lengths, slightly higher for 10+ years.
- Recommendation: Factor in employment stability but consider alongside other variables.

>### Business Recommendations
#### 1. Risk Management:

- Focus on high-risk categories (Small Business loans, high DTI, high loan to income ratios).
- Implement stricter approval processes and provide financial counseling.
#### 2. Interest Rate Strategy:

 - Adjust interest rates based on a combination of risk factors to manage risk better.
#### 3. Loan Approval Criteria:

 - Refine loan approval criteria using insights from the analysis to prevent overextension of borrowers.
#### 4. Financial Counseling:

 - Offer support to high-risk borrowers to help manage their debt and reduce defaults.

>## Conclusion
### This analysis helps identify potential defaulters by examining various financial indicators and relationships. The insights and recommendations provided aim to improve loan approval processes, manage risks effectively, and support borrowers in maintaining their financial health.

### For more detailed analysis and visualizations, refer to the Nikhil-Nishant.ipynb notebook.

> ## Technologies
- Jupyter Notebook version:  6.5.4
- Python version:  3.11.5 
- Pandas version:  2.0.3
- NumPy version:  1.24.3
- Matplotlib version:  3.7.2
- Seaborn version:  0.12.2

> ## Files in the Project
 1. **Nikhil-Nishant.ipynb:** The Jupyter Notebook containing the analysis code and visualizations.
 2. **Data_Dictionary.xlsx:** The data dictionary providing descriptions of each column in the loan dataset.
 3. **loan.csv:** The loan dataset used for analysis.
 4. **README.md** File for High level Project overview & approach.
 5. **Nikhil_Nishant.pdf** File about the Analysis and Conclusions of EDA performed in business terms.

> ## Contributors
- Nikhil Gupta
- Nishant Singh

