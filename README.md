# Credit Card Fraud Detection 

## Context
Built as part of the **ECX UNILAG** machine learning track.

Machine learning system for detecting fraudulent credit card transactions, 
trained on 568,630 real-world transactions from the 2023 Kaggle dataset.

## Models Compared
- Logistic Regression
- Random Forest  (Best)
- XGBoost

## Results
| Model | Precision | Recall | AUPRC |
|-------|-----------|--------|-------|
| Logistic Regression | 99.92% | 99.73% | 99.99% |
| Random Forest | 99.98% | 99.97% | 100% |
| XGBoost | 99.98% | 99.96% | 100% |

## Key Techniques
- SMOTE for class imbalance (applied to training data only)
- StandardScaler for feature scaling
- AUPRC as primary metric (not accuracy)

## Dataset
[Credit Card Fraud Detection 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023) — Kaggle

## Stack
Python, Scikit-learn, XGBoost, Pandas, NumPy

---
*Built by [David Gilbert](https://github.com/SwiftDG)*
