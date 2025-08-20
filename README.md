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
# Key Insights
1. Age – Older customers are most likely to churn.
2. Balance & Salary – High-value customers are more prone to switching banks.
3. Credit Score – Lower scores correlate with higher churn.
4. Product Number – Churn risk varies by product type. For example, customers linked only to Product 1 may have higher churn, while those with Product 3 or 4 tend to be stickier. This suggests that some products naturally create stronger customer loyalty than others.
5. Activity – Inactive customers have higher churn rates.
6. Demographics (Gender, Geography) – Minimal impact.
# Business Recommendations
* Focus on older, high-balance customers with loyalty programs.
* Product-Specific Retention – Since churn varies by product type, cross-sell and upsell sticky products to customers holding only high-churn products. This increases long-term engagement and loyalty.
* Boost engagement through mobile/app campaigns.
* Provide credit support for customers with lower scores.
* Tailored retention strategies for German customers
# Tech Stack
* Language: Python
* Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* Modeling: Logistic Regression, Random Forest
* Visualization: Feature importance plots, EDA charts
# Business Impact
By deploying this churn prediction model, the bank can:
* Reduce customer attrition with targeted interventions.
* Improve Customer Lifetime Value (CLV) by retaining high-value clients.
* Adopt data-driven decision making for customer retention strategies.
# Contributing
Contributions are welcome! Feel free to fork this repo, raise issues, and submit pull requests.
