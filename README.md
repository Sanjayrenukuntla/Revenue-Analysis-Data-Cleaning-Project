# 📊 Revenue Analysis & Data Cleaning Project

## 🔍 Overview

This project focuses on cleaning and analyzing a transactional dataset using Excel.
The goal was to transform inconsistent raw data into a structured format suitable for business insights.

---

## ⚠️ Data Issues Identified

* Inconsistent discount formats (decimal vs percentage)
* Complex tax inclusion logic
* Presence of non-active transactions affecting analysis

---

## 🛠 Data Cleaning Steps

* Standardized discount values into consistent percentage format
* Applied conditional logic for tax calculation
* Filtered relevant records for accurate analysis
* Created calculated columns:

  * Net Amount
  * Tax Amount
  * Final Amount
  * Normalized Discount
  * Month extraction
  * Customer status flag

---

## 📊 Analysis Performed

### 1. Region Summary

* North region has the highest average final amount per active transaction

### 2. Monthly Trend

* Revenue shows high fluctuations with sharp growth and decline periods
* Significant spike observed in Jan-2025

---

## 📸 Sample Dataset (Cleaned)

The dataset contains multiple fields such as Region, Currency, Product Type, and Status.
Below is a focused sample showing key columns used for analysis.

![Dataset Sample](images/dataset_processed.png)

---

## 📊 Region Summary (Pivot Table)

![Region Summary](images/region_summary.png)

---

## 📈 Monthly Trend Analysis

![Monthly Trend](images/monthly_trend.png)

---

## 💡 Key Insights

* Data inconsistency directly impacts financial calculations
* Filtering only active transactions improves accuracy
* Revenue trend shows volatility, indicating possible seasonality or inconsistent sales

---

## 🧰 Tools Used

* Microsoft Excel
* Pivot Tables
* Advanced formulas (SUMPRODUCT, IF, COUNTIF)

---

## 📁 Files

* `Revenue_Analysis_Project.xlsx` → Full working file with formulas
* `images/` → Screenshots used in documentation

---

## 🚀 Outcome

Successfully transformed messy transactional data into structured insights using Excel-based data cleaning and analysis techniques.
