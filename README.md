# Customer Shopping Behavior Analysis
**End-to-End Data Analytics Project (Python · SQL · Power BI · Gamma)**

## Inspiration & Reference
This project was completed as a learning-based, hands-on replication inspired by the work of  
**Amlan Mohanty**, whose tutorial clearly demonstrates a real-world data analytics workflow.

- YouTube Tutorial: https://www.youtube.com/watch?v=5PrZvPeUw60  
- Reference Repository: https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI  

Following this reference, I independently rebuilt the full pipeline to strengthen my understanding
of SQL-based analysis, dashboard design, and business-oriented data storytelling.

---

## Overview
This project presents a complete **end-to-end data analytics workflow**, starting from raw customer
transaction data and ending with actionable business insights delivered through dashboards,
reports, and presentations.

The primary objective is to analyze customer shopping behavior using Python and SQL,
and communicate insights effectively using Power BI.

---

## Dataset
- **Name:** Customer Shopping Behavior Dataset
- **Format:** CSV
- **Description:** Transaction-level customer data including purchase behavior,
  product categories, and spending patterns.

---

## Tools & Technologies
- **Python:** pandas, numpy, matplotlib, seaborn
- **SQL:** PostgreSQL / MySQL / SQL Server
- **Database:** Relational SQL Database
- **Visualization:** Power BI
- **Reporting:** PDF Report
- **Presentation:** Gamma

---

## Project Steps

### 1. Data Loading & Cleaning (Python)
- Loaded raw data from CSV files
- Cleaned and preprocessed data
- Performed exploratory data analysis (EDA)
- Created derived features for analysis

### 2. SQL Analysis
- Imported cleaned data into a SQL database
- Wrote SQL queries to analyze:
  - Customer spending behavior
  - Purchase frequency
  - Category-level trends

### 3. Power BI Dashboard
- Connected Power BI to the SQL database
- Built an interactive dashboard with:
  - Key performance indicators (KPIs)
  - Customer segmentation
  - Sales and category trends

### 4. Reporting & Presentation
- Summarized insights in a structured analytics report
- Created a professional presentation using Gamma

---

## Dashboard
The Power BI dashboard enables:
- High-level performance tracking
- Customer behavior analysis
- Data-driven decision support

**File:** `customer_behavior_dashboard.pbix`

---

## Results & Insights
- Identified high-value customer segments
- Discovered key purchasing trends
- Generated insights for targeted marketing strategies

---

## Repository Structure
├── data/
│ └── customer_shopping_behavior.csv
├── sql/
│ └── customer_behavior_query.sql
├── dashboard/
│ └── customer_behavior_dashboard.pbix
├── report/
│ └── Customer Shopping Behavior Analysis.pdf
├── notebooks/
│ └── data_analysis.ipynb
└── README.md


---

## How to Run

### Python
```bash
pip install pandas numpy matplotlib seaborn

**SQL**
Load data into your SQL database
Run queries from customer_behavior_query.sql

**Power BI**
Open customer_behavior_dashboard.pbix
Update database connection if needed
Refresh data

**Key Takeaway**
This project demonstrates my ability to build an end-to-end data analytics pipeline,
integrating Python, SQL, and BI tools to deliver business-focused insights.


