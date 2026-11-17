# Telco Customer Churn - Data Cleaning & EDA

### Project Goal
Understand why telecom customers churn using real customer data.

### Dataset
- 7043 customers, 21 features
- Source: IBM Telco Customer Churn

### What I Did
- Cleaned `TotalCharges` (converted object to float64, fixed 11 missing values where tenure = 0)
- Validation: Duplicates = 0, Nulls = 0, Spaces = 0
- EDA on Churn vs: Tenure, MonthlyCharges, Contract type, Internet Service
- Handled class imbalance (26.5% churn rate)

### Key Findings
- Month-to-month contracts have highest churn
- Fiber optic users churn more
- New customers (low tenure) churn more

### Tools
Python, Pandas, Matplotlib, Seaborn

### Files
- `project1.ipynb`: Full analysis + Validation
