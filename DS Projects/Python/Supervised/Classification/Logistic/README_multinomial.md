## Project Overview
Insurance providers often need to understand regional customer distributions to support pricing strategies, marketing campaigns, and operational planning.  
This project builds a **multiclass logistic regression model** to predict a customer’s **geographic region** using demographic, lifestyle, and financial variables.

---

## Business Problem
Can we predict an insurance customer’s region based on their:
- Age
- Sex
- BMI
- Smoking status
- Number of children
- Medical insurance charges?

Understanding regional patterns enables:
- Targeted marketing strategies
- Region-specific risk analysis
- Better resource allocation

---

## Business Questions
1. Can customer attributes accurately predict geographic region?
2. Which features contribute most to distinguishing regions?
3. Do smoking habits and BMI vary significantly by region?
4. How well does a multiclass logistic regression model generalize?

---

## Dataset
**Insurance Dataset (1338 records)**

| Feature | Description |
|-------|-------------|
| age | Customer age |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| charges | Insurance charges |
| region | Geographic region (Target) |

---

## Methodology
1. Data loading and inspection
2. Exploratory data analysis (EDA)
3. Feature engineering and preprocessing
4. Train–test split with stratification
5. Multiclass logistic regression modeling
6. Model evaluation and interpretation
7. Business insights and recommendations

---

##  Model
- **Algorithm**: Multinomial Logistic Regression
- **Preprocessing**:
  - StandardScaler for numerical features
  - OneHotEncoder for categorical variables
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

---

## Results Summary
- The model achieved **moderate classification accuracy**
- Lifestyle factors such as **smoking status and BMI** showed stronger regional influence
- Demographic overlap across regions limits predictive performance

---

## Key Insights
- Logistic regression provides **interpretability** for business stakeholders
- Region prediction is better suited for **trend analysis** rather than strict automation
- Additional socioeconomic variables could improve accuracy

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook


---

## 📌 Author
**Samson Nigussie**  
Data Scientist | Data Analyst  

