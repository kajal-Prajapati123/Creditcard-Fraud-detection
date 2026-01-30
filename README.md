# Creditcard-Fraud-detection

This project is a part of internship task to perform **Fraud detection analysis and modeling** on Creditcard dataset using **Python, Pandas, Matplotlib, Seaborn, sklearn**

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
Due to the highly imbalanced nature of the dataset, special care is taken during preprocessing and model selection.

# Dataset Information
Source: Kaggle Credit Card Fraud Dataset
Total Records: 284,807 transactions

# Features:
V1 to V28: PCA-transformed numerical features (anonymized for confidentiality)
Time: Seconds elapsed between transactions
Amount: Transaction amount

# Class:
0 → Non-Fraud
1 → Fraud

# Data Preprocessing
Handled class imbalance using:
class_weight='balanced'

# Model Used
Logistic Regression
Why Logistic Regression?
- Suitable for binary classification
- Interpretable results
- Performs well on linearly separable data
- Efficient for large datasets

# Model Evaluation
Accuracy
Precision
Recall
F1-score
Confusion Matrix
Special focus was given to Recall, as detecting fraud cases is more important than overall accuracy.

# Feature Importance
Coefficients of Logistic Regression were analyzed
Important features influencing fraud detection were visualized
Feature importance plot saved as:
feature_importance_plot.png
