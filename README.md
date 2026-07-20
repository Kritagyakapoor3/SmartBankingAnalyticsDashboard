# Machine Learning - Loan Default Prediction

## Overview

This module is a part of the Smart Banking Analytics project. It focuses on predicting loan default risk using supervised machine learning algorithms. The objective is to help financial institutions identify high-risk loan applicants and support data-driven lending decisions.

---

## Objective

Develop a machine learning model that predicts whether a customer is likely to default on a loan based on customer, loan, and financial information.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

---

## Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Inspection
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Feature Engineering
7. Feature Selection
8. Train-Test Split
9. Feature Scaling
10. Logistic Regression
11. Decision Tree
12. Random Forest
13. Model Comparison
14. Save Best Model
15. Business Insights
16. Conclusion

---

## Machine Learning Models

### Logistic Regression
A baseline linear classification model used for predicting loan default.

### Decision Tree
A tree-based classification model capable of capturing non-linear relationships.

### Random Forest
An ensemble learning algorithm consisting of multiple decision trees. This model achieved the best performance and was selected as the final model.

---

## Feature Engineering

Additional features created include:

- Loan Property Ratio
- Income Loan Ratio
- High Loan Indicator
- High Income Indicator
- Credit Category
- Interest Category
- Property Category

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature Importance

The Random Forest model produced the best overall performance and was selected as the final model.

---

## Business Insights

The model helps financial institutions to:

- Identify high-risk loan applicants.
- Improve loan approval decisions.
- Reduce potential loan defaults.
- Support risk-based customer segmentation.
- Improve overall credit risk management.

---

## Files

```
Machine_Learning/
│
├── loan_default_prediction.ipynb
├── best_loan_default_model.pkl
├── feature_importance.csv
├── model_comparison.csv
├── business_insights.csv
└── requirements.txt
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- ROC-AUC analysis
- Streamlit web application
- Model deployment using Flask or FastAPI

---

## Author

**Kritagya Kapoor**

Data Analytics | Machine Learning | Python | SQL | Power BI

## Note

The trained Random Forest model (`best_loan_default_model.pkl`) is not included in this repository because it exceeds GitHub's web upload size limit. You can regenerate it by running the notebook from start to finish.