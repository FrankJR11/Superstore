# Superstore Sales Analysis

## Brief Background
The Superstore dataset is a retail transactions benchmark covering a US office supplies retailer. It contains orders, products, customers, discounts, profits, shipping, and regions. This analysis explores sales performance, profitability levers, and operational insights.

## Project Overview
- Scope: End-to-end exploratory analysis of historical Superstore transactions.
- Focus: Top-selling products, trends over time, regional performance, and core KPIs.
- Deliverables: Reproducible notebook(s), summary charts, and CSV exports of key aggregations.

## Dataset Source
- Kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Objectives
- Quantify sales by product, category, and region.
- Identify top-selling products and underperformers.
- Examine monthly and yearly sales trends.
- Surface regions with highest sales and growth opportunities.
- Produce clean, reusable outputs.

## Exploration Questions
- What are the top-selling products and categories?
- How do sales trend monthly and yearly?
- Which regions generate the most revenue?
- Where do discounts help or hurt profit?
- Which ship modes are most used and do they impact sales?

## Tools and Technologies
- Python (pandas, matplotlib, seaborn)

## Approach
1. Data loading and light cleaning (types, dates, text normalization).
2. Build aggregations for products, time, and region.
3. Visualize monthly trends and yearly totals.
4. Export CSVs for downstream use.

## Key Results (from this run)
- Top sellers identified and saved to top_selling_products.csv.
- Monthly and yearly sales computed and exported.
- Region sales leaderboard created (West leads in this sample).

## Outputs (generated files)
- top_selling_products.csv
- monthly_sales.csv
- yearly_sales.csv
- region_sales.csv
