# Infotact Data Team 2

# Marketing Attribution & ROI Dashboard

## Overview

This project analyzes marketing campaign performance using Python, SQL, and Power BI. It provides insights into advertising spend, customer conversions, campaign effectiveness, and Return on Ad Spend (ROAS) through data cleaning, business metric calculations, attribution modeling, and interactive dashboards.

### Objectives

- Analyze marketing campaign spend
- Calculate key business KPIs
- Perform attribution modeling
- Measure Return on Ad Spend (ROAS)
- Build an interactive Power BI dashboard

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Power BI |
| Database | PostgreSQL |
| SQL Toolkit | SQLAlchemy, psycopg2 |
| Development Environment | Jupyter Notebook, VS Code |
| Version Control | Git, GitHub |

---

## Datasets

The project uses three datasets:

1. **Ad Spend Data**
   - Marketing channel
   - Campaign
   - Amount Spent
   - Clicks
   - Impressions
   - CPC

2. **Web Analytics Log**
   - Session ID
   - User ID
   - Timestamp
   - Traffic Channel
   - Device
   - Session Duration

3. **CRM Conversion Data**
   - Customer ID
   - Conversion Date
   - Revenue
   - Last Touch Channel
   - Product Purchased
   - Country

---

## Key Performance Indicators (KPIs)

- Total Spend
- Total Revenue
- Total Clicks
- Total Impressions
- Total Conversions
- Click Through Rate (CTR)
- Cost Per Click (CPC)
- Customer Acquisition Cost (CAC)
- Return On Ad Spend (ROAS)

---

## Attribution Models

- First Touch Attribution
- Last Touch Attribution
- Revenue Attribution

---

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- PostgreSQL
- SQLAlchemy
- Power BI
- Git
- GitHub

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Business KPI Calculation
5. SQL Database Setup
6. Attribution Modeling
7. Interactive Power BI Dashboard

---

## Dashboard Features

- Marketing Performance Overview
- Spend by Channel
- Revenue by Channel
- Campaign Performance
- Device Distribution
- Country-wise Conversions
- Interactive Filters and Slicers

---

## Folder Structure

```text
Infotact-Data-Team-2/
│
├── dashboard/
│   └── Marketing_Attribution_Dashboard.pbix
│
├── datasets/
│   ├── ad_spend_data.csv
│   ├── web_analytics_log.csv
│   └── crm_conversion_data.csv
│
├── notebooks/
│   ├── 01_Dataset_Generation.ipynb
│   ├── 02_Duplicate_Timestamp_Cleaning.ipynb
│   ├── 03_EDA.ipynb
│   ├── 04_Business_Metrics.ipynb
│   ├── 05_SQL_Database_Setup.ipynb
│   └── 06_Attribution_Modeling.ipynb
│
├── reports/
│   └── duplicate_timestamp_report.md
│
├── screenshots/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   └── business_metrics.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

### Folder Description

| Folder/File | Description |
|-------------|-------------|
| **dashboard/** | Contains the interactive Power BI dashboard (.pbix) |
| **datasets/** | Stores the CSV datasets used for analysis |
| **notebooks/** | Jupyter notebooks covering data preparation, analysis, SQL setup, and attribution modeling |
| **reports/** | Project reports and documentation |
| **screenshots/** | Dashboard screenshots used in the README and project documentation |
| **README.md** | Project overview, setup instructions, and documentation |
| **requirements.txt** | Python package dependencies |
| **.gitignore** | Files and folders ignored by Git |