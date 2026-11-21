# retail-sales-performance-customer-insights
End-to-end retail analytics capstone using Excel, SQL, Python and Power BI.
# Retail Sales Performance & Customer Insights
### End-to-End Data Analytics Capstone Project

## Project Overview

This project is an end-to-end retail analytics capstone designed to transform raw retail sales data into meaningful business insights.

The project follows a complete analytics workflow using **Excel, SQL, Python, and Power BI**, covering data cleaning, exploratory data analysis, database querying, customer segmentation, and interactive dashboard development.

**Domain:** Retail / E-Commerce Analytics

## Business Problem

A retail business wants to understand its sales performance, customer purchasing behaviour, product performance, store performance, and campaign effectiveness.

The objective is to use data-driven analysis to help business stakeholders make better decisions about sales, customer retention, inventory, and marketing strategies.

## Project Objectives

- Analyze overall retail sales and revenue performance.
- Identify high-performing and underperforming stores and products.
- Understand customer purchasing behaviour and segmentation.
- Analyze sales trends over time.
- Evaluate campaign performance.
- Identify customers with potential churn risk.
- Present actionable business insights through an interactive dashboard.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, profiling, lookup functions, PivotTables and PivotCharts |
| SQL – TiDB Cloud | Relational data analysis, joins, aggregations, CTEs and window functions |
| Python – Google Colab | Data cleaning, EDA, feature engineering, statistical analysis and customer segmentation |
| Power BI | Data visualization, DAX, interactive dashboards and business storytelling |

## Dataset Structure

The project uses a retail star-schema dataset containing seven tables:

- Fact_Sales
- Dim_Customers
- Dim_Products
- Dim_Stores
- Dim_Salesperson
- Dim_Campaign
- Dim_Dates

The sales dataset contains approximately 1,000,000 transactions.

## Project Workflow

### Stage 1 – Excel: Data Cleaning & Analysis

- Imported and organized seven datasets.
- Performed data profiling and quality checks.
- Checked duplicate keys, missing values and orphan foreign keys.
- Identified and handled text-formatting inconsistencies.
- Performed outlier analysis using the IQR method.
- Applied XLOOKUP to enrich the sales dataset.
- Created PivotTables and PivotCharts.
- Applied conditional formatting.
- Prepared a Data Quality Report.

### Stage 2 – SQL: Relational Data Analysis

- Loaded datasets into TiDB Cloud.
- Worked with relational tables and key relationships.
- Practiced joins, subqueries, CTEs and window functions.
- Answered business questions using SQL.
- Analyzed sales, products, stores and customer performance.

### Stage 3 – Python: EDA & Customer Analytics

Using Google Colab:

- Performed data exploration and validation.
- Used Pandas and NumPy for data manipulation.
- Analyzed distributions and outliers.
- Performed feature engineering.
- Conducted customer segmentation using clustering.
- Analyzed customer purchasing behaviour and churn risk.

### Stage 4 – Power BI: Dashboard & Business Insights

- Built an interactive retail sales dashboard.
- Created KPI cards and business performance visuals.
- Analyzed revenue by product, store, customer segment and campaign.
- Used slicers and interactive report features.
- Presented findings to support business decision-making.

## Key Data Quality Findings

- No duplicate business keys were identified.
- No blank values were identified in the documented checks.
- No orphan foreign keys were identified across 1,000,000 sales records.
- No missing campaign keys were identified.
- No outliers were identified using the selected IQR rule.
- Trailing spaces were identified in `store_type` for 173 of 500 stores and corrected using Trim in Power Query.

## Repository Structure

- `01_Excel/` – Excel analysis and data quality documentation.
- `02_SQL/` – SQL queries and query catalog.
- `03_Python/` – Google Colab notebooks.
- `04_PowerBI/` – Power BI dashboard and screenshots.
- `05_Documentation/` – Project methodology and business insights.

## Business Value

This project demonstrates how raw retail data can be transformed into structured information and actionable insights.

It brings together data preparation, analytical querying, statistical exploration, customer segmentation and business intelligence reporting.

## Skills Demonstrated

Excel | SQL | Python | Pandas | NumPy | EDA | Statistics | Clustering | Customer Segmentation | Power BI | DAX | Data Cleaning | Data Visualization | Business Analysis

## Project Deliverables

- Excel data preparation and quality report.
- SQL business analysis query collection.
- Python EDA and customer analytics notebooks.
- Interactive Power BI dashboard.
- Project documentation and business findings.
## Author

**Pooja Ammasi**  
Aspiring Data Analyst | Business Analyst
