# Project Description (README Intro)

An end-to-end machine learning project that predicts medical insurance charges using ensemble regression techniques. The project compares Random Forest, AdaBoost, Gradient Boosting, and Stacking models, with a focus on business interpretability and model performance optimization.

# Business Problem

Insurance companies must accurately estimate expected medical costs to:

Price premiums fairly

Reduce underwriting risk

Identify high-cost customer segments

This project builds predictive models to estimate annual insurance charges using demographic and lifestyle features.

# Dataset

Source: Medical Cost Personal Dataset
Size: 1,338 records

Features
Feature	Description
age	Age of policyholder
sex	Gender
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential region
charges	Annual medical insurance charges (target)
⚙️ Modeling Approach
# Models Implemented

✅ Random Forest Regression (baseline)

✅ AdaBoost Regression

✅ Gradient Boosting Regression

✅ Stacking Regressor (Random Forest + GB + Ridge)

Techniques Used

One-hot encoding via ColumnTransformer

Pipeline-based modeling

Cross-validation

Hyperparameter tuning with:

GridSearchCV

RandomizedSearchCV

Ensemble learning for performance gains

# Model Performance (Typical Results)
Model	MAE ↓	RMSE ↓	R² ↑
AdaBoost	Moderate	Moderate	~0.82
Random Forest	Low	Low	~0.88
Gradient Boosting	Lower	Lower	~0.87
Stacking Regressor	Lowest	Lowest	~0.90+
# Key Insights

Smoking status is the strongest predictor of insurance charges

Age and BMI have nonlinear effects captured well by ensemble models

Stacking significantly improves prediction accuracy for high-cost individuals

# Business Impact

Enables data-driven premium pricing

Improves risk segmentation

Reduces financial exposure from underpriced policies

Demonstrates production-ready ML pipelines

# Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook
