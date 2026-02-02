# Project Description 

This project builds an end-to-end machine learning regression pipeline to predict individual medical insurance charges using demographic, lifestyle, and regional features.
Support Vector Regression (SVR) is applied to capture non-linear relationships between predictors and medical costs.

# Business Problem

Health insurance providers need accurate cost predictions to:

Price policies fairly

Identify high-risk customers

Optimize underwriting decisions

Reduce financial uncertainty

Traditional linear models fail to capture strong non-linear effects (e.g., smoking + age).
This project evaluates whether SVR can improve prediction accuracy.

# Dataset

Insurance dataset (1338 records)

Feature	Description
age	Age of the insured
sex	Gender
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential region
charges	Medical insurance cost (target)

# Business Questions Answered

Can we accurately predict insurance charges using customer demographics?

How strongly do smoking and BMI drive medical costs?

Does SVR outperform linear regression in modeling non-linear insurance data?

Is SVR suitable for pricing and risk assessment?

# ML Workflow

Business understanding

Data loading & EDA

Feature engineering

One-hot encoding for categorical variables

Feature scaling (critical for SVR)

Train-test split

SVR model with RBF kernel

Hyperparameter tuning using GridSearchCV

Model evaluation (MAE, RMSE, R²)

Business interpretation

# Model Performance (Typical)

R²: ~0.80–0.85

RMSE: ~$4,000–$5,500

MAE: ~$3,000–$4,000

SVR significantly improves prediction accuracy over baseline linear models by capturing non-linear cost drivers.

# Key Insights

Smoking status is the strongest cost driver

BMI has a compounding effect with age

SVR is effective for pricing accuracy but less interpretable

Suitable for actuarial modeling and risk segmentation

# Tech Stack

Python

Pandas, NumPy

Scikit-learn

SVR (RBF Kernel)

GridSearchCV
