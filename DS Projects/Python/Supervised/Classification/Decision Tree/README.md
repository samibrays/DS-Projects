This project builds an end-to-end Decision Tree classification model to predict a customer’s insurance region using demographic, health, and financial attributes.
It also compares Label Encoding vs One-Hot Encoding and explains their impact on machine learning models.

# Business Problem

Insurance companies often need to:

Identify regional customer patterns

Understand risk distribution by geography

Support region-specific pricing and marketing strategies

This project answers:

Can we predict a customer’s region using demographic and risk-related data?

# Dataset

Insurance customer data (1,338 records)

Features

age

sex

bmi

children

smoker

charges

Target

region (4 classes)

# Business Questions

Which customer features best distinguish insurance regions?

Are smokers and high charges concentrated in specific regions?

How explainable is region prediction using decision trees?

How does encoding choice affect model behavior?

# Methodology

Exploratory Data Analysis (EDA)

Encoding comparison:

Label Encoding

One-Hot Encoding

Feature engineering

Train-test split

Decision Tree classification

Model evaluation

Feature importance analysis

Tree visualization and rule interpretation

# Model

Algorithm: Decision Tree Classifier

Criterion: Gini

Max Depth: Tuned to prevent overfitting

# Results

Region is partially predictable, with overlap across demographics

Charges and smoker status are the strongest regional differentiators

Decision Trees provide clear, interpretable rules

# Key Insights

Label Encoding is appropriate for tree-based models and targets

One-Hot Encoding is necessary for linear and distance-based models

Encoding choice significantly impacts model assumptions and interpretability
