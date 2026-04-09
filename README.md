# Sales Overview Dashboard

## Overview
This project presents a Power BI dashboard for e-commerce sales analysis to evaluate monthly performance, track key business metrics, and identify sales trends over time.

The main goal was to practice data analysis and business intelligence by transforming raw transactional data into an interactive dashboard that supports data-driven decision-making.

## Business Problem
Which factors are driving sales performance over time, and how effectively is the business meeting its monthly sales targets?

The dashboard answers the following questions:

- How have total sales evolved month-over-month?
- Are sales meeting monthly targets?
- Which products are top performers or underperforming?
- How many unique transactions occur each month?

Insights from this analysis support decisions related to sales strategy, inventory management, and performance tracking.

## Tools
- Microsoft Power BI
- Python
- Pandas
- Jupyter Notebook
- CSV files

## Dataset
The dataset contains e-commerce transactional data with the following fields:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- Country

Derived fields used in the analysis:

- MonthYear
- Total Revenue
- Total Units Sold
- Unique Products Sold
- Total Transactions

## Key Metrics
The dashboard includes four main KPIs:

1. Total Revenue – total sales value  
2. Total Units Sold – total quantity of products sold  
3. Unique Products Sold – number of distinct products sold  
4. Total Transactions – number of unique invoices  

Additionally, a monthly trend analysis visual shows revenue and units evolution over time, with optional target comparison.

## Key Insights
- Sales performance fluctuates across months, showing clear seasonal patterns.
- Revenue is concentrated in a limited number of products.
- Units sold and revenue do not always follow the same trend.
- Transaction volume varies significantly across time periods.
- Combining multiple KPIs provides a more complete view of business performance.


## Visualization

![Dashboard Preview](images/dashboard_screenshot.png)

## How to Use
1. Open `powerbi/Sales_Dashboard.pbix` in Power BI Desktop.  
2. Load the dataset from `data/processed/online_retail_cleaned.csv`.  
3. Explore the dashboard using filters and interactive visuals.

## Additional Notes
For a more detailed explanation of the analytical decisions, design choices, and reasoning behind this project, see:

- [Analysis Decisions and Reasoning](analysis_decisions.md)

## Next Steps
- Add profit margin and cost analysis  
- Include deeper segmentation by country or product category  
- Implement drill-down capabilities in Power BI  
- Automate data refresh pipeline  
- Extend analysis with forecasting models