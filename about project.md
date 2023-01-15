# Credit Card Default Risk Analysis

The purpose of this project is to conduct 
quantitative analysis on credit card default risk by using 3 machine learning models with accessible customer data, instead of credit score or credit history, with the goal of assisting and speeding up the human decision making process.

Project Overview
The analysis consists of 2 Jupyter notebooks.

Exploratory Data Analysis. The detailed notebook of EDA can be found here.
Machine Learning Modeling. The detailed notebook of modeling can be found here.
Machine Learning Models Used:

1. Logistic Regression
2. Random Forest
3. XGBoost
See the presentation slides for a summary of this analysis.

## Key Findings from EDA
Males have more delayed payment than females in this dataset. Keep in mind that this finding only applies to this dataset, it does not imply this is true for other datasets.
Customers with higher education have less default payments and higher credit limits.
Customers aged between 30-50 have the lowest delayed payment rate, while younger groups (20-30) and older groups (50-70) all have higher delayed payment rates. However, the delayed rate drops slightly again in customers older than 70.
There appears to be no correlation between default payment and marital status.
Customers being inactive doesn’t mean they have no default risk. We found 317 out of 870 inactive customers who had no consumption in 6 months then defaulted next month.
