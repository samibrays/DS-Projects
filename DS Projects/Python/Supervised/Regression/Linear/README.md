# Business Problem

Health insurance providers need to understand what drives medical costs in order to:

Price policies accurately

Identify high-risk customer profiles

Reduce financial exposure from underpricing

This project builds an interpretable regression model to quantify how demographic and lifestyle factors impact insurance charges.

# Dataset Description

Records: 1,338 insurance customers

Features:

age – Age of policyholder

sex – Gender

bmi – Body Mass Index

children – Number of dependents

smoker – Smoking status

region – Residential region

charges – Medical insurance cost (target variable)
# Business Questions

What factors most strongly influence insurance charges?

How much more do smokers cost insurers?

Does BMI significantly increase medical costs?

Can insurance charges be predicted reliably using demographic data?

How well does the model perform for high-cost customers?

# Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Statsmodels

# Methodology
1. Data Preparation

Verified data completeness (no missing values)

Encoded categorical variables using one-hot encoding

Split data into training and testing sets

2. Exploratory Data Analysis

Distribution analysis of insurance charges

Cost comparison by smoking status

Correlation analysis of numerical variables

3. Model Development

Built a Multiple Linear Regression model

Evaluated performance using:

MAE

MSE

RMSE

R² Score

4. Model Diagnostics

Residual distribution analysis

Q–Q plot for normality testing

Residuals vs predicted values for heteroscedasticity

# Model Performance
Metric	Value
R² Score	0.78
MAE	$4,181
RMSE	$5,796
# Key Insights

Smoking status is the strongest driver of insurance costs

Age and BMI significantly increase charges

Model performs well for average customers

Prediction error increases for high-cost individuals

Residual diagnostics reveal right-skewness and heteroscedasticity, common in insurance data

# Limitations

Linear regression underperforms for extreme medical costs

Model does not capture unobserved health conditions
