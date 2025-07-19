# 📊 Customer Churn Analysis Dashboard — Excel Project

This project presents an interactive dashboard that analyzes telecom customer churn using Microsoft Excel. It provides actionable insights into customer behavior, helping businesses understand why customers leave and how to reduce churn.

---

## 🚨 Problem Statement

Customer churn is a major concern for subscription-based businesses. Reducing churn can significantly improve profitability. This dashboard explores churn patterns to:

- Identify high-risk segments
- Analyze patterns by gender, service, contract, and charges
- Make data-driven retention decisions

---

## 📂 Dataset Overview

- **Name:** Telco Customer Churn
- **Source:** Kaggle / IBM Sample Dataset
- **Format:** CSV imported into Excel
- **Records:** ~7,000 customer records
- **Key Columns:**
  - `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - `tenure`, `PhoneService`, `InternetService`, `Contract`, etc.
  - `MonthlyCharges`, `TotalCharges`, `Churn`

---

## 🎯 Project Objectives

- Create a professional **Excel Dashboard**
- Analyze customer churn trends
- Use **Pivot Tables**, **Slicers**, and **KPIs**
- Provide clear insights to reduce churn

---

## 📌 Features Implemented

### ✅ Dashboard Components:
- **Pivot Tables** and **Pivot Charts** for dynamic analysis
- **Slicers** for filtering:
  - Gender
  - Internet Service
  - Contract Type
  - Senior Citizen Status
- **Interactive Charts**: Bar chart, Pie chart, and Line chart views

### ✅ Key Performance Indicators (KPIs):
- **Total Customers** → `=COUNTA('Churn by Gender'!A:A)`
- **Churned Customers** → `=COUNTIF(telco_customer_churn!W:W, "Yes")`
- **Average Monthly Charges** → `=IFERROR(AVERAGEIF('Churn by Gender'!T:T, ">0"), "No Data")`

🛠 All KPIs update dynamically with slicer selections.

---

## 🔍 Insights Extracted

- Senior citizens have a higher churn rate.
- Month-to-month contract users are more likely to leave.
- Customers without dependents and partners are at higher churn risk.
- Fiber optic users churn more compared to DSL users.
- Higher monthly charges correlate with increased churn.

---

## 🛠 Tools & Skills Used

- **Microsoft Excel**
- Pivot Tables & Pivot Charts
- Excel Slicers
- Formulas: `COUNTIF`, `AVERAGEIF`, `IFERROR`, `COUNTA`
- Data Cleaning (TotalCharges, blanks, text-to-numeric)
- Dashboard design (layout, color coding, readability)

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `telco_customer_churn.csv.xlsx` | Main working Excel file with dataset, pivot tables, and dashboard |
| `dashboard_screenshots/` | Folder with dashboard screenshots |
| `README.md` | Documentation file (this file) |

---

## 🚀 Future Enhancements

- Build a Python version using Pandas, Matplotlib & Seaborn
- Perform full **EDA (Exploratory Data Analysis)**
- Apply Machine Learning models (Logistic Regression, Decision Trees) to **predict churn**
- Deploy the ML model using Streamlit or Flask

---

## 🧠 What I Learned

- How to analyze data using Excel
- Creating clean, dynamic dashboards
- Visualizing data for decision-makers
- Building KPIs and resolving formula issues
- Storytelling using visual data elements

---

## ▶️ How to Use This Project

1. Download the `.xlsx` file
2. Open it in **Microsoft Excel**
3. Explore the dashboard and use **slicers** to filter by gender, internet type, contract, etc.
4. Hover over visuals to view insights
5. View KPIs to get quick churn metrics

---

## 📬 Connect with Me

Let’s connect professionally!

- 🔗 [LinkedIn] : (https://www.linkedin.com/in/riya-sharma20/)
- 📧 Email: riyaasharma0020@gmail.com
- 🗃️ GitHub: https://github.com/riyasharma0020

---

> 💡 _If you like this project, consider giving it a ⭐ and sharing your feedback!_
