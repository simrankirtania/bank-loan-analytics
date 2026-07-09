# 🏦 Bank Loan Risk Analytics

An end-to-end data analytics project that analyzes a bank's lending portfolio to evaluate lending performance, identify high-risk borrowers, build a predictive default model, and create an interactive executive dashboard.

This project follows a complete analytics workflow using **Excel, SQL Server, Python, and Power BI**, demonstrating how raw financial data can be transformed into actionable business insights.

---

# Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Dataset Description](#dataset-description)
- [Project Workflow](#project-workflow)
- [Phase 1: Data Cleaning (Excel)](#phase-1-data-cleaning-excel)
- [Phase 2: SQL Analysis](#phase-2-sql-analysis)
- [Phase 3: Python Analytics](#phase-3-python-analytics)
- [Phase 4: Power BI Dashboard](#phase-4-power-bi-dashboard)
- [Key Business Insights](#key-business-insights)
- [Business Recommendations](#business-recommendations)
- [Tools & Technologies](#tools--technologies)
- [Repository Structure](#repository-structure)
- [Dashboard Preview](#dashboard-preview)

---

# Project Overview

Banks approve thousands of loan applications every year, making effective credit risk management essential for maintaining a healthy lending portfolio.

This project analyzes historical loan data to answer important business questions, identify patterns associated with loan defaults, develop a predictive risk model, and present the results through an interactive Power BI dashboard.

The project demonstrates the complete analytics lifecycle from raw data cleaning to business intelligence reporting.

---

# Business Problem

The objective of this project is to help the bank:

- Monitor lending performance
- Understand portfolio quality
- Identify high-risk borrowers
- Improve underwriting decisions
- Reduce future loan defaults
- Build interactive executive reports for decision-making

---

# Dataset Description

The dataset contains **38,576 loan applications** and **27 variables** describing borrower demographics, loan characteristics, repayment information, and credit risk.

### Key Variables

- Loan Amount
- Interest Rate
- Annual Income
- Debt-to-Income Ratio (DTI)
- Employment Length
- Home Ownership
- Loan Purpose
- Loan Status
- State
- Installment
- Total Payment
- Risk Score
- Risk Segment
- Default Flag

---

# Project Workflow

```text
Raw Loan Dataset
        │
        ▼
Excel
• Data Cleaning
• Data Validation
        │
        ▼
SQL Server
• Portfolio KPIs
• Business Analysis
• Customer Segmentation
        │
        ▼
Python
• Exploratory Data Analysis
• Risk Analysis
• Predictive Modeling
        │
        ▼
Power BI
• Interactive Dashboard
• Executive Reporting
• Business Insights
```

---

# Phase 1: Data Cleaning (Excel)

The raw loan dataset was cleaned before analysis.

### Tasks Performed

- Checked missing values
- Verified duplicate records
- Standardized data formats
- Validated numerical columns
- Prepared the dataset for SQL analysis

---

# Phase 2: SQL Analysis

Microsoft SQL Server was used to answer business questions and analyze portfolio performance.

### Analysis Performed

- Portfolio KPIs
- Good Loan vs Bad Loan Analysis
- Loan Status Analysis
- Monthly Lending Trends
- Month-to-Date (MTD) Analysis
- Month-over-Month (MoM) Analysis
- State Analysis
- Loan Purpose Analysis
- Loan Term Analysis
- Employment Length Analysis
- Home Ownership Analysis

### SQL Concepts

- GROUP BY
- CASE WHEN
- Aggregate Functions
- CTEs
- Window Functions
- Ranking Functions
- Date Functions

---

# Phase 3: Python Analytics

Python was used to perform exploratory analysis, borrower risk analysis, and predictive modeling.

### Exploratory Data Analysis

- Loan Amount Distribution
- Interest Rate Distribution
- Debt-to-Income Ratio Distribution

### Risk Analysis

- Default Rate by Loan Purpose
- Default Rate by State
- Default Rate by Employment Length
- Default Rate by Home Ownership

### Statistical Analysis

- Correlation Matrix
- Risk Segmentation

### Predictive Analytics

Built a Logistic Regression model to predict borrower defaults.

### Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### Feature Importance

Identified the strongest factors influencing loan default.

---

# Phase 4: Power BI Dashboard

An interactive executive dashboard was developed to monitor lending performance and portfolio health.

### Dashboard Pages

### Executive Summary

- Portfolio KPIs
- Good vs Bad Loans
- Loan Status Overview

### Portfolio Overview

- Monthly Trends
- Geographic Analysis
- Loan Purpose Analysis
- Loan Term Analysis
- Employment Analysis
- Home Ownership Analysis

### Loan Details

Interactive loan-level reporting with dynamic filters.

### Dashboard Features

- Dynamic Slicers
- Drill-through Analysis
- DAX Measures
- Month-to-Date (MTD)
- Month-over-Month (MoM)

---

# Key Business Insights

- Over **86%** of issued loans are performing loans.
- Loan applications, funding, and repayments increased steadily throughout the year.
- Debt Consolidation is the most common borrowing purpose.
- Mortgage holders account for the largest borrower segment.
- Borrowers with longer employment histories contribute the highest repayments.
- Higher interest rates and debt-to-income ratios are associated with greater default risk.
- Predictive modeling successfully identifies borrowers with elevated credit risk before loan approval.

---

# Business Recommendations

- Strengthen underwriting for high-risk loan purposes.
- Monitor high-default states more closely.
- Apply enhanced screening for borrowers with higher credit risk indicators.
- Use borrower risk segmentation during loan approval.
- Incorporate predictive risk scoring into lending decisions.

---

# Tools & Technologies

- Microsoft Excel
- Microsoft SQL Server (MSSQL)
- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- Power BI
- DAX

---

# Repository Structure

```text
Bank-Loan-Risk-Analytics
│
├── financial_loan.csv
├── SQL Queries Analysis.pdf
├── Bank_Loan_Risk_Analysis.ipynb
├── Bank_Loan_Risk_Analytics.ipynb
├── Bank Loan power bi report.pbix
├── Bank Loan power bi report.pdf
├── README.md
├── LICENSE.txt
└── .gitignore
```

---

# Dashboard Preview

## Executive Summary

<img width="666" height="371" alt="Screenshot 2026-07-09 235254" src="https://github.com/user-attachments/assets/077e5bf2-5855-4cac-9dd6-52c00e296372" />


---

## Portfolio Overview

<img width="664" height="371" alt="Screenshot 2026-07-09 235314" src="https://github.com/user-attachments/assets/d4e785a2-90c3-4a49-84e7-5e9b1a6ef97c" />


---

## Loan Details

<img width="665" height="371" alt="Screenshot 2026-07-09 235330" src="https://github.com/user-attachments/assets/ed28b76f-8c8f-4f0b-a3d0-e40619c4c888" />


---

## ⭐ If you found this project helpful, consider giving it a star!
