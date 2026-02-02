# Project Overview

This project builds an end-to-end supervised machine learning pipeline to predict whether an insurance customer is a smoker using demographic and health-related variables. The solution uses Logistic Regression, focusing on interpretability and business relevance for insurance risk assessment.

# Business Problem

Smoking status is a key driver of insurance risk and premium pricing.
The objective is to predict smoker status before policy issuance to support:

Risk segmentation

Premium optimization

Preventive healthcare programs

# Dataset

Insurance dataset with 1,338 records and the following variables:

Feature	Description
age	Age of policyholder
sex	Gender
bmi	Body Mass Index
children	Number of dependents
region	Residential region
smoker	Smoking status (Target)
charges	Medical insurance cost

# Machine Learning Approach

Problem Type: Binary Classification

Target Variable: smoker (Yes / No)

Algorithm: Logistic Regression

# End-to-End Workflow

Business understanding

Data loading and inspection

Data preprocessing

Categorical encoding

Feature scaling

Train-test split

Model training (Logistic Regression)

Model evaluation

Model interpretation (Odds Ratios)

Business insights and recommendations

# Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn (optional)

# Model Evaluation Metrics

Accuracy

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

# Key Insights

BMI and age are strong predictors of smoking behavior

Logistic Regression provides clear interpretability via odds ratios

Model effectively identifies high-risk individuals (smokers)

# Future Improvements

Handle class imbalance

Hyperparameter tuning

Compare with tree-based models

Deploy using Docker or FastAPI
