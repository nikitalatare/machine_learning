# Project Name
Lending club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.
Borrowers can easily access lower interest rate loans through a fast online interface.
The objective of analysis is to use the information about past loan applicants and find whether they ‘defaulted’ or not.
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default


## Table of Contents for Python file
- Data Understanding: Identifying data quality issues and the meanings of the variables
- Data cleaning Process
  Removing features on the basis of business logic
  Handling missing values
  Checking for missing values
  Standardizing the data for analysis
  Derived Variables
  Analysis for Outlier Treatment
- Univariate Analysis
  EDA for Loan Amount
  EDA for Funded Amount
  EDA for Categorical Data
  EDA for Home ownership
  EDA for Purpose
  Creating category bins for numerical variable to make them categorical
  EDA for Interest rate wrt the interest rate categories created
  EDA for Open_acc , Revol_util, Total_acc and Annual_inc
  EDA for Installment
  EDA by Issued Month and Year
  EDA for variables related to installment, debt-to-income ratio (dti), and loan amount (loan_amnt).
- Observations from Univariate EDA & Recommendation
- Bivariate Analysis
  EDA for Term vs Loan Status
  EDA for Annual income vs loan purpose
  EDA for Annual income vs home ownership
  EDA for Annual Income vs Loan amount
  EDA for Annual income vs int_rate
  EDA for Grade vs Loan amount
  EDA for Loan vs Loan purpose
  EDA for Loan vs House Ownership
  EDA for Loan amount vs month issued and year issued
  EDA for Loan amount amount vs Grade
  EDA for Loan Amount vs Interest Rate
  EDA for Grade vs Interest rate
  EDA for Term and Loan amount
Correlation Matrix
Observations and Recommendations based on Bivariate analysis

## General Information
Project Description:
This project involves conducting a comprehensive data analysis on a loan dataset from Lending Club, which is the largest online loan marketplace. The dataset contains information about past loan applicants and whether they defaulted on their loans or not. The primary objective of this analysis is to identify the key factors or variables that strongly indicate loan default, thus helping the company understand the driving factors behind default.

Background of the Project:
Lending Club is an online platform that connects borrowers with investors to provide various types of loans, including personal loans, business loans, and financing for medical procedures. One of the company's main goals is to offer lower interest rate loans to borrowers through a convenient online interface. To ensure the sustainability and success of their lending business, Lending Club needs to mitigate the risk of loan default by identifying the factors that contribute to it. This project aims to provide insights into these factors through data analysis.

Business Problem:
The primary business problem this project is trying to solve is understanding the drivers behind loan default for Lending Club. Loan defaults can result in financial losses for the company and affect the overall stability of their lending platform. By identifying the variables strongly associated with loan defaults, Lending Club can take proactive measures to minimize risks, make informed lending decisions, and improve their loan approval process. In essence, the project aims to provide actionable insights to reduce default rates and enhance the overall success of Lending Club's lending operations.

Dataset:
The dataset being used in this project contains historical data related to loan applicants who have applied for loans through Lending Club. It includes a variety of variables such as borrower information (e.g., income, employment), loan details (e.g., loan amount, interest rate), and loan status (whether the loan was repaid or defaulted). The dataset is a valuable resource for conducting data analysis to identify patterns, correlations, and predictive factors related to loan defaults.

The project's tasks involve data understanding, cleaning, and conducting both univariate and bivariate analyses to explore the relationships between different variables and loan default. Ultimately, the analysis aims to provide Lending Club with actionable insights and recommendations for reducing loan default rates and improving their lending processes.

## Conclusions
Observations from Univariate EDA & Recommendation

### Based on the analysis with respect to the charged off loans for each variable suggests the following. There is a more probability of defaulting when :

- Applicants with 'RENT' as their house ownership status have a higher probability of defaulting.
- Borrowers who use the loan for debt consolidation purposes are more likely to default.
- Default probability is elevated when the interest rate falls within the range of 13-17%.
- Borrowers with an annual income ranging from USD 30000 to USD 60000 are more prone to default.]
- Individuals with 20-37 open accounts (open_acc) exhibit a higher likelihood of default.
- Borrowers with a employment length of 10 years have an increased chance of defaulting.
- Loans funded by investors within the range of $5,000 to $10,000 are associated with higher default rates.
- Loan amounts falling between $5000 and $10000 are linked to an elevated likelihood of default.
- A debt-to-income ratio (dti) in the range of 12-18 increases the probability of default.
- Loans with monthly installments between $150 and $300 are more likely to default.
- Loans with a term of 36 months have a higher probability of defaulting.
- Loans without verified status are associated with a greater likelihood of default.
- A borrower's default probability tends to be higher when they have zero recent inquiries in the last 6 months.
- Borrowers with zero derogatory public records are more prone to default.
- Loans intended for the purpose of debt consolidation exhibit a higher likelihood of default.
- Loans graded as 'B' have an increased probability of default.
- Specifically, loans assigned a total grade of 'B5' have a higher likelihood of defaulting.


# Observations and Recommendations based on Bivariate analysis 

- There is a higher probability of defaulting among applicants who take out loans for 'home improvement' and have an annual income ranging from USD 65,000 to UD 70,000.
- Borrowers who own homes under 'MORTGAGE' status and earn between USD 60,000 and USD 70,000 annually are more likely to default.
- A heightened risk of default is associated with applicants who receive interest rates falling in the range of 21-24% and have an annual income between USD 70,000 and USD 80,000.
- Borrowers who take out loans in the range of USD 30,000 to USD 35,000 and are charged an interest rate between 15% and 17.5% exhibit an increased likelihood of default.
- Applicants who secure loans for small business purposes and have a loan amount exceeding USD 14,000 are more prone to default.
- Individuals with 'MORTGAGE' home ownership status and loans ranging from USD 14,000 to USD 16,000 have an elevated probability of default.
- When loans are graded as 'F' and fall within the loan amount range of USD 15,000 to USD 20,000, there is a higher likelihood of default.
- Borrowers with an employment length of 10 years who obtain loans between USD 12,000 and USD 14,000 are at an increased risk of default.
- Loans that are verified and have a loan amount exceeding $16,000 are associated with a greater probability of default.
- For loans graded as 'G' with interest rates surpassing 20%, there is an elevated likelihood of default.


## Technologies Used
Python: A popular programming language for data analysis and manipulation.
Jupyter Notebooks: An interactive computing environment for data analysis and visualization.
Pandas: A Python library for data manipulation and analysis.
NumPy: A library for numerical computations in Python.
Matplotlib and Seaborn: Libraries for creating data visualizations and plots.




## Contact
Created by [@vaibhav90363]  or [@nikitalatare] - feel free to contact me!
