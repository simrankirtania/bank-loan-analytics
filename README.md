# 🏦 Bank Loan Risk Analytics

An end-to-end data analytics project that analyzes **38,576 consumer loan records** to understand portfolio performance, identify default risk, build operational tools, and create an executive monitoring dashboard.

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Project Workflow](#-project-workflow)
- [Key Results](#-key-results)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Analysis Components](#-analysis-components)
- [Business Impact](#-business-impact)
- [How to Use](#-how-to-use)

## 📌 Project Overview

The project uses **SQL, Python, Advanced Excel, and Power BI**, with each tool answering a different business question:

- **SQL:** Portfolio performance and loan trends
- **Python:** Borrower risk analysis and default prediction
- **Excel:** Formula-driven operational tools
- **Power BI:** Interactive executive monitoring

The goal is to identify high-risk lending segments **before loans are funded**.

## 🔄 Project Workflow

```text
Raw Loan Data
    ↓
Data Cleaning & Validation
    ↓
SQL Portfolio Analysis
    ↓
Python Risk Analytics & Predictive Modeling
    ↓
Advanced Excel Analysis
    ↓
Power BI Dashboard
    ↓
Business Reporting
```

## 📊 Key Results

- **38,576** total loan applications
- **$435.8M** total funded amount
- **$473.1M** total amount received
- **86.2%** of loans classified as Good Loans
- **13.8%** classified as Charged Off
- Approximately **$28.2M net shortfall** from charged-off loans
- **Interest Rate and DTI** identified as the strongest default-risk drivers
- **Logistic Regression ROC-AUC: 0.687**
- **Random Forest ROC-AUC: 0.684**
- Charge-off rates increase from **5.7% for Grade A** to **31.3% for Grade G**
- **Small Business loans** were identified as disproportionately risky

## 🛠 Tools & Technologies

- **SQL:** SQLite
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning:** Logistic Regression, Random Forest
- **Excel:** SUMIFS, COUNTIFS, INDEX/MATCH, PMT, IPMT, PPMT, SUMPRODUCT, TEXTJOIN
- **Power BI:** DAX, MTD/MoM Measures, Interactive Slicers

## 📁 Project Structure

```text
Bank-Loan-Risk-Analytics/
│
├── 0. Data/
│   └── financial_loan.csv
│
├── 1. Notebooks/
│   ├── 1. Bank_Loan_SQL_Analysis_SQLite.ipynb
│   └── 2. Bank_Loan_Risk_Analysis_Python.ipynb
│
├── 2. Excel WorkBook/
│   ├── Bank_Loan_Advanced_Excel_Analysis.xlsx
│   └── Bank_Loan_Advanced_Excel_Analysis.pdf
│
├── 3. Power BI Dashboard/
│   ├── Bank Loan power bi report.pbix
│   └── Bank Loan power bi report screenshot.pdf
│
├── 4. Business Report/
│   └── Business_Questions_and_Answers.pdf
│
├── LICENSE.txt
└── README.md
```

## 🔍 Analysis Components

### SQL Portfolio Analysis

Analyzes:

- Portfolio KPIs
- Good vs. Bad Loans
- Monthly trends
- State, term, purpose, and employment analysis
- Credit grade performance

📓 [`Open SQL Notebook`](./1.%20Notebooks/1.%20Bank_Loan_SQL_Analysis_SQLite.ipynb)

### Python Risk Analytics & Modeling

Includes:

- Borrower risk profiling
- Correlation analysis
- Low/Medium/High risk segmentation
- Logistic Regression
- Random Forest
- Model evaluation and feature importance

📓 [`Open Python Notebook`](./1.%20Notebooks/2.%20Bank_Loan_Risk_Analysis_Python.ipynb)

### Advanced Excel Analysis

Includes:

- Formula-driven KPI Dashboard
- Risk Classification using DTI and Interest Rate
- Loan Amortization Calculator
- Advanced Lookups and Aggregations

📊 [`Open Excel Workbook`](./2.%20Excel%20WorkBook/Bank_Loan_Advanced_Excel_Analysis.xlsx)

### Power BI Dashboard

A 3-page interactive dashboard featuring:

- **Summary:** Portfolio KPIs and Good vs. Bad Loan metrics
- **Overview:** Trends, geography, purpose, term, and borrower segments
- **Details:** Transaction-level drill-down

📊 [`Open Power BI Report`](./3.%20Power%20BI%20Dashboard/Bank%20Loan%20power%20bi%20report.pbix)

## 💼 Business Impact

This project creates a complete workflow from historical loan data to decision-making:

**SQL** identifies where performance and losses occur →  
**Python** identifies which borrowers are most likely to default →  
**Excel** makes the analysis usable for non-technical teams →  
**Power BI** enables continuous management monitoring.

The result is a repeatable approach to support **better underwriting, risk-based decision-making, and portfolio monitoring**.

## 🚀 How to Use

1. Open the SQL and Python notebooks in **Jupyter Notebook/JupyterLab**
2. Open the Excel workbook in **Microsoft Excel**
3. Open the `.pbix` file in **Power BI Desktop**
4. Review the consolidated findings in the Business Report

## 📄 Business Report

For the complete business questions and findings:

📄 [`Business_Questions_and_Answers.pdf`](./4.%20Business%20Report/Business_Questions_and_Answers.pdf)

---

⭐ If you found this project useful, consider giving the repository a star!
