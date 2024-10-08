# AdventureWorks Power BI Report

A comprehensive business intelligence solution built in **Microsoft Power BI** for AdventureWorks, a global manufacturer specializing in cycling equipment and accessories.

## Data Source  
The dataset used for this project is derived from Microsoft's [AdventureWorks sample databases](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms), provided as part of the [Maven Analytics Power BI Desktop course](https://mavenanalytics.io/course/microsoft-power-bi-desktop).

---

## Overview of the Dataset
- **Coverage Period:** Sales and return data from `01/01/2020` to `30/06/2022`.
- **Geographical Scope:** AdventureWorks operates in six countries across three continents:

  - Australia
  - Canada
  - France
  - Germany
  - United Kingdom
  - United States

- **Customer Profiles Include:**

  - Date of birth
  - Annual income
  - Education level
  - Number of children
  - Occupation
  - Homeownership status

---

## Project Scope & Key Tasks
This dashboard development involved several key tasks:

1. **Data Preparation & Transformation**
   - Connected raw data to Power BI.
   - Built a relational data model.
   - Created calculated columns and measures using DAX.
   - Generated a rolling calendar using PowerQuery M code.

2. **Interactive Dashboard Construction**
   - Designed multiple views to track key metrics and provide deep-dive analysis for stakeholders.

---

## Dashboard Components & Features

### Executive Summary
- Displays high-level KPIs such as revenue, profit, order volume, and return rates.
- Includes page-level filters by product and category.
- Offers drill-through functionality to view detailed product insights.

### Map View
- Visualizes total order volume by country, enabling performance comparison across regions.

### Product Detail View
- Provides per-product analysis of orders, revenue, and profit.
- Includes a "what if" analysis to project profit changes through price adjustments.

### Customer Analysis
- Displays customer-level data, offering insights on total revenue and revenue per customer.

---

## Custom User Interface Elements
- **Filter Pane:** Allows dynamic filtering by year and region.
- **Custom Tooltips:** Enhances product category analysis with additional order metrics.

---

## Key Insights from the Analysis

### Revenue & Profit Trends
- Total revenue for the period was **$24.9 million**, with a profit of **$10.5 million**.
- A significant revenue drop occurred between `01/06/2020` and `01/11/2020`, likely due to the COVID-19 pandemic.
- Revenue growth resumed after November 2020, peaking in December 2021 at **$1.64 million**, potentially due to a seasonal campaign like Black Friday.

### Product Performance
- **Tires and tubes** are the most ordered products, while **cycling shorts** lead in returns.
- **Mountain bike fenders** and **sports helmets** top revenue generation despite high return rates.
- **Clothing and accessories** are the most profitable product categories overall.

### Customer Behavior
- Starting from `02/08/2021`, there was a notable increase in weekly customers, with about **200 new customers per week**.
- Despite the customer growth, revenue per customer has been declining year-on-year.
- The U.S. market is the largest with **8,700 orders** and **$7.94 million** in total revenue, but **Australia** leads in revenue per customer at **$2,131**.

---

### License
This project is based on publicly available datasets provided by [Microsoft](https://docs.microsoft.com/en-us/sql/samples/adventureworks?view=sql-server-ver15).
