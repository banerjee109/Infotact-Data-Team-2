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

---

## Installation & Setup

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/<Jainam249>/Infotact-Data-Team-2.git
```

Navigate to the project directory:

```bash
cd Infotact-Data-Team-2
```

---

### 2. Install Python Dependencies

Install all required Python libraries:

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` file, install the libraries manually:

```bash
pip install pandas numpy matplotlib sqlalchemy psycopg2-binary jupyter
```

---

### 3. Open the Jupyter Notebooks

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in the following order:

1. `01_Dataset_Generation.ipynb`
2. `02_Duplicate_Timestamp_Cleaning.ipynb`
3. `03_EDA.ipynb`
4. `04_Business_Metrics.ipynb`
5. `05_SQL_Database_Setup.ipynb`
6. `06_Attribution_Modeling.ipynb`

---

### 4. PostgreSQL Setup

1. Install PostgreSQL.
2. Create a database named `marketing_db`.
3. Update the database connection string in `05_SQL_Database_Setup.ipynb` with your PostgreSQL username and password.
4. Run the notebook to import the datasets into PostgreSQL.

---

### 5. Power BI Dashboard

1. Open the `Marketing_Attribution_Dashboard.pbix` file from the `dashboard/` folder.
2. Refresh the data if required.
3. Explore the interactive dashboard using the available filters and slicers.

---

### System Requirements

- Python 3.10 or later
- Jupyter Notebook
- PostgreSQL
- Power BI Desktop
- Git