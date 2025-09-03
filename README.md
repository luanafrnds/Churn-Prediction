# Customer Churn Analysis & Prediction

Telco Customer Churn Prediction
🔎 Project Overview
This project aims to predict customer churn for a telecommunications company. By analyzing historical customer data, we can identify key factors that lead to churn and build a machine learning model to predict which customers are at risk. This allows the company to proactively intervene and retain valuable customers.

The primary goals of this project are:

To understand the main drivers of customer churn.

To build a predictive model that can identify at-risk customers with high accuracy.

To provide actionable insights for business stakeholders.



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

Correlations and statistical tests.

Churn rates segmented by contract type, internet service, and monthly charges.

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

The most important features for prediction were:

Contract type

Tenure

Internet service type

Monthly charges

Tech support availability



📌 Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
