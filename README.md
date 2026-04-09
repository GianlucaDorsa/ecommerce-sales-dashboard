# E-commerce Sales Dashboard

## Overview
This project presents a Power BI dashboard that analyzes e-commerce sales performance.

The goal is to transform raw transactional data into clear business insights about revenue, products, and customer activity.

---

## Business Problem
The dashboard was built to answer:

- How is revenue evolving over time?
- Which products drive the most sales?
- Are there signs of seasonality or fluctuations in demand?
- How does transaction volume vary monthly?

These insights support better decisions in sales strategy and inventory planning.

---

## Tools
- Power BI  
- Python (data cleaning)  
- Pandas  
- Excel / CSV  

---

## Dataset
Transactional e-commerce data including:

- Invoice number and date  
- Product details  
- Quantity and unit price  
- Country  

Key metrics were derived:

- Revenue  
- Monthly aggregation (MonthYear)  
- Unique products  
- Total transactions  

---

## Key Metrics
The dashboard focuses on four KPIs:

- Total Revenue  
- Units Sold  
- Unique Products  
- Total Transactions  

A monthly trend visual shows performance evolution over time.

---

## Key Insights
- Revenue and sales volume fluctuate monthly, showing demand variability.  
- A small number of products generate most of the revenue.  
- Peaks in transactions indicate periods of higher customer activity.  
- Product performance is uneven, highlighting optimization opportunities.

---

## Dashboard Preview
![Dashboard Preview](images/dashboard_screenshot.png)

---

## How to Use
1. Open `Sales_Dashboard.pbix` in Power BI Desktop  
2. Load data from `data/processed/`  
3. Explore filters and visuals interactively  

---

## Additional Notes
See analytical decisions and reasoning here:

- [Analysis Decisions](analysis_decisions.md)

---

## Next Steps
- Add profit analysis  
- Include product category breakdown  
- Build drill-down views  
- Automate data refresh  