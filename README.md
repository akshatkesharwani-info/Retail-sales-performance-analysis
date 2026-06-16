# 🛒 Retail Sales Performance Analysis

**Suggested repo name:** `retail-sales-performance-analysis`
**Maps to your existing repo:** `retail_sales_analys` — rename it to the name above.

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
A national retail chain wants an executive-level analysis of its 4-year sales history — which products, regions and customer segments drive revenue and profit, with actionable recommendations attached.

## Dataset
- Superstore Sales Dataset — [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Tech Stack
Python · Pandas · SQL-style analysis · Excel (openpyxl) · Matplotlib · Seaborn

## Approach
1. Loaded and inspected the dataset, converted dates, derived Year/Month/Quarter/Profit Margin
2. Calculated core business KPIs — total sales, total profit, average discount, profit margin
3. Ran SQL-style groupby analysis: sales/profit by Region, Sub-Category and Segment
4. Performed seasonal analysis to find peak and low sales months/quarters
5. Built a 6-panel visualization dashboard (regional sales, sub-category profit, monthly trend, discount-vs-profit, category×segment, profit-margin heatmap)
6. Exported summary tables to a multi-sheet Excel report for stakeholders

## Key Results & Insights
- West region leads in total sales, but Central has the lowest profit margin overall
- Furniture sub-categories like Tables and Bookcases are running at a loss
- Higher discounts correlate strongly with lower profit — a clear downward trend
- Q4 (Oct–Dec) consistently shows the highest sales across all years — holiday effect
- Consumer segment drives 51% of total sales, but Corporate has the higher average order value

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook retail_sales_analysis.ipynb
```

## Project Structure
```
retail-sales-performance-analysis/
├── notebooks/retail_sales_analysis.ipynb
├── reports/superstore_report.xlsx
├── images/retail_dashboard.png
├── requirements.txt
└── README.md
```

## Author
Akshat Kesharwani — [LinkedIn](https://linkedin.com/in/akshat-kesharwani-b0452b346) · [Portfolio](https://akshatkesharwani-info.github.io)
