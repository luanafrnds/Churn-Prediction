# Customer Churn Analysis & Prediction

Telco Customer Churn Prediction

🔎 Project Overview

This project aims to predict customer churn for a telecommunications company. By analyzing historical customer data, we can identify key factors that lead to churn and build a machine learning model to predict which customers are at risk. This allows the company to proactively intervene and retain valuable customers.

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Modeling](#modeling)
5. [Results](#results)
6. [Insights](#insights)
7. [How to Run](#how-to-run)
8. [Technologies](#technologies)
9.[Tools & Libraries](#technologies)



## Overview
Customer churn is a major challenge in the telecom industry.  
This project applies Exploratory Data Analysis (EDA), statistical tests, and machine learning to predict which customers are at risk of leaving.  
By identifying key factors influencing churn, telecom companies can improve retention strategies and reduce revenue loss.

---
## Dataset
- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- Rows: 7,043 customers
- Features: 21 variables (customer demographics, services, charges, contracts, etc.)
- Target: `Churn` (Yes/No)

---
## Exploratory Data Analysis
Some key findings:
- Customers with **month-to-month contracts** are much more likely to churn.
- **High monthly charges** are strongly associated with churn.
- Longer **tenure** reduces churn likelihood.

---
### Example Visuals:
- Distribution of churned vs. retained customers
- Churn rate by contract type
- Correlation heatmap

---

## Modeling
- Logistic Regression → Baseline model
- Random Forest → Improved performance
- Gradient Boosting (XGBoost/LightGBM) → Best results

---
### Evaluation Metrics:
- Accuracy: 82%
- Precision: 79%
- Recall: 85%
- ROC-AUC: 0.88

---
## Results
- The model can correctly identify most customers at risk of churn.

  **Top features influencing churn:**
  1. Contract type
  2. Monthly charges
  3. Tenure
  4. Tech support availability
  5. Internet service type

---
## Insights
- Encourage customers to switch from month-to-month to annual contracts.
- Offer discounts to high monthly charge customers.
- Provide bundled services (tech support, security) to reduce churn.
---

## Insights

-Tenure is the strongest churn predictor → new customers churn more often.
-Month-to-month contracts have the highest churn rate compared to long-term contracts.
-Fiber optic customers, especially with medium-to-high monthly charges, churn more frequently.
-Customers without TechSupport or OnlineSecurity are more likely to leave.



---

### **Technologies**

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib & Seaborn (visualizations)
- Jupyter Notebook
- (Optional) Streamlit for deployment




## Tools & Libraries

-Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
