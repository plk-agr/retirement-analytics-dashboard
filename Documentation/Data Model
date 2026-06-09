# Data Model

Overview

The Retirement Analytics Dashboard follows a dimensional data modeling approach optimized for analytical reporting in Google BigQuery.

The model consists of one dimension table and multiple fact tables that support retirement balance analysis, contribution tracking, investment allocation analysis, retirement readiness assessment, and transaction reporting.

---

Dimension Table

dim_employee

Stores employee master and demographic information used across all reporting views.

Purpose

Provides employee attributes for filtering, grouping, and drill-down analysis.

Fields

Field Name| Description
Employee_ID| Unique employee identifier
Employee_Name| Employee full name
Department| Employee department
Age_Group| Employee age category
Tenure_Category| Employee tenure classification

---

Fact Tables

fact_account_balance

Stores employee retirement account balances.

Purpose

Used to analyze retirement assets and retirement readiness.

Key Metrics

- Retirement Balance
- Account Value
- Balance Trends

---

fact_contributions

Stores employee retirement contribution records.

Purpose

Used to analyze contribution behavior and savings patterns.

Key Metrics

- Employee Contributions
- Employer Contributions
- Contribution Percentage

---

fact_fund_allocation

Stores investment allocation information.

Purpose

Used to evaluate portfolio composition and risk exposure.

Key Metrics

- Allocation Percentage
- Fund Distribution
- Risk Allocation

---

fact_digital_transactions

Stores retirement-related transaction activity.

Purpose

Used for transaction monitoring and activity reporting.

Key Metrics

- Transaction Amount
- Transaction Count
- Transaction Trends

---

fact_loan_withdrawals

Stores employee loan and withdrawal activity.

Purpose

Used to analyze retirement plan leakage and withdrawal behavior.

Key Metrics

- Loan Amount
- Withdrawal Amount
- Leakage Amount

---

Data Model Relationships

                    dim_employee
                          |
      -------------------------------------------------
      |           |            |           |          |
      |           |            |           |          |
fact_account_balance
fact_contributions
fact_fund_allocation
fact_digital_transactions
fact_loan_withdrawals

The Employee Dimension acts as the primary reporting dimension and is linked to all fact tables through Employee_ID.

---

Reporting Layer

The reporting layer consists of business-friendly views created in Google BigQuery to simplify dashboard development and reporting.

Reporting Views

vw_executive_summary

Provides high-level retirement plan performance metrics.

Includes:

- Total Employees
- Total Retirement Assets
- Total Contributions
- Average Contribution Percentage
- Total Leakage

---

vw_retirement_readiness

Provides employee retirement preparedness analysis.

Includes:

- Retirement Balance
- Contribution Percentage
- Readiness Classification

---

vw_investment_analysis

Provides investment allocation and portfolio risk insights.

Includes:

- Fund Allocation
- Risk Distribution
- Investor Profile Analysis

---

vw_transaction_analysis

Provides transaction activity reporting.

Includes:

- Transaction Trends
- Transaction Type Analysis
- Source System Analysis
- Withdrawal and Loan Activity

---

Design Benefits

- Simplified reporting architecture
- Faster dashboard performance
- Scalable BigQuery data model
- Consistent business metrics
- Easy integration with Looker Studio
- Supports drill-down and self-service analytics
