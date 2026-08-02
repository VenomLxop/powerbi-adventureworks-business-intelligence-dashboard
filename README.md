---------------------------------------------------
 AdventureWorks Business Intelligence Dashboard

      Power BI | DAX | Power Query
---------------------------------------------------
📊 AdventureWorks Business Intelligence Dashboard | Power BI



The **AdventureWorks Business Intelligence Dashboard** is an end-to-end Business Intelligence project developed using Microsoft Power BI. This project demonstrates the complete BI workflow—from data extraction and transformation to data modeling, DAX calculations, and interactive dashboard development.

The dashboard enables users to monitor key business KPIs, analyze sales and profitability, evaluate customer behavior, and identify product performance trends through interactive visualizations.

---

# Table of Contents

1. Project Overview
2. Dashboard Preview
3. Features
4. Project Workflow
5. Data Model
6. Dashboard Pages
7. DAX Measures
8. Technologies Used
9. Data Set
10. Installation
11. Usage
12. Repository Structure
13. Future Improvements
14. License
15. Contact

---

# Project Overview

AdventureWorks Cycles is a fictional bicycle manufacturing company used for Business Intelligence and Analytics projects.

The objective of this project is to transform raw business data into an interactive decision-support dashboard capable of tracking company performance across sales, customers, products, and returns.

The project follows the complete Business Intelligence workflow:

- Data Extraction
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Dashboard Development
- Business Insights

---

# Dashboard Preview

### Executive Dashboard

<img src="Images/Executive Dashboard.png" width="900"/>

---

### Product Analytics

<img src="Images/Product Detail Dashboard.png" width="900"/>

---

### Customer Analytics

<img src="Images/Customer Detail Dashboard.png" width="900"/>

---

### AI Key Influencers

<img src="Images/Key Influencers Dashboard.png" width="900"/>

---

# Features

✔ Executive KPI Dashboard

✔ Product Performance Analysis

✔ Customer Analytics Dashboard

✔ Dynamic Metric Selection

✔ Time Intelligence Analysis

✔ Price Adjustment What-if Analysis

✔ AI Key Influencers

✔ Decomposition Tree Analysis

✔ Custom Tooltips

✔ Drillthrough Navigation

✔ Interactive Filters & Slicers

✔ Bookmark Navigation

✔ Conditional Formatting

---

# Project Workflow

## Stage 1 – Data Preparation

- Imported multiple datasets
- Cleaned and transformed data using Power Query
- Created calculated columns
- Built a dynamic Calendar Table
- Merged and appended queries
- Validated data quality

---

## Stage 2 – Data Modeling

Developed a Star Schema consisting of:

### Fact Tables

- Sales Data
- Returns Data

### Dimension Tables

- Calendar Lookup
- Customer Lookup
- Product Lookup
- Territory Lookup
- Product Category Lookup
- Product Subcategory Lookup

Additional Tables

- Measure Table
- Price Adjustment Parameter
- Product Metric Selector
- Customer Metric Selector

---

## Stage 3 – DAX Development

Created 40+ DAX measures including:

- Revenue
- Profit
- Orders
- Return Rate
- Previous Month Revenue
- Previous Month Profit
- Rolling Revenue
- Rolling Profit
- Revenue Target
- Profit Target
- Order Target
- Running Totals
- Average Revenue per Customer

---

## Stage 4 – Dashboard Development

Designed interactive dashboards including:

- Executive Dashboard
- Product Detail Dashboard
- Customer Detail Dashboard
- AI Key Influencers
- Decomposition Tree
- Category Tooltips

---

# Data Model

<img src="Images/Polished Data set Image.png" width="900"/>

The project follows a Star Schema to improve performance, simplify relationships, and enable efficient filtering across fact and dimension tables.

---

# Dashboard Pages

## Executive Dashboard

Displays:

- Revenue
- Profit
- Orders
- Return Rate
- Revenue Trend
- Monthly KPIs
- Product Rankings

---

## Product Dashboard

Displays:

- Monthly Performance
- Product Targets
- Dynamic Metric Selection
- Price What-if Analysis
- Product Summary

---

## Customer Dashboard

Displays:

- Customer Segmentation
- Revenue per Customer
- Top Customers
- Occupation Analysis
- Income Analysis

---

## AI Insights

Power BI AI visuals were used to identify the factors influencing customer behavior and product pricing.

---

# Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Time Intelligence
- AI Visuals
- What-if Parameters

---
# Dataset

This project is built using the **AdventureWorks** sample dataset as part of a Microsoft Power BI training course.

To respect the course materials and associated licensing, the raw dataset is **not included** in this repository.

If you would like to explore or reproduce this project, please obtain the AdventureWorks dataset from one of the following sources:

- The original training course (if you are enrolled)
- The official Microsoft AdventureWorks sample data

Once the dataset is available, open the Power BI (.pbix) file and update the data source paths if required.

---
# Installation

Clone this repository

```bash
git clone https://github.com/VenomLxop/powerbi-adventureworks-business-intelligence-dashboard.git
```

Open

```
Dashboard/AdventureWorks.pbix
```

using Microsoft Power BI Desktop.

---

# Usage

1. Open the PBIX file.

2. Refresh the dataset.

3. Navigate through the dashboard pages.

4. Use slicers and filters to explore insights.

5. Experiment with the Price Adjustment parameter to analyze business scenarios.

---

# Repository Structure

```
AdventureWorks-Business-Intelligence-Dashboard
│
├── Dashboard
│   └── AdventureWorks.pbix
│
├── Images
│   ├── ExecutiveDashboard.png
│   ├── ProductDashboard.png
│   ├── CustomerDashboard.png
│   ├── KeyInfluencers.png
│   └── DataModel.png
│
├── README.md
│
└── LICENSE
```

---

# Future Improvements

- Power BI Service Deployment
- Row-Level Security (RLS)
- SQL Database Integration
- Forecasting Dashboard
- Python Integration
- Real-Time Data Refresh

---

# License

This project is intended for educational and portfolio purposes using the AdventureWorks sample dataset provided by Microsoft.

---

# Contact

**Lankeshwar M**

📧 Email: lankeshwar.mnitt2027@gmail.com

💼 LinkedIn: www.linkedin.com/in/lankeshwar-m-b40a67353

---

⭐ If you found this project useful, feel free to star the repository!
