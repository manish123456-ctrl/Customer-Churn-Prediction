# Customer Churn Prediction

A machine learning pipeline to predict customer churn using XGBoost on Telco dataset.

## Results
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 74% | 0.83 |
| Random Forest | 77% | 0.81 |
| XGBoost | 79% | 0.80 |

## Tech Stack
Python · Scikit-learn · XGBoost · Pandas · Matplotlib · Seaborn · SMOTE

## Key Steps
- EDA on 7,032 customer records
- Fixed TotalCharges data quality issue
- Handled class imbalance using SMOTE
- Compared 3 models — XGBoost won
- Feature importance: tenure is #1 predictor

## Dataset
Telco Customer Churn — Kaggle (7,043 rows, 21 features)
