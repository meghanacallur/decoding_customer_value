# Decoding Customer Value - A SQL-Driven Retention Strategy

## Overview
An end-to-end data analytics project for a direct-to-consumer fashion brand with ~3,900 customers. The goal: identify what the brand's most valuable customers look like, measure how much revenue depends on promotions, and build a data-backed retention strategy that reduces discount dependency without hurting sales.

## Business Question
> Is the business successfully building a loyal customer base, or is it reliant on continuous promotional activity to drive sales?

## Project Structure
├── 01_Feature_Engineering.ipynb   # Data cleaning + engineered features
├── 02_SQL_Queries.ipynb           # Segmentation queries answering 3 core business questions
├── SQL_Results/                   # Exported query outputs (CSV)
├── engineered_dataset.csv         # Cleaned dataset with engineered features
├── dashboard.pbix                 # Power BI founder dashboard (4 panels)
└── Retention_Playbook.pdf         # Promotional sunset plan + ideal customer profile

## Key Findings
- Only 6.5% of customers fall in the High Value tier — revenue base is concentrated and fragile
- Promo dependency inversely correlates with value: high-value customers have 3x lower dependency than low-value customers
- Clothing and Accessories are retention anchors; Spring is the strongest acquisition window
- 29 out of 50 states show organic demand — genuine brand pull without discounts

## Tools Used
- **Python** — data cleaning, feature engineering (pandas, scikit-learn)
- **SQL** — customer segmentation via SQLite
- **Power BI** — founder dashboard (4-panel)

## Deliverables
| Deliverable | Description |
|---|---|
| Python | Cleaned dataset + 6 engineered features |
| SQL | 4 segmentation queries answering core business questions |
| Power BI | Four-panel founder dashboard |
| Playbook | Promotional sunset plan + ideal customer profile |
| Summary | Executive summary of findings and recommendations |
