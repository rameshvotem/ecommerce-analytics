This project focuses on E-commerce Sales & Customer Analytics, using the Olist Brazilian E-commerce dataset from Kaggle.
The goal is to build a complete analytics pipeline — from raw data to business insights — over 30 days.

🎯 Objectives

Analyze customer behavior and order patterns.

Identify top-performing products, categories, and regions.

Build Power BI dashboards for real-time insights.

Apply RFM analysis, cohort retention, and forecasting.

### Step 2 — Initial Data Exploration
- Loaded and reviewed all Olist tables.
- Checked missing values and datatypes.
- Identified key relationships and data quality issues.
- Ready for Day 3 (Data Cleaning & Standardization).
### Step 3 Data Cleaning
- Cleaned column names (lowercase, underscores).
- Converted date columns to datetime.
- Filled or tagged missing delivery dates.
- Verified unique IDs and row counts.
- Exported cleaned data to `/data/staging/`.
- ### Step 4 — SQL Integration & Relational Model Setup
- Created SQLite database and loaded cleaned CSV tables.
- Verified table relationships and row counts.
- Database ready for analytical SQL queries.
### Step 5 — Exploratory SQL Analysis
- Ran SQL queries to analyze order patterns and data quality.
- Calculated total orders, monthly trends, and average delivery time.
- Exported summarized data for Power BI visualizations.
- Verified successful data pipeline from raw → clean → database → query stage.
