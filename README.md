#  Customer Churn Analysis & Prediction

An end-to-end **Data Analytics & Machine Learning** project that predicts customer churn using **SQL Server, Python, Random Forest, Excel, and Power BI**. This project demonstrates the complete workflow from data preparation and machine learning to interactive business dashboards.

---

##  Tech Stack

- SQL Server
- Python (Pandas, NumPy, Scikit-learn)
- Random Forest Classifier
- Excel
- Power BI

---

##  Project Workflow

###  Data Preparation (SQL Server)
- Cleaned and transformed customer data using excel .
- Created **vw_ChurnData** for training the ML model.
- Created **vw_JoinData** for predicting churn on new customer data.

###  Machine Learning (Python)
- Trained a **Random Forest Classifier** using `vw_ChurnData`.
- Performed data preprocessing and label encoding.
- Predicted customer churn using `vw_JoinData`.
- Exported predicted churn customers to **Predictions.xlsx**.

###  Dashboard (Power BI)
- Imported SQL data and `Predictions.xlsx`.
- Created interactive dashboards to analyze customer behavior, churn trends, and predicted churn customers.

---

##  Project Files

| File | Description |
|------|-------------|
| `SQLQuery.sql` | SQL queries for data preparation |
| `vw_ChurnData.sql` | SQL View used for model training |
| `vw_JoinData.sql` | SQL View used for churn prediction |
| `prediction.py` | Random Forest training & prediction script |
| `Predictions.xlsx` | Output file containing predicted churn customers |
| `CUSTOMER_CHURN_ANALYSIS.pbix` | Power BI Dashboard |

---

#  Dashboard Preview

## Dashboard 1

<p align="center">
  <img src="Screenshot 2026-07-12 171314.png" width="900">
</p>

---

## Dashboard 2

<p align="center">
  <img src=""C:\Users\chira\OneDrive\Pictures\Screenshots\Screenshot 2026-07-12 171332.png"" width="900">
</p>

---

## 🚀 Project Workflow

```text
Customer Data
      │
      ▼
 SQL Server
      │
 ├── vw_ChurnData
 ├── vw_JoinData
      │
      ▼
Random Forest Model
(prediction.py)
      │
      ▼
Predictions.xlsx
      │
      ▼
Power BI Dashboard
```

---

## ✨ Key Features

- SQL Data Cleaning & Transformation
- Machine Learning using **Random Forest**
- Customer Churn Prediction
- Interactive Power BI Dashboard
- End-to-End Analytics Pipeline
- 
