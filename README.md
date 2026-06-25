# Capstone 3 – Northeast Regional Sales Analysis with Power BI

Video Presentation Link https://yearuptemp-my.sharepoint.com/:v:/g/personal/dnji_my_yearupunited_org/IQARQXuwRxNbRoaBs8t3A8NAAa9RPGHp7HxNaceTnRMc0N8?e=GGGjox
## Project Overview

This project was completed as part of the Year Up United Data Analytics Training Academy Week 12 Capstone. The purpose of this project was to analyze EmporiUm sales data using Power BI and develop a business intelligence report that provides meaningful insights into sales performance within the Northeast Region.

EmporiUm is a virtual student bookstore that operates through both physical retail stores and online sales channels. The company requested an analysis of sales activity over a four-year period to identify trends, evaluate performance across states and product categories, and determine the top-selling books within the assigned region.

For this capstone, the Northeast Region included the following states:

* Maryland
* Massachusetts
* Maine
* New Jersey

Both Store Sales and Online Sales data were included in the analysis to provide a complete picture of regional performance.

---

## Project Objectives

The primary objectives of this project were to:

* Analyze sales trends across the Northeast Region over time.
* Compare sales performance across product categories.
* Evaluate sales distribution among Northeast states.
* Identify the top-selling books and authors in the region.
* Compare Store Sales and Online Sales performance.
* Provide actionable business recommendations based on the findings.

---

## Tools and Technologies Used

### Power BI Desktop

Used for data modeling, visualization creation, report design, and dashboard development.

### Power Query

Used to clean, transform, and prepare data before analysis.

### DAX (Data Analysis Expressions)

Used to create measures and perform calculations such as:

* Total Sales
* Total Transactions
* Average Sale Amount
* Sales by Category
* Sales by State

### GitHub

Used for version control, project organization, and repository management.

---

## Data Sources

The project utilized data provided in the Capstone 3 dataset, including:

### Store Sales

Contains in-store transaction data including:

* Transaction Date
* Store ID
* Product Number
* Sales Amount

### Online Sales

Contains online transaction data including:

* Order Date Information
* Product Number
* Shipping State
* Sales Amount

### Products

Contains product information including:

* Product Number
* Product Name
* Category
* Subcategory

### Store Locations

Contains store information including:

* Store ID
* Store Name
* State

### Management Team

Contains regional and territory management assignments.

### Book List

Contains general audience book titles and author names used to identify top-selling books.

---

## Data Preparation and Cleaning

Several data preparation steps were required before analysis could begin.

### Store Sales Cleaning

The Store Sales table was reviewed and cleaned by:

* Verifying data types.
* Removing unnecessary spaces and formatting issues.
* Merging Store Sales with Store Locations to obtain state information.
* Filtering records to include only Northeast states.

### Online Sales Cleaning

The Online Sales table was cleaned by:

* Creating a Transaction Date field from separate Year, Month, and Day columns.
* Standardizing field names.
* Filtering records to include only Northeast states.

### Products Table

The Products table was cleaned by:

* Verifying product identifiers.
* Standardizing category names.
* Removing formatting inconsistencies.

### Data Consolidation

Store Sales and Online Sales data were combined into a unified sales table to support regional analysis across both sales channels.

A Sales Type field was added to distinguish between:

* Store Sales
* Online Sales

---

## Data Model

Relationships were created to connect fact and dimension tables.

### Relationships

All Northeast Sales - Products

* Product Number

All Northeast Sales - Store Locations

* Store ID

These relationships enabled category-level, state-level, and product-level analysis throughout the report.

---

## Key Measures Created

### Total Sales

Calculates total revenue generated within the Northeast Region.

### Total Transactions

Calculates the total number of transactions.

### Average Sale

Calculates average revenue generated per transaction.

### Sales by Category

Measures category performance across all sales channels.

### Sales by State

Measures revenue contribution from each Northeast state.

---

## Report Pages

### Page 1: Northeast Regional Sales Overview

Purpose:
Provide a high-level summary of regional sales performance.

Visuals Included:

* Sales Trend Line Chart
* Revenue by State Donut Chart
* Total Sales KPI
* Total Transactions KPI
* Average Sale KPI

Business Value:

This page allows management to quickly understand overall performance, identify sales trends, and compare state contributions to regional revenue.

---

### Page 2: Product and Book Analysis

Purpose:
Analyze product category performance and identify top-selling books.

Visuals Included:

* Sales by Category Bar Chart
* Top-Selling Books Table
* Store Sales vs Online Sales Comparison

Business Value:

This page helps management identify high-performing categories, understand customer purchasing behavior, and prioritize inventory and marketing efforts.

---

## Key Business Questions Answered

This project was designed to answer the following questions:

1. How have sales performed over time in the Northeast Region?

2. Which Northeast states generate the highest sales revenue?

3. Which product categories perform best?

4. Which books are the top-selling titles within the region?

5. How do Store Sales compare to Online Sales?

6. What opportunities exist to improve future sales performance?

---

## Insights and Findings

The report provides insights into:

* Regional sales growth trends.
* State-level revenue distribution.
* High-performing product categories.
* Best-selling books and authors.
* Customer purchasing behavior across sales channels.

These insights help management make more informed decisions regarding inventory planning, marketing strategies, and resource allocation.

---

## Recommendations

Based on the analysis, the following recommendations were developed:

### Inventory Planning

Increase inventory levels for top-performing categories and best-selling books before peak sales periods.

### Marketing Strategy

Focus promotional efforts on products and categories that consistently generate strong sales.

### State-Level Opportunities

Evaluate lower-performing states to identify opportunities for targeted growth initiatives.

### Channel Optimization

Continue monitoring Store Sales and Online Sales performance to ensure resources are allocated effectively.

### Forecasting

Use historical sales trends to improve future demand forecasting and operational planning.

---

## Project Deliverables

This repository contains:

* Power BI Report (.pbix)
* README Documentation
* Project Screenshots
* Presentation Materials
* Video Demonstration Link
* Supporting Files

---

## Conclusion

This project demonstrates the use of Power BI, Power Query, data modeling, and business intelligence techniques to transform raw sales data into actionable insights.

By combining Store Sales and Online Sales across the Northeast Region, the report provides management with a comprehensive view of performance, customer behavior, and sales opportunities. The resulting dashboard supports data-driven decision-making and helps EmporiUm continue improving operational and sales performance.

