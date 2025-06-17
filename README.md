# 📊 Customer Churn Analysis & Prediction Dashboard

This project simulates a full analytics pipeline to analyze customer churn behavior using OLAP-style exploration, predictive modeling with PyTorch, and an interactive Tableau dashboard.

---

## 🚀 Overview

This project aims to identify key drivers of customer churn in a telecom company and provide business-friendly insights using statistical analysis and machine learning. The project demonstrates:

- Data cleaning and warehouse-style dimensional modeling
- OLAP exploration (churn rates by contract, internet service, tenure, etc.)
- Predictive churn classification using a neural network (PyTorch)
- Key KPIs and trends visualized using Tableau

---

## 🧰 Tools Used

- **Python** (pandas, PyTorch, scikit-learn, SMOTE)
- **Tableau Public** for dashboards
- **GitHub** for version control and documentation

---

## 🔍 OLAP-Style Exploration (Examples)

	•	Churn Rate by Contract Type:
Compared churn rates across contract types (Month-to-month, One year, Two years), showing much higher churn among short-term users.
	•	Churn by Internet Service:
Analyzed churn rates for customers with DSL, Fiber optic, or No internet service, revealing fiber optic users are most likely to leave.
	•	Churn by Tenure Groups:
Grouped customers by tenure buckets (e.g., 0–12m, 13–24m, 25–48m, 49–72m) to identify how loyalty affects churn likelihood.
	•	Monthly Charges Bucket Analysis:
Created charge ranges (Low, Medium, High) from the MonthlyCharges column and explored how pricing tiers relate to churn behavior.

---

## 🤖 Predictive Modeling

The classification model was built with PyTorch and achieved:

- **Accuracy:** ~79%
- **F1-score for churners:** ~0.58
- **Balanced performance** using SMOTE and weighted loss

---

## 📈 Tableau Dashboard

The Tableau dashboard summarizes:

- KPI: Overall churn rate (%)
- KPI: Average monthly charges
- Visualizations by customer segments

![Dashboard Preview](images/dashboard_overview.png)

---


## 📚 Data Source

- [Telco Customer Churn Dataset (IBM Sample)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## ✍️ Author

Seokhyun Yoon (Sean)  
[LinkedIn](https://www.linkedin.com/in/seokhyun-yoon-241a61104/) | [GitHub Portfolio](https://github.com/SeanYooon/Data-Analysis-Portfolio-)

---
