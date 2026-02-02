# Business Problem

Health insurance providers need to predict annual medical charges accurately to:

Price premiums fairly

Identify high-risk customer segments

Design preventive healthcare programs

This project builds an interpretable Decision Tree Regression model to predict insurance charges based on demographic and lifestyle factors.

# Dataset

Features:

Age

Sex

BMI

Number of children

Smoking status

Region

Target:

Annual medical charges

# Approach

Business problem definition

Exploratory Data Analysis (EDA)

Data preprocessing & encoding

Baseline Decision Tree Regression

Hyperparameter tuning using GridSearchCV

Model evaluation & interpretation

Business insights & pricing rules

# Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

# Model Performance (Tuned Decision Tree)

R² Score: ~0.80

RMSE: Significantly reduced vs baseline

MAE: Improved pricing accuracy per customer

# Key Insights

Smoking status is the strongest driver of insurance costs

BMI and age introduce non-linear cost thresholds

Decision Tree rules provide clear, explainable pricing logic

# Example Business Rule

IF smoker = Yes AND BMI > 30 AND age > 40 → Expected charges are significantly higher

# Future Enhancements

Random Forest & Gradient Boosting comparison

SHAP-based explainability

Pricing simulation dashboard

# Business Goal:
Help insurers price premiums accurately and identify high-risk customer segments.

# What I did:

Defined business-driven ML questions

Performed EDA and feature engineering

Built and tuned a Decision Tree using GridSearchCV

Translated model rules into explainable business insights

# Key Insights:

Smoking status is the strongest predictor of medical cost

BMI and age create clear cost thresholds

Decision Trees provide transparent, executive-friendly rules

# Tech Stack:
Python | Pandas | Scikit-learn | Matplotlib
