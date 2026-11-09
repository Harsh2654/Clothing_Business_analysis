# Clothing_Business_analysis
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.
An analysis of the repository reveals a complete four-stage data analytics lifecycle: Python (EDA & ETL), Relational Database (SQL query logic), Business Intelligence (Power BI modeling & DAX), and Executive Reporting (PDF/PPTX presentation).
## 📌 Executive Summary
Understanding customer retention drivers, spending patterns, and product category profitability is critical in retail and apparel. This project delivers an industry-standard, end-to-end analytics pipeline on retail customer shopping behavior (3,900+ customer records). 
The analysis bridges raw transactional data with actionable commercial strategies—identifying high-value customer cohorts, subscription discount leakage, and category-level cross-sell opportunities.

🔍 Key Analytical Workflows
1. Python Data Engineering & EDA
Data Audit: Evaluated 3,900 customer records across 19 features with zero unhandled nulls post-processing.
Transformations: Standardized age bins, purchase frequencies, and price brackets.
Automated Pipeline: Connected directly to the SQL database using SQLAlchemy and pyodbc to load cleaned staging tables.

2. SQL Business Analysis
The customer_behavior_sql_queries.sql script answers key business questions:
Customer Segmentation: Ranked top customer cohorts by Lifetime Purchase Amount (SUM(Purchase_Amount_USD)).
Subscription Economics: Analyzed whether subscription status directly correlates with higher average order value (AOV) and purchase frequency.
Product & Category Performance: Identified top-selling apparel items by season, shipping preference, and review rating.
Discount Sensitivity: Evaluated discount usage rates across demographic bands to isolate margin leakage.

3. Power BI Executive Dashboard
Data Modeling: Constructed optimized star/snowflake relationships with clear dimensional boundaries.
Key DAX Measures: Dynamic KPIs for Total Revenue, Average Order Value (AOV), Repeat Customer Rate, and Customer Lifetime Value (CLV).
Interactive Slicers: Dynamic filtering by Demographic Age Cohort, Product Category, Subscription Status, and Payment Method.
