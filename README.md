# Churn-Prediction

elco Customer Churn Prediction
🔎 Project Overview

This project analyzes a Telco customer dataset to understand the drivers of customer churn (whether a customer leaves the service). The goal is to uncover business insights and build a machine learning model that can predict churn with high accuracy (>80%).

🎯 Objectives

Identify which features most strongly predict churn.

Explore customer behavior in relation to contract type, internet service, monthly charges, and tenure.

Test hypotheses such as:

Do long-term contracts reduce churn?

How does internet service type affect churn rates?

Are high-cost customers more likely to leave?

Build a classification model to predict churn and evaluate its performance.

📂 Dataset

The dataset includes customer demographics, account information, service subscriptions, billing, and churn labels.
Main features:

customerID, gender, SeniorCitizen, Partner, Dependents, tenure

PhoneService, MultipleLines, InternetService, OnlineSecurity, TechSupport

StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod

MonthlyCharges, TotalCharges, Churn

🛠️ Methods

Exploratory Data Analysis (EDA)

Correlations and statistical tests (Chi-square, correlation matrix).

Churn rates segmented by contract type, internet service, and monthly charges.

Machine Learning

Preprocessing: categorical encoding, train-test split.

Model: Random Forest Classifier with class balancing.

Evaluation: Accuracy, Precision, Recall, F1-score, ROC-AUC.

Feature importance analysis.

📈 Key Insights

Tenure is the strongest churn predictor → new customers churn more often.

Month-to-month contracts have the highest churn rate compared to long-term contracts.

Fiber optic customers, especially with medium-to-high monthly charges, churn more frequently.

Customers without TechSupport or OnlineSecurity are more likely to leave.

🤖 Model Performance

Random Forest achieved >80% accuracy with balanced precision and recall.

The most important features for prediction were:

Contract type

Tenure

Internet service type

Monthly charges

Tech support availability

🚀 Next Steps

Hyperparameter tuning for improved performance.

Try other models (Logistic Regression, Gradient Boosting, XGBoost).

Build a simple dashboard to visualize churn predictions.

📌 Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
