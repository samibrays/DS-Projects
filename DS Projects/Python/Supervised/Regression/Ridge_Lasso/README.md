# Project Overview

Medical insurance providers must accurately estimate healthcare costs while avoiding overfitting and bias. This project builds regularized regression models (Ridge & Lasso) to predict individual insurance charges using demographic and behavioral data.

# Business Problem

How can insurance companies predict medical charges accurately while maintaining model stability and interpretability?

# Dataset

Features

Age

Sex

BMI

Number of Children

Smoking Status

Region

Target

Insurance Charges

# Analytical Approach

Exploratory Data Analysis (EDA)

Feature Encoding & Scaling

Ridge Regression (L2 Regularization)

Lasso Regression (L1 Regularization)

Model Evaluation using MAE, RMSE, and R²

Coefficient interpretation for business insights

# Models Used
Model	Purpose
Linear Regression	Baseline
Ridge Regression	Reduce variance, stabilize predictions
Lasso Regression	Feature selection & interpretability
# Key Results

Smoking status is the strongest driver of insurance costs

BMI and age show consistent positive relationships with charges

Lasso eliminated low-impact regional variables

Regularization improved model generalization and pricing reliability

# Tech Stack

Python

pandas, numpy

scikit-learn

matplotlib, seaborn

Jupyter Notebook

# Business Impact

Enables fairer and more stable premium pricing

Reduces overfitting in cost prediction models

Improves interpretability for underwriting teams
