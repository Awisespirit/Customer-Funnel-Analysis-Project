# 📊 Customer Churn Prediction & Analysis (Telecom Case Study)

## 🧠 Executive Summary

Customer churn is a critical challenge for subscription-based businesses, directly impacting revenue and growth.

In this project, I analyzed telecom customer data and built a **Logistic Regression model** to identify customers at risk of churning. The goal was to provide actionable insights that enable proactive retention strategies.

---

## 🎯 Business Problem

NexaSat, a telecom provider serving SMEs, faced increasing customer churn due to competitive market pressures and lack of targeted retention strategies.

The business needed a data-driven approach to:

* Identify customers at risk of churn
* Understand key drivers of churn
* Optimize retention and marketing efforts

---

## 📂 Dataset Overview

The dataset includes customer-level information such as:

* Demographics: Gender, Senior Citizen, Partner, Dependents
* Usage Metrics: Call Duration, Data Usage
* Subscription Details: Plan Type, Plan Level, Multiple Lines, Tech Support
* Financial Data: Monthly Bill Amount
* Lifecycle: Tenure (Months)
* Target Variable: Churn (0 = Active, 1 = Churned)

---

## ⚙️ Methodology

### 1. Data Preparation

* Cleaned dataset (duplicates, null values)
* Encoded categorical variables (Yes/No → 1/0)
* Selected relevant features

### 2. Exploratory Data Analysis

* Compared churn vs non-churn customers
* Analyzed churn across plan types, tenure, and services

### 3. Model Building

* Used **Logistic Regression** for binary classification
* Split data into training and testing sets
* Evaluated using classification metrics

---

## 🤖 Model Performance

* **Accuracy:** 63.9%

### Confusion Matrix:

|                 | Predicted No Churn | Predicted Churn |
| --------------- | ------------------ | --------------- |
| Actual No Churn | 135                | 79              |
| Actual Churn    | 63                 | 116             |

### Classification Metrics:

* Precision (Churn): 0.59
* Recall (Churn): 0.65
* F1-Score: 0.62

---

## 📊 Key Insights

* Customers with **shorter tenure** are more likely to churn
* **Basic plan users** show higher churn rates
* Customers without **tech support** are more likely to leave
* Higher monthly charges without added value increase churn risk

---

## 💡 Business Recommendations

* Improve onboarding experience for new customers
* Offer incentives for long-term subscriptions
* Bundle services (tech support, multiple lines)
* Target churn-risk customers with personalized offers
* Focus retention efforts on high-risk segments

---

## ⚖️ Model Evaluation & Business Trade-offs

In churn prediction, **recall is more important than accuracy**, as failing to identify a churned customer results in lost revenue.

This model achieved a recall of **65%**, making it effective for identifying at-risk customers.

Although precision is moderate, the cost of targeting additional customers is lower than the cost of losing them.

---

## 🔧 Model Improvement Opportunities

* Feature engineering (customer behavior trends)
* One-hot encoding for categorical variables
* Hyperparameter tuning
* Testing advanced models (Random Forest, Gradient Boosting)
* Handling class imbalance

---

## 📈 Business Impact

This model enables:

* Proactive churn prevention
* Improved customer retention
* Better marketing efficiency
* Increased customer lifetime value

---

## 🛠 Tools Used

* SQL (PostgreSQL)
* Python (Pandas, Scikit-learn)
* Excel

---

## 📎 Project Files

* SQL Analysis
* Python Model Notebook
* Dataset (Sample)

---

## 👤 Author

**Ayokunle Olokoyo**
Data Analyst | SQL • Python • Power BI
