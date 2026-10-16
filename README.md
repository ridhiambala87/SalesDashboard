# AdventureWorks Sales Performance & Revenue Analytics

## Project Overview

This project analyzes AdventureWorks sales data using **Microsoft Power BI** to identify revenue trends, top-selling products, and regional sales performance. The goal is to transform raw sales data into meaningful business insights through data cleaning, data modeling, KPI development, and interactive visualizations.

The project demonstrates an end-to-end data analytics workflow, from preparing datasets to building an interactive dashboard that supports data-driven decision-making.

## Objectives

- Analyze revenue trends across different years and months.
- Identify top-selling products and high-performing product categories.
- Evaluate regional and country-wise sales performance.
- Calculate key performance indicators (KPIs).
- Clean and transform raw datasets for reliable analysis.
- Build an interactive Power BI dashboard with slicers and visualizations.

## Tools & Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — KPI calculations and analytical measures
- **Microsoft Excel / CSV** — Data inspection and preparation

## Dataset

The project uses the AdventureWorks sample dataset, including:

- AdventureWorks Sales Data 2020
- AdventureWorks Sales Data 2021
- AdventureWorks Sales Data 2022
- Customer Lookup
- Product Lookup
- Product Subcategories Lookup
- Product Categories Lookup
- Territory Lookup
- Calendar Lookup
- Returns Data

These datasets provide sales records and supporting information about products, customers, territories, dates, and returns.

## Data Cleaning & Preparation

The following steps were performed to prepare the data for analysis:

1. Combined sales records from 2020, 2021, and 2022.
2. Removed duplicate records.
3. Handled missing values in essential fields.
4. Standardized date and numeric data types.
5. Merged sales data with product, category, and territory lookup tables.
6. Created calculated columns for revenue, cost, profit, and profit margin.
7. Prepared separate dimension tables to support data modeling.

**Metric note:** Revenue is estimated as order quantity multiplied by product list price because actual transaction-level revenue and discounts are not available in the supplied sales files. Profit is calculated using the estimated revenue and product cost.

## Key Performance Indicators (KPIs)

The dashboard focuses on the following metrics:

- **Total Revenue:** Estimated sales value.
- **Total Profit:** Estimated profit after product cost.
- **Profit Margin:** Estimated profit as a percentage of revenue.
- **Total Orders:** Number of distinct orders.
- **Units Sold:** Total quantity of products sold.
- **Average Order Value (AOV):** Estimated revenue divided by distinct orders.

## Dashboard Features

The Power BI dashboard provides interactive analysis through:

- Monthly revenue trend analysis
- Top 10 products by revenue
- Regional and country-wise performance comparison
- Revenue by product category
- Profitability analysis
- KPI cards for quick performance monitoring
- Interactive slicers for year, region, category, and continent

## Business Value

This dashboard helps users:

- Identify revenue patterns and high-performing periods.
- Recognize products that contribute significantly to sales.
- Compare regional performance and identify potential growth opportunities.
- Evaluate profitability alongside revenue.
- Explore sales data interactively to support business decisions.

## How to Run the Project

1. Clone or download this repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. If prompted, update the data source paths to match your local files.
4. Refresh the dataset if necessary.
5. Use the available slicers and visualizations to explore sales performance.

## Key Learnings

- Data cleaning and transformation using Power Query
- Data modeling and relationships
- DAX measures and KPI creation
- Interactive dashboard development
- Business analysis and insight communication
- Translating raw datasets into actionable visual insights

## Conclusion

The AdventureWorks Sales Performance & Revenue Analytics project demonstrates how Power BI can be used to transform sales data into an interactive business intelligence solution. By combining data preparation, KPI analysis, and visual storytelling, the dashboard makes it easier to understand product performance, revenue trends, and regional sales patterns.

**Project Type:** Data Analytics | Business Intelligence | Internship Project

**Developed using:** Microsoft Power BI, Power Query, DAX, Excel, and CSV datasets
