# Retail Sales Analysis — Excel

## Overview

This project presents an end-to-end retail sales analysis developed entirely in Microsoft Excel.

The objective was to transform a raw sales dataset into a structured analysis that answers common business questions and presents the results through tables, visualizations, and an interactive-style dashboard.

The project covers data cleaning, data transformation, lookup functions, pivot tables, business analysis, data visualization, and dashboard development.

---

## Business Questions

The analysis was designed to answer the following questions:

* What is the total revenue generated during the period?
* What is the average value of an order?
* How many orders were placed?
* How does revenue compare across branches?
* How does revenue change over time?
* Which product categories generate the most revenue?
* Which payment method is used most frequently?
* Which salesperson generated the highest revenue?
* How does salesperson performance compare in terms of revenue, order count, and average revenue?

---

## Dataset

The dataset represents a retail sales operation with information about:

* Order ID
* Order date
* Customer ID
* Customer name
* Product
* Category
* Quantity
* Unit price
* Salesperson
* Branch
* Payment method

The project contains **100 sales records** covering the period from **January to March 2026**.

A product catalog was also used as a reference table to support product information and lookup operations.

---

## Data Preparation

The original data was reviewed and prepared before performing the analysis.

The cleaning process included:

* Removing duplicate records
* Standardizing customer names and text values
* Checking and standardizing data types
* Reviewing dates
* Validating numerical fields
* Organizing reference tables
* Preparing the cleaned dataset for analysis

The cleaned data was consolidated into a structured analysis table used by the pivot tables and dashboard.

---

## Excel Tools & Techniques

The project was developed using Microsoft Excel and includes the following techniques:

### Data Cleaning

* Duplicate removal
* Text standardization
* Data type validation
* Data organization

### Excel Functions

* `SUM`
* `AVERAGE`
* `COUNTA`
* `XLOOKUP` / `BUSCARX`
* `GETPIVOTDATA`

### Data Analysis

* Pivot Tables
* Aggregations
* Grouping by category
* Grouping by branch
* Grouping by month
* Salesperson performance analysis
* Payment method frequency analysis

### Data Visualization

* Column/bar charts
* Category revenue visualization
* Salesperson revenue comparison
* Monthly revenue visualization

### Dashboard

A dedicated dashboard was created to present the main business metrics in a concise format.

---

## Workbook Structure

The Excel workbook is organized into several sheets, each with a specific purpose.

| Sheet             | Purpose                                                             |
| ----------------- | ------------------------------------------------------------------- |
| `Raw`             | Original sales dataset                                              |
| `Raw_catalog`     | Original product catalog/reference data                             |
| `Ref_Tables`      | Structured reference and calculation tables                         |
| `Product_Catalog` | Clean product catalog used for lookup operations                    |
| `Analysis`        | Business questions, calculations, and pivot-table analysis          |
| `Visualization`   | Charts based on the analysis                                        |
| `Dashboard`       | Final presentation of key performance indicators and visualizations |

This structure separates the raw data from the analysis and presentation layers.

---

## Key Results

The analysis produced the following results:

| Metric                              |          Result |
| ----------------------------------- | --------------: |
| Total Revenue                       |   **$3,074.50** |
| Total Orders                        |         **100** |
| Average Order Value                 |     **$30.745** |
| Highest Revenue Category            | **Electronics** |
| Most Frequently Used Payment Method |        **Card** |
| Highest Revenue Salesperson         |      **Daniel** |

### Revenue by Category

| Category    |   Revenue |
| ----------- | --------: |
| Electronics | $1,337.00 |
| Accessories |   $810.00 |
| Home        |   $684.00 |
| Office      |   $243.50 |

Electronics generated the largest share of total revenue, with **$1,337.00**.

### Revenue by Branch

| Branch   | Revenue |
| -------- | ------: |
| San José | $877.50 |
| Alajuela | $810.50 |
| Cartago  | $766.00 |
| Heredia  | $620.50 |

### Monthly Revenue

| Month    |   Revenue | Orders |
| -------- | --------: | -----: |
| January  | $1,279.00 |     35 |
| February | $1,012.00 |     35 |
| March    |   $783.50 |     30 |

### Payment Methods

| Payment Method | Orders |
| -------------- | -----: |
| Card           |     38 |
| Cash           |     28 |
| Mobile Payment |     26 |
| Transfer       |      8 |

### Salesperson Performance

| Salesperson | Revenue | Orders | Average Revenue |
| ----------- | ------: | -----: | --------------: |
| Daniel      | $932.00 |     32 |          $29.13 |
| Sofia       | $881.50 |     23 |          $38.33 |
| Valeria     | $711.50 |     26 |          $27.37 |
| Marco       | $549.50 |     19 |          $28.92 |

The salesperson analysis includes not only total revenue, but also order count and average revenue per order.

---

## Dashboard

The final dashboard consolidates the main performance indicators and visualizations from the analysis.

The dashboard was designed to provide a quick overview of:

* Total Revenue
* Total Orders
* Average Order Value
* Revenue by category
* Revenue by salesperson
* Revenue trends over time

The dashboard serves as the final presentation layer of the project.

---

## Project Workflow

The project follows a simple data-analysis workflow:

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Standardization
   ↓
Reference Tables
   ↓
Pivot Tables & Calculations
   ↓
Business Analysis
   ↓
Visualizations
   ↓
Dashboard
```

This structure demonstrates how raw business data can be transformed into information that supports analysis and decision-making.

---

## Skills Demonstrated

This project demonstrates practical experience with:

* Microsoft Excel
* Data Cleaning
* Data Transformation
* Data Validation
* XLOOKUP / BUSCARX
* Excel formulas
* Pivot Tables
* Data Aggregation
* Business Questions
* KPI Analysis
* Data Visualization
* Dashboard Design
* Basic Business Analysis

---

## Project Files

```text
retail-sales-excel-analysis/
│
├── README.md
│
├── retail_sales_excel_project_completed.xlsx
│
└── screenshots/
    ├── dashboard.png
    ├── analysis.png
    └── visualization.png
```

---

## Conclusion

This project demonstrates an end-to-end Excel workflow, starting with raw retail sales data and ending with a structured business analysis and dashboard.

The main focus was not only on creating spreadsheets, but on using Excel to clean data, answer business questions, identify patterns, calculate relevant metrics, and communicate results visually.

---
