# Business Problem

Insurance providers often rely on regional segmentation for pricing, marketing, and risk modeling. This project explores whether customer demographic and health-related attributes can be used to predict geographic region.

# Objective

Build and evaluate a K-Nearest Neighbors (KNN) classification model to predict a customer’s region based on:

Age

Sex

BMI

Number of children

Smoking status

Insurance charges

# Business Questions

Can customer attributes accurately predict geographic region?

Do healthcare costs vary significantly by region?

Is region distinguishable using distance-based models?

What are the limitations of KNN for demographic classification?

# Machine Learning Approach

Problem Type: Multiclass Classification

Algorithm: K-Nearest Neighbors (KNN)

Target Variable: Region

Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

# Data Processing

Label encoding for categorical variables

Feature scaling using StandardScaler

Stratified train-test split

Hyperparameter tuning for optimal k

# Model Performance

Accuracy: ~25–35%

Model performed slightly better than random guessing

High overlap between regional customer profiles

# Key Insights

Region is weakly predictable using demographic data alone

Distance-based models struggle with overlapping populations

Region is better used as an input feature, not a prediction target

# Business Recommendation

Capture region explicitly rather than inferring it

Use clustering for customer segmentation

Enhance datasets with ZIP/state-level data

# Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn
