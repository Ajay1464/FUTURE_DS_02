# FUTURE_DS_02 - Telco Customer Churn Analysis (Power BI)

## 📌 Project Overview
This project focuses on **Customer Retention & Churn Analysis** using the **Telco Customer Churn dataset**.
The goal is to identify **why customers unsubscribe (churn)**, understand churn patterns, and provide actionable business insights to reduce churn.

---

## 🎯 Objectives
- Analyze churn (Yes/No) behavior across customers
- Calculate **Churn Rate %** and key retention metrics
- Identify churn drivers such as:
  - Contract type
  - Payment method
  - Tenure (customer lifetime)
  - Services used (Internet, Phone, Online Security, Streaming, etc.)
- Provide business recommendations to improve retention

---

## 🛠 Tools Used
- **Power BI**
- Microsoft Excel (optional for data checking)
- Telco Customer Churn Dataset (CSV)

---

## 🧹 Data Cleaning Steps
- Removed duplicate customer records
- Checked and handled missing/null values
- Fixed data types (especially `TotalCharges`)
- Created additional columns for better churn analysis (Tenure Groups, etc.)
- Verified churn values (Yes/No) for correct segmentation

---

## 📊 Key Measures (DAX)
**Total Customers**
```DAX
Total Customers = COUNTROWS('WA_Fn-UseC_-Telco-Customer-Churn')
