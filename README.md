# Telco Customer Churn Analysis Dashboard (Excel)

## Overview

Customer churn is a major challenge for telecom companies because losing existing customers directly affects revenue and growth.
In this project, I analyzed a telecom customer dataset to understand **why customers leave, which segments are at higher risk, and what the potential business impact of churn is**.

The analysis was done entirely in **Microsoft Excel** using tools such as **Power Query, Power Pivot, DAX measures, Pivot Tables, and interactive dashboards**.
The final output is an **executive-level dashboard** that allows users to explore churn patterns and key business insights interactively.

---

## Dataset

The dataset contains information about telecom customers, including:

* Customer demographics
* Contract type
* Internet service
* Payment method
* Monthly charges
* Tenure
* Churn status

It includes data for **7,000+ customers**, which makes it suitable for performing meaningful churn analysis.

---

## Project Workflow

The project follows a structured analytics workflow:

### 1. Data Preparation

* Loaded raw telecom dataset
* Cleaned missing and inconsistent values
* Created structured tables for analysis
* Performed transformations using **Power Query**

### 2. Feature Engineering

Additional columns were created to support analysis:

* Customer Lifetime Value (CLTV)
* CLTV Category
* Churn Score
* Churn Value (binary indicator)
* Tenure Groups for lifecycle analysis

### 3. Exploratory Data Analysis

Several statistical and distribution analyses were performed:

* Descriptive statistics
* Tenure distribution
* Monthly charges distribution
* Outlier detection using IQR
* Correlation analysis between key variables

### 4. Customer Churn Analysis

Multiple segmentation analyses were used to understand churn drivers:

* Churn by **contract type**
* Churn by **tenure group**
* Churn by **internet service**
* Churn by **payment method**
* Churn across **customer value segments**

### 5. KPI Development

Using **Power Pivot and DAX**, key business metrics were created:

* Total Customers
* Churn Rate
* Revenue at Risk
* Average Tenure
* Average Customer Lifetime Value

### 6. Dashboard Development

All insights were combined into an **interactive Excel dashboard** with:

* KPI cards
* Pivot-based visualizations
* Interactive slicers
* Customer segmentation views
* Revenue impact analysis

---

## Key Insights

Some important findings from the analysis:

* Customers with **month-to-month contracts show the highest churn rate**.
* **New customers (0–6 months tenure)** are significantly more likely to churn.
* Customers using **fiber optic internet services churn more frequently** than DSL users.
* Customer churn represents approximately **$2.9M in potential revenue at risk**.

These insights can help telecom companies design better **retention strategies and customer engagement programs**.

---

## Dashboard Features

The Excel dashboard includes:

* Executive KPI summary
* Customer churn drivers
* Customer lifecycle churn analysis
* Customer value segmentation
* Revenue-at-risk visualization
* Interactive filters using slicers

Users can filter the dashboard by attributes such as **contract type, internet service, payment method, gender, senior citizen status, and city**.

---

## Tools & Techniques Used

* Microsoft Excel
* Power Query
* Power Pivot
* DAX Measures
* Pivot Tables
* Data Visualization
* Descriptive Statistics
* Correlation Analysis

---

## Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

---

## Author

**Ashutosh Jamnal**

This project was created as part of my data analytics portfolio to demonstrate my ability to perform **end-to-end analysis and build business-focused dashboards using Excel.**

