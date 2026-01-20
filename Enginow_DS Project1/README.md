**Enginow: Customer Churn Analysis Using Machine Learning**

## Project Objective
The primary goal of this project is to predict whether a customer is likely to stop using a service (churn) based on their behavioral, demographic, and service-related factors. This is a classic industry problem used across telecom, banking, SaaS, and e-commerce to improve customer retention.

## Dataset Overview
The analysis is performed on a structured customer dataset containing the following key attributes:

Demographics: Gender, Age.
Service Details: Tenure, Phone Service, Internet Service, Contract Type.
Financials: Monthly Charges, Total Charges.
Target Variable: Churn (Yes/No).

## Expected Workflow
The project follows a rigorous data science pipeline:

1. Data Preprocessing
Handled missing and incorrect values in the TotalCharges column.
Converted categorical data into numerical format using Label Encoding.
Scaled numerical features to improve model performance.

2. Exploratory Data Analysis (EDA)
Analyzed the distribution of churners to understand the baseline churn rate.
Investigated the relationship between Contract Type and churn.
Generated Correlation Heatmaps to identify relationships between service usage and retention.
Assessed the Revenue Impact of churned customers.

3. Classification Modeling
Built and evaluated multiple classification models to find the most accurate predictor:
Logistic Regression
Decision Tree
Random Forest

Evaluation Metrics used:
Accuracy 
Precision & Recall 
Confusion Matrix 

## Key Business Insights
Contract Influence: Customers on month-to-month contracts exhibit significantly higher churn risk.
Top Factors: Identified the most influential factors driving customer exit.
Retention Strategy: Recommendations provided to reduce churn and improve customer lifetime value.

## Skills Gained
Classification Modeling 
Exploratory Data Analysis (EDA) 
Business Analytics Thinking 
Understanding Customer Risk Patterns 

## Project Deliverables
Jupyter Notebook: Contains all clean, commented code and logic.
Visualizations: In-depth analysis of patterns and service usage.
Performance Report: Detailed metrics for the classification models.
Actionable Insights: 4-5 key findings to help businesses retain high-risk segments