# 📊 Revenue Analysis & Data Cleaning (Excel Project)

End-to-end data cleaning and business analysis project using Excel, focused on solving real-world inconsistencies in transactional data and generating meaningful insights.

---

## 🎯 Business Context

In real-world datasets, inconsistencies in discount formats, tax calculations, and transaction statuses can lead to incorrect financial reporting.
This project focuses on identifying and resolving such issues to ensure accurate and reliable revenue analysis.

---

## 📌 Project Overview

This project demonstrates practical data analysis skills using Excel on a transactional dataset containing sales, discounts, tax logic, and customer activity.

### Key Objectives:

* Clean inconsistent and raw data
* Apply business rules using formulas
* Perform revenue analysis
* Generate insights using pivot tables and trends

---

## 🧹 Data Cleaning & Preparation

Several data quality issues were identified and handled:

* **Inconsistent Discount Format**
  The discount column contained both whole numbers (e.g., 15) and decimals (e.g., 0.15).
  → Standardized into a consistent percentage format.

* **Tax Inclusion Logic**
  Tax calculation varied depending on whether tax was already included.
  → Applied conditional formulas to correctly compute Net and Final amounts.

* **Mixed Transaction Status**
  Dataset included Active, Cancelled, Churned, and Paused transactions.
  → Filtered appropriately to ensure accurate analysis.

---

## ⚙️ Key Calculations

The dataset was enhanced using Excel formulas to derive meaningful metrics:

* Net Amount
* Tax Amount (based on tax inclusion logic)
* Final Amount
* Discount Normalization
* Month extraction from transaction date
* Customer behavior flag (Active + Cancelled/Churned)

---

## 📸 Dataset Snapshot

The dataset contains multiple attributes such as Region, Currency, Status, and Product Type.
Below is a focused sample showing key columns used for analysis.

![Dataset Overview](images/dataset_overview.png)

---

## 🔄 Discount Normalization

Converted inconsistent discount values into a standardized format to ensure accurate calculations.

![Discount Cleaning](images/discount_cleaning.png)

---

## 📊 Region-wise Analysis (Pivot Table)

A pivot table was used to evaluate regional performance.

**Key Finding:**
North region shows the highest average final amount per active transaction.

![Pivot Table](images/pivot_table.png)

---

## 📈 Monthly Revenue Trend

Revenue trends were analyzed over time using:

* Monthly Revenue
* Cumulative Revenue
* Month-over-Month (MoM) Growth

![Monthly Trend](images/monthly_trend.png)

---

## 📌 Key Insights

* North region generates significantly higher revenue compared to other regions, indicating strong market performance.
* Month-over-Month growth shows high volatility, suggesting inconsistent sales patterns.
* Data inconsistencies (especially in discount formats and tax logic) can significantly distort financial outcomes if not handled properly.
* Presence of customer churn alongside active transactions highlights potential retention opportunities.

---

## 🛠 Tools Used

* Microsoft Excel
* Pivot Tables
* Advanced Formulas (IF, SUMPRODUCT, COUNTIF, TEXT, etc.)

---

## 📁 Files Included

* `Revenue_Analysis_Project.xlsx` → Complete working file with formulas
* `/images` → Supporting screenshots for analysis

---

## 👤 Author

**Sanjay Renukuntla**
