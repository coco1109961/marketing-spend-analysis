# marketing-spend-analysis
## Overview
This project analyzes multi-channel marketing spend data to understand budget allocation patterns and ensure data consistency between reported total investment and channel-level spend.

The analysis focuses on validating data quality, identifying discrepancies, and generating actionable insights into marketing strategy and channel effectiveness.

---

## Business Question
- How is marketing budget allocated across different channels?
- Is the reported total investment consistent with the sum of channel-level spend?
- What do discrepancies reveal about data quality and budget reporting?

---

## Data Source
- Dataset: Marketing Spend Dataset (Kaggle)
- Time period: 2015–2016
- Granularity: Monthly marketing investment by channel

---

## Data Validation & Quality Checks
Before conducting analysis, the dataset was validated by reconciling total investment against the sum of channel-level spend for each month.

### Validation Steps:
- Calculated channel-level spend sum per month
- Compared channel sum with reported total investment
- Classified discrepancies into:
  - **Rounding difference** (minor numerical differences due to rounding)
  - **Unallocated value** (potential missing or undistributed budget)

### Key Findings:
- Most discrepancies were attributable to rounding differences
- Only a small number of months showed evidence of unallocated marketing spend

To ensure analytical accuracy, subsequent analysis focuses on months where discrepancies are caused by rounding differences.

---

## Analysis Scope
- Channel-level budget allocation
- Relative contribution of each marketing channel
- Identification of dominant channels and spending patterns

---

## Tools Used
- Microsoft Excel (data validation, reconciliation, aggregation)
- GitHub (project documentation and version control)

---

## Key Insights
- Sponsorship and online marketing account for a significant share of total marketing spend
- Performance-driven channels such as SEM and Affiliates play a consistent supporting role
- Budget allocation suggests a strategic balance between brand-building and performance marketing

---

## Project Structure
