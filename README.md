# Retirement Analytics Dashboard

## Project Overview

This project demonstrates an end-to-end Retirement Analytics solution built using Google BigQuery, SQL, and Looker Studio.

The solution analyzes employee retirement savings, retirement readiness, investment allocations, and transaction activity.

---

## Technology Stack

- Google BigQuery
- SQL
- Looker Studio
- GitHub

---

## Data Model

### Dimension Table

#### `dim_employee`

### Fact Tables

#### `fact_account_balance`

#### `fact_contributions`

#### `fact_fund_allocation`

#### `fact_digital_transactions`

#### `fact_loan_withdrawals`

---

## Reporting Views

#### `vw_executive_summary`

#### `vw_retirement_readiness`

#### `vw_investment_analysis`

#### `vw_transaction_analysis`

---

## Dashboard Pages

### 1. Executive Summary Dashboard

Provides a high-level overview of retirement plan performance and participant metrics.

### 2. Retirement Readiness Dashboard

Analyzes employee retirement preparedness and savings progress.

### 3. Investment Analysis Dashboard

Provides insights into investment allocation and fund distribution trends.

### 4. Transaction Analysis Dashboard

Analyzes participant transaction activity and digital engagement.

### Sample Data

Contains CSV files.

---

## Repository Structure

```text
retirement-analytics-dashboard/
│
├── documentation/
├── sql/
├── dashboard_screenshots/
├── dashboard_exports/
├── sample_data/
└── architecture/
```

### Folder Description

| Folder | Description |
|----------|-------------|
| documentation | Project documentation |
| sql | SQL scripts, transformations, and reporting views |
| dashboard_screenshots | Dashboard screenshots |
| dashboard_exports | Exported dashboard files |
| sample_data | Sample datasets |
| architecture | Solution architecture diagrams |

---

## Solution Components

### Data Warehouse

Google BigQuery is used to store and process retirement analytics data.

### Data Transformation

SQL scripts are used to create dimension tables, fact tables, and reporting views.

### Reporting Layer

Reporting views provide business-ready datasets for dashboard consumption.

### Visualization Layer

Looker Studio dashboards provide interactive reporting and analytics.

---

## Dashboard Coverage

- Executive Summary
- Retirement Readiness Analysis
- Investment Allocation Analysis
- Transaction Activity Analysis

---

## Project Objectives

- Analyze employee retirement savings behavior
- Measure retirement readiness across participants
- Evaluate investment allocation trends
- Monitor contribution activity
- Analyze digital transaction engagement
- Track loan and withdrawal activity

---

## Screenshots

Dashboard screenshots are available in the `dashboard_screenshots` folder.

---

## Architecture

Solution architecture diagrams are available in the `architecture` folder.
