## Project Overview
This project applies a **Naive Bayes classification model** to predict a customer’s **geographic region** based on demographic and health-related attributes. The goal is to explore whether customer characteristics can be used to support **regional segmentation, pricing, and marketing strategies** in the insurance domain.

---

## Business Problem
Insurance providers often tailor pricing, marketing, and operational strategies by region.  
This project investigates:

- Can we predict a customer’s region using demographic and lifestyle data?
- Which features contribute most to regional differentiation?
- How effective is a probabilistic model such as Naive Bayes for this task?

---

## Dataset
**Source:** Public insurance dataset  
**Records:** 1,338 customers

### Features
| Variable | Description |
|-------|-------------|
| age | Customer age |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Geographic region *(Target)* |

---

## Modeling Approach
- Problem Type: Multiclass Classification
- Algorithm: **Gaussian Naive Bayes**
- Encoding: Label Encoding for categorical variables
- Scaling: StandardScaler
- Evaluation Metrics:
  - Accuracy
  - Confusion Matrix
  - Precision / Recall / F1-score

---

## Results
- Achieved **moderate classification accuracy**
- Regions show overlapping demographic patterns
- Naive Bayes provides **probabilistic insights** useful for segmentation

---

## Limitations
- Assumes feature independence
- No geographic or economic indicators
- Region prediction is inherently challenging without spatial features

---

## Future Improvements
- Add income and location-based features
- Compare with Random Forest & XGBoost
- Use spatial clustering for regional analysis

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn


