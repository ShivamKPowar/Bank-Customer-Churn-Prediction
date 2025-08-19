# Bank-Customer-Churn-Prediction
Data Analysis project on Bank Customer Churn. Covers exploratory data analysis (EDA), data preprocessing, feature engineering, visualization, model building (Logistic Regression &amp; Random Forest), feature importance analysis, and business insights to improve customer retention strategies.
# Project Overview
Customer churn is a critical challenge in the banking industry. This project focuses on building a machine learning model to predict which customers are likely to leave the bank. By identifying at-risk customers early, banks can take proactive steps to retain them, reduce revenue loss, and improve customer satisfaction.
# Objectives
* Analyze customer demographic, financial, and behavioral data.
* Build and evaluate multiple ML models for churn prediction.
* Identify the key drivers of churn using feature importance.
Dataset
The dataset includes the following key variables:
* Demographics – Age, Gender, Geography
* Financials – Balance, Estimated Salary, Credit Score
* Customer Behavior – Tenure, Active Member, Has Credit Card, Product Number
* Target Variable – Churn (Exited: 0 = No, 1 = Yes)
# Project Workflow
1. Data Preprocessing
   * Handle missing values & duplicates
   * Encode categorical variables (Gender, Geography)
   * Feature scaling (StandardScaler)
2. Exploratory Data Analysis (EDA)
   * Churn distribution analysis
   * Correlation heatmaps
   * Geography & Gender churn trends
3. Model Building
   * Logistic Regression
   * Random Forest
4. Hyperparameter Tuning
   * GridSearchCV for best parameters
   * Adjusted probability threshold (0.3) for higher recall
5. Model Evaluation
   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix
