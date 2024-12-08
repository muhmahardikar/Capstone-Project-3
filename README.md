# Capstone-Project-3

# Predicting Customer Churn in Telco Company

## Overview
This project aims to build a machine learning model to predict customer churn in a telecommunications company. Customer churn refers to the loss of customers who stop using a company's services. Accurately predicting churn enables proactive retention efforts, reducing financial loss and improving customer satisfaction.

## Why is Customer Churn Important?
Customer churn has significant implications, including:

- **Financial Impact:**
  - Acquiring new customers is 5-25 times more expensive than retaining existing ones.
  - Lost recurring revenue from churned customers (e.g., $50/month per customer).
  - Negative brand reputation and potential market share loss.

- **Operational Challenges:**
  - Inefficient allocation of resources for mass retention programs.
  - Overworked retention teams dealing with non-priority cases.

## Project Objectives
The main objectives of this project are:

1. **Predict Churn:**
   - Develop a machine learning model to predict customers likely to churn.
   - Focus on identifying customers with a high probability of churn.

2. **Enable Proactive Actions:**
   - Provide early warnings for at-risk customers.
   - Optimize retention strategies and resource allocation.

## Data Overview
The dataset used contains information on 4,930 customers, with 10 features and 1 target variable (Churn: Yes/No). After preprocessing, the final dataset includes:

- **Numerical Features:**
  - Tenure (months of subscription).
  - MonthlyCharges (monthly fees).

- **Categorical Features:**
  - Dependents, OnlineSecurity, OnlineBackup, InternetService, DeviceProtection, TechSupport, Contract, PaperlessBilling.

- **Target Variable:**
  - Churn (Yes/No).

## Data Preprocessing
Key preprocessing steps included:

1. **Handling Duplicates:** Removed 77 duplicate records.
2. **Encoding Categorical Variables:** Applied label encoding and one-hot encoding.
3. **Scaling Numerical Features:** Standardized numerical values (Tenure and MonthlyCharges).
4. **Final Dataset:** Prepared a clean, numerical dataset with 16 features.

## Model Development
Three machine learning models were evaluated:

1. **Logistic Regression:**
   - Simple and interpretable.
2. **Random Forest:**
   - Powerful ensemble method using bagging.
3. **XGBoost:**
   - Gradient boosting for higher accuracy.

### Evaluation Metrics
- **Precision:** Accuracy of positive predictions.
- **Recall:** Sensitivity to actual churned customers.
- **F1-Score:** Balance between precision and recall.
- **ROC AUC Score:** Model's ability to distinguish between churn and non-churn customers.

## Model Improvement
Key improvement techniques included:

1. **Handling Imbalanced Data:** Used SMOTE (Synthetic Minority Oversampling Technique).
2. **Hyperparameter Tuning:** Optimized model parameters.
3. **Feature Analysis:** Identified and selected important features.

## Financial Impact Analysis
The final churn prediction model enables:

- Reduction in unnecessary retention costs.
- Improved customer satisfaction through timely interventions.
- Increased ROI by targeting at-risk customers effectively.

## Recommendations
- Integrate the model into the company's CRM system for real-time predictions.
- Regularly update the model with new customer data for improved accuracy.
- Use insights from feature importance analysis to tailor customer retention programs.

---

## Author
**Muhammad Mahardika Renaldi**

Thank you for exploring this project! For any questions or collaborations, feel free to reach out.

