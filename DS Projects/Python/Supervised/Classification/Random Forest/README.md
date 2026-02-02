# Project Overview

This project builds a multiclass machine learning model to predict a customer’s geographic insurance region using demographic, health, and cost-related features. The goal is to uncover regional risk and cost patterns that can inform pricing strategies, marketing decisions, and resource allocation in the insurance domain.

# Business Objective

Insurance providers operate differently across regions due to variations in:

Healthcare costs

Lifestyle risk factors

Demographic distributions

This project answers the question:

Can we predict a customer’s region based on personal and medical cost attributes—and what factors most clearly differentiate regions?

# Dataset Description

Records: 1,338 insurance customers

Feature	Description
age	Age of primary beneficiary
sex	Gender
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
charges	Medical insurance charges
region	Geographic region (target)

# Business Questions

Can demographic and health data predict a customer’s region?

Which variables most strongly differentiate geographic regions?

Do medical charges and lifestyle risks vary meaningfully by region?

Can this model support region-specific pricing or outreach strategies?

# Machine Learning Approach
Problem Type

Multiclass Classification

Model Selection

Random Forest Classifier

Captures non-linear relationships

Robust to noise and outliers

Provides feature importance for business insight

# Key Steps
1. Data Preprocessing

One-hot encoding for categorical variables

Label encoding for region target

Stratified train-test split

2. Model Training

Random Forest with 300 estimators

Controlled depth to reduce overfitting

3. Model Evaluation

Accuracy score

Confusion matrix

Precision, recall, and F1-score per region

4. Explainability

Feature importance analysis to identify key regional drivers

# Results & Insights
Model Performance

Accuracy: ~60% (vs. 25% random baseline)

Strongest predictions driven by:

Medical charges

BMI

Smoking status

Key Insights

Medical costs vary significantly by region

Lifestyle risk factors are strong geographic signals

Some regions show overlapping demographic patterns

# Business Impact

This model demonstrates how insurers can:

Design region-specific pricing strategies

Identify high-risk geographic segments

Optimize resource allocation and outreach

Support data-driven expansion planning

# Tech Stack

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn
