End-to-End Bank Loan Risk Analytics Project
Project Overview
This project analyzes a consumer lending portfolio using SQL, Python, and Power BI to identify business trends, evaluate credit risk, and build a predictive model for loan defaults.
The objective is to transform raw lending data into actionable business insights that support lending decisions, risk management, and portfolio monitoring.

Business Problem
Financial institutions must balance loan growth with credit risk.
This project answers three key questions:
1. How is the loan portfolio performing?
2. Which borrower segments are most likely to default?
3. How can decision-makers monitor risk and lending performance?

Project Workflow
Raw Loan Data (CSV)
?
SQL Analysis
?
Python Risk Analytics & Machine Learning
?
Power BI Executive Dashboard
?
Business Recommendations

Tools & Technologies
* SQL Server
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Power BI
* GitHub

Dataset
The dataset contains approximately 38,000 loan records with borrower demographics, loan characteristics, repayment history, and loan status information.
Key fields include:
* Loan Amount
* Interest Rate
* Annual Income
* Debt-to-Income Ratio
* Employment Length
* Home Ownership
* Loan Purpose
* Loan Status

SQL Analysis
The SQL phase focused on portfolio performance analysis.
Key Metrics
* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average DTI
* Good Loan vs Bad Loan Analysis
Key Findings
* 86.2% of loans were classified as Good Loans.
* Total funded amount exceeded $435M.
* Total repayments exceeded $473M.
* Loan demand and repayments increased steadily throughout the year.
* California, New York, Texas, and Florida were the largest lending markets.

Python Analytics
Python was used for exploratory analysis, risk segmentation, and predictive modeling.
Exploratory Analysis
* Loan Amount Distribution
* Interest Rate Distribution
* Borrower Segment Analysis
* Default Rate Analysis
* Correlation Analysis
Risk Segmentation
Borrowers were grouped into:
* Low Risk
* Medium Risk
* High Risk
High-risk borrowers exhibited approximately double the default rate compared to low-risk borrowers.
Predictive Modeling
A Logistic Regression model was trained to predict loan defaults using:
* Annual Income
* Loan Amount
* Interest Rate
* Debt-to-Income Ratio
* Installment
* Total Accounts
Model Performance
* Accuracy: ~63%
* ROC-AUC: ~0.69
Key Risk Drivers
1. Interest Rate
2. Debt-to-Income Ratio
These variables had the strongest relationship with default risk.

Power BI Dashboard
The Power BI dashboard provides interactive portfolio monitoring.
Dashboard Pages
Summary
* Portfolio KPIs
* Good vs Bad Loan Performance
* Loan Status Overview
Overview
* Monthly Trends
* Geographic Analysis
* Purpose Analysis
* Employment Analysis
* Home Ownership Analysis
Details
* Transaction-Level Loan Information

Business Insights
Portfolio Performance
* The portfolio remains healthy with 86.2% performing loans.
* Repayments exceed funded amounts, indicating positive portfolio returns.
Borrower Behavior
* Debt Consolidation is the most common loan purpose.
* Mortgage holders form the largest borrower segment.
* Borrowers with 10+ years of employment demonstrate stronger repayment behavior.
Credit Risk
* Small Business loans show elevated default risk.
* Higher Interest Rates strongly correlate with default probability.
* Higher Debt-to-Income ratios increase borrower risk.

Recommendations
1. Strengthen underwriting for high-risk loan purposes.
2. Closely monitor borrowers with high DTI ratios.
3. Incorporate predictive risk scoring into approval workflows.
4. Expand lending efforts in high-performing states.
5. Use borrower segmentation to improve pricing and risk management.
Repository Structure
??? Data
? ??? financial_loan.csv
??? SQL
? ??? SQL Queries Analysis.pdf
??? Python
? ??? Bank_Loan_Risk_Analytics.ipynb
??? PowerBI
? ??? Power BI Dashboard.pbix
? ??? Dashboard Screenshots
??? README.md
??? Project_Report.pdf

Author
Simran Kirtania
M.Sc. Economics | Data Analytics | SQL | Python | Power BI
