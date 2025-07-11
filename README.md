📊 Customer Churn Prediction Using Machine Learning

This project analyzes customer behavior to predict whether a customer is likely to churn (i.e., stop using a service). The goal is to help telecom companies proactively retain customers by identifying those at risk.

📁 Dataset
The dataset used is the Telco Customer Churn dataset, which includes customer demographics, account information, and service usage patterns.

✅ Objective
To build and evaluate machine learning models that can classify whether a customer will churn or not, based on their profile and activity data.

🛠️ Project Workflow
Data Cleaning & Preprocessing

Handled missing values in TotalCharges

Encoded categorical variables

Scaled numerical features

Train-Test Split

80/20 split using train_test_split() with random_state=42

Modeling

Trained three models:

Logistic Regression

Random Forest

XGBoost

Evaluation: Compared accuracy, precision, recall, and F1-score

Analyzed confusion matrices

Selected the best model based on performance

🧪 Results
Model	Accuracy	Notes

Logistic Regression	80.6%	Best balance between churners and non-churners

Random Forest	78.2%	Struggled with recall for churners

XGBoost	78.6%	Slightly better precision for churners

📌 Final Model Chosen: Logistic Regression – simple, interpretable, and highest overall performance.

💾 Model File
The trained model is saved as:

customer_churn_logistic_regression.pkl

This can be loaded and used in future applications for churn prediction.
