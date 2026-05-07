# Loan Approval Prediction — Machine Learning Project

## Project Overview
Predict whether a loan application will be approved or rejected
using supervised machine learning algorithms.

## Dataset
- Source: Kaggle — Loan Prediction Problem Dataset
- Rows: 614 | Columns: 13
- Target: Loan_Status (Y = Approved, N = Rejected)

## Models Trained & Accuracy
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 78.86% |
| Random Forest | 75.61% |
| Decision Tree | 69.11% |
| SVM | 65.04% |
| KNN | 57.72% |

## Best Model
Logistic Regression with 78.86% accuracy

## Key Findings
- Credit History is the most important feature
- Applicant Income and Loan Amount are 2nd and 3rd most important
- Semiurban property area has higher approval rate

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Files
- loan_data.csv — Dataset
- loan_prediction.ipynb — Main notebook
- eda_graphs.png — EDA visualizations
- confusion_matrix.png — Model evaluation
- roc_curve.png — ROC curves
- model_comparison.png — Accuracy comparison
