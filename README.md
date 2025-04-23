# AMEX_Default_Prediction
Predicting Defaulters using AMEX Banking dataset using High level Machine Learning Models and AI for Model Explainability with Fairness Checks and presenting the Insights through PowerBI Dashboard

# AMEX Credit Default Prediction: Interpretable & Fair Modeling

## Project Overview

This project, developed as part of an MSc Data Science dissertation (2024-2025), focuses on building an interpretable, fair, and regulatory-compliant credit scoring model to predict credit card default risk. It utilizes the publicly available American Express Default Prediction dataset from Kaggle and explores classical machine learning techniques, emphasizing transparency and ethical considerations crucial in the banking sector.

The primary goals are:
1.  Develop a robust data preprocessing pipeline.
2.  Compare Logistic Regression, Decision Trees, and XGBoost models.
3.  Employ SHAP (Shapley Additive Explanations) for model interpretability.
4.  Assess and attempt to mitigate model bias using AIF360.
5.  Address class imbalance using SMOTE.
6.  Design a conceptual Power BI dashboard for stakeholder insights.

## Key Features

*   **Comprehensive Data Processing:** Includes handling missing values, outlier removal (IQR), log transformation, feature scaling (StandardScaler, MinMaxScaler), encoding (One-Hot, Label), and multicollinearity reduction.
*   **Class Imbalance Handling:** Implements SMOTE to create a balanced training dataset.
*   **Model Comparison:** Trains and evaluates Logistic Regression, Decision Tree (tuned), and XGBoost (tuned) using metrics like Accuracy, F1-Score, ROC-AUC, Precision, Recall, and Confusion Matrices.
*   **Cost-Sensitive Evaluation:** Assesses models based on hypothetical misclassification costs.
*   **Explainable AI (XAI):** Uses SHAP to understand feature contributions for the best-performing model (XGBoost).
*   **Fairness Assessment:** Employs the AIF360 toolkit to measure Disparate Impact and Statistical Parity Difference based on gender. Includes an experimental application of Reweighing for bias mitigation.
*   **Reproducibility:** Uses a fixed random seed (`seed=42`) for relevant operations.
*   **Visualization:** Generates various plots for EDA, model performance, SHAP explanations, and fairness metrics.
*   **Conceptual Dashboard:** Outlines the design and insights for a potential Power BI dashboard deployment (Chapter 7 of the dissertation).

