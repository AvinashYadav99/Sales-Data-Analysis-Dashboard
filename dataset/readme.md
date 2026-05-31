# Dataset Information

## Data Modeling Approach

This Power BI project follows a Star Schema data modeling approach for optimized reporting and analytics performance.

---

# Fact Table

## Fact_Sales

Contains transactional business data used for reporting and KPI calculations.

### Columns

* CustomerID
* Date
* Net Sales
* Discount Percentage
* Discount Value
* Profit
* Quantity Sold

---

# Dimension Tables

## Dim_Customers

Contains customer-related information.

### Columns

* Customer Name
* City
* State
* EmailID
* Phone Number

---

## Dim_Product

Contains product-related details.

### Columns

* Product Name
* Product Line
* Price Per Unit

---

## Dim_Promotion

Contains promotion and campaign information.

### Columns

* Promotion Name
* Coupon Code
* Ad Type
* Percentage

---

# Date Table

A dedicated Date Table was created to support:

* Time Intelligence Functions
* Monthly Trend Analysis
* Year-over-Year Comparisons
* Quarterly Reporting

---

# Measures Table

Created DAX measures for KPI calculations and business analysis.

## DAX Measures

* Total Profit
* Sum of Net Sales
* Quantity Sold

---

# Data Modeling Concepts Used

* Star Schema
* One-to-Many Relationships
* Time Intelligence
* DAX Measures
* KPI Calculations
* Optimized Data Model Design

