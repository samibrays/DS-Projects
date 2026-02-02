# Business Problem

Insurance companies operate across multiple geographic regions with varying healthcare costs, demographic distributions, and risk profiles.
This project aims to predict a policyholder’s region using demographic, lifestyle, and financial features to support regional risk segmentation, pricing strategies, and targeted marketing.

# Dataset

1,338 insurance policyholders

Features:

Age

Sex

BMI

Number of children

Smoking status

Insurance charges

Target:

Region (Multiclass classification)

# Business Questions

Can customer demographics and healthcare costs predict geographic region?

Which features best differentiate regions?

Are certain regions more predictable than others?

How can insurers leverage region prediction for operational strategy?

# Machine Learning Approach

Model: Support Vector Machine (SVM – RBF Kernel)

Task: Multiclass classification

Preprocessing:

StandardScaler for numerical features

OneHotEncoder for categorical variables

Validation: Train–test split with stratification

Evaluation Metrics:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

# Key Results

Achieved moderate classification accuracy (~50–65%)

Smoking status and healthcare charges contributed significantly to regional separation

Some regions exhibit overlapping demographic profiles, limiting separability

# Business Impact

Demonstrates that region alone does not fully explain cost differences

Supports data-driven regional pricing and segmentation

Highlights the importance of behavioral and lifestyle variables

# Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook
