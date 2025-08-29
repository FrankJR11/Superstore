# Superstore
Superstore Dataset Analysis 


**Background**

The Superstore dataset is a popular retail-sales benchmark containing transactional records for a US office supplies retailer. It includes orders, customers, products, and shipping details across regions. This project explores sales performance, profitability, and trends to surface actionable insights for merchandising and operations.


**Project Overview**

Scope: End-to-end exploratory data analysis on historical Superstore transactions.
Focus Areas: Top-selling products, sales trends over time, regional performance, and foundational KPIs.
Deliverables: Cleaned data pipeline, reproducible notebooks, summary visuals, and CSV exports of key aggregations.
Dataset Source
Kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final


**Project Objectives**

Quantify total sales and profitability at product, category, and regional levels.
Identify top-selling products and high/low-performing segments.
Examine monthly and yearly sales trends.
Highlight regions with the highest sales and opportunities for growth.
Provide clean outputs for stakeholders and downstream analysis.
Exploration Questions
Which products generate the highest total sales?
What does the sales trend look like monthly and yearly?
Which regions contribute the most revenue?
How concentrated are sales across categories and sub-categories?
Are there seasonal spikes worth planning for?
Tools & Technologies
Language: Python
Core libraries: pandas, matplotlib, seaborn
Environment: Jupyter Notebook
File formats: CSV (inputs/exports), PNG (plots)


**Approach**

Data Ingestion: Load the Superstore CSV and standardize column names.
Data Cleaning:
Handle duplicate date columns and mixed date formats.
Coerce numeric fields (e.g., Sales) and drop irrecoverable records where necessary.
Feature Engineering:
Create time features (Year, Month) for time series aggregations.
Analysis:
Product-level: Rank products by total Sales.
Time series: Aggregate monthly and yearly Sales and visualize trends.
Region-level: Aggregate and rank regions by total Sales.
Outputs:
CSV exports for top products, monthly sales, yearly sales, and region sales.
Visuals for monthly trend and yearly totals.


**Conclusions**

Sales grow notably into 2016–2017 with volatility at the monthly level, indicating periodic spikes that may align with promotions or seasonality.
Top-selling products are concentrated in a mix of technology and office equipment SKUs.
The West region leads overall sales, followed by the East, suggesting resource allocation and inventory planning should prioritize these regions while exploring uplift strategies for Central and South.
Further work: Layer profit margins, discount elasticity, and category mix to refine pricing and assortment decisions.
Additional Sections (Optional)


**Project Structure**

notebooks/: analysis notebooks
data/: raw and interim data (not committed if large)
outputs/: exported CSVs and figures
Reproducibility

Clone repo and open notebooks in Jupyter.
Ensure Python 3.x with pandas, matplotlib, seaborn installed.
Place the Superstore CSV in data/ or update the notebook path accordingly.
Key Generated Files (exports)

top_selling_products.csv
monthly_sales.csv
yearly_sales.csv
region_sales.csv
