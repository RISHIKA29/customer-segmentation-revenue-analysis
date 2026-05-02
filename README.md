# Customer Segmentation and Revenue Analysis

## Overview
This project focuses on analyzing customer behavior by segmenting customers based on their value and activity. The goal was to transform raw sales data into meaningful customer-level insights that help identify high-value customers, inactive users, and revenue distribution patterns.

The analysis combines data cleaning, feature engineering, and visualization to support better business decision-making.

---

## Dashboard Preview

### Overall Dashboard
<img width="1660" height="928" alt="image" src="https://github.com/user-attachments/assets/8727604f-8d76-4bfb-a229-56fa47942f6c" />

### Customer Segmentation
<img width="436" height="394" alt="image" src="https://github.com/user-attachments/assets/014abe9b-7719-432c-a751-2017c94b8224" />

### Top Customers
<img width="490" height="412" alt="image" src="https://github.com/user-attachments/assets/955fa6a0-929d-4945-8a9f-c7299a5b0678" />

---

## Key Insights
- High-value customers contribute the majority of total revenue.
- Inactive customers still generate significant revenue, indicating re-engagement opportunities.
- Revenue is concentrated within a small group of customers.
- Customer segmentation helps identify retention and growth strategies.

---

## Features
- KPI Metrics:
  - Total Customers
  - Total Sales
  - Average Order Value
  - High Value Customers
- Customer Segmentation:
  - Value-based segmentation (High, Medium, Low)
  - Recency-based segmentation (Active, Inactive, At Risk)
- Revenue analysis by customer segment
- Top customers by revenue and profit
- Interactive filtering and drill-down analysis

---

## Tech Stack
- Python (Pandas) – data cleaning and feature engineering
- SQL logic – analytical transformations applied within the workflow
- Power BI – data modeling and dashboard visualization

---

## Project Workflow
1. Data Cleaning  
   - Processed raw sales data and handled missing values using Python  

2. Feature Engineering  
   - Created customer-level metrics (total sales, profit, order count)  
   - Built customer segments based on:
     - Customer value (High, Medium, Low)
     - Customer activity (Active, Inactive, At Risk)

3. Data Modeling  
   - Imported processed data into Power BI  
   - Built measures and relationships  

4. Dashboard Development  
   - Designed KPI cards and visualizations  
   - Built segmentation-based revenue analysis  

---

## Repository Structure

```
customer-segmentation-revenue-analysis/
│
├── dashboards/
│ └── customer_segmentation_dashboard.pbix
│
├── data/
│ ├── cleaned_sales_data.csv
│ └── customer_segmentation_data.csv
│
├── notebooks/
│ └── customer_segmentation_analysis.ipynb
│
├── images/
│ ├── dashboard_overview.png
│ ├── customer_segmentation.png
│ └── top_customers.png
│
└── README.md
```

---

## Business Impact
This project helps stakeholders:
- Identify high-value customers
- Understand revenue concentration across customer groups
- Detect inactive or at-risk customers
- Support retention and re-engagement strategies
- Prioritize marketing efforts based on customer value

---

## How to Use
1. Download the repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Explore customer segments using filters and visuals  

---

## Author
Rishika Reddy
