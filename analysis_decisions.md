# Analysis Decisions and Reasoning

## Purpose
This document explains the reasoning behind the analytical and design decisions made in this Power BI dashboard project.  
The goal is to ensure that the analysis is not only descriptive, but also intentional, focused, and aligned with the business objective.

---

## 1. Variable Selection
The analysis focused on variables that directly contribute to understanding e-commerce sales performance:

- Revenue (Total Sales Value)
- Quantity Sold
- Product Description / Stock Code
- Invoice / Transaction ID
- Time (Month-Year)
- Country (contextual segmentation)

These variables were selected because they allow the identification of:
- Sales trends over time
- Top-performing products
- Transaction volume behavior
- Revenue distribution patterns

Non-essential variables were excluded to maintain clarity and focus on business-relevant insights.

---

## 2. KPI Definition
The following KPIs were defined to summarize business performance:

- Total Revenue → overall business performance
- Total Units Sold → product demand and volume
- Unique Products Sold → product diversity and catalog performance
- Total Transactions → customer activity and engagement

These KPIs were chosen because they provide a balanced view of:
- Revenue generation
- Operational volume
- Customer behavior

---

## 3. Visualization Choices

### Line / Column Chart (Monthly Trend)
- Used to analyze performance over time
- Best suited to identify trends, seasonality, and fluctuations
- Enables comparison between actual performance and potential targets

### KPI Cards
- Used for high-level summary metrics
- Provide immediate snapshot of business performance
- Improve readability and executive-level interpretation

### Why not more complex visuals?
The goal was clarity over complexity.  
Since the dataset focuses on sales performance, simple and interpretable visuals were prioritized over overly complex representations.

---

## 4. Analytical Approach
The project follows a structured analytical workflow:

1. Data cleaning and preparation in Python
2. Aggregation of key business metrics
3. Transformation into time-based summaries (Month-Year)
4. Visualization in Power BI

Each step was designed to progressively transform raw transactional data into meaningful business insights.

The guiding principle throughout the project was:

> "Every metric and visualization must answer a business question."

---

## 5. Reflection
The decisions made in this project were driven by the goal of clarity, relevance, and business impact.

This includes:

- Focusing only on meaningful business variables
- Avoiding unnecessary complexity in visuals
- Prioritizing interpretability over technical depth
- Ensuring every chart supports decision-making

The result is a dashboard that is not only visually informative but also aligned with real business analysis thinking.