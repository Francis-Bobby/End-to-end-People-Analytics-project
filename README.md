Business Problem
High employee turnover is costly — estimates suggest replacing an employee costs 50–200% of their annual salary. HR teams need to identify who is at risk of leaving, why, and when to intervene.
This project simulates a real-world People Analytics workflow: cleaning raw HR data, engineering features, running exploratory analysis, and delivering an interactive dashboard for HR business partners.

Objectives

Identify the top drivers of employee attrition
Segment at-risk employee profiles by department, tenure, and role
Build KPI dashboards to track attrition trends over time
Deliver actionable insights for HR and senior leadership


Project Structure
hr-attrition-analytics/
├── data/
│   ├── raw/                  # Original IBM HR dataset
│   └── processed/            # Cleaned dataset after Python pipeline
├── sql/
│   ├── 01_create_tables.sql  # Schema definition
│   ├── 02_kpi_queries.sql    # Attrition rate, headcount, avg tenure
│   └── 03_segment_analysis.sql # Breakdown by dept, age band, role
├── notebooks/
│   └── hr_eda.ipynb          # Python EDA and feature engineering
├── dashboard/
│   ├── hr_dashboard.pbix     # Power BI file
│   └── screenshots/          # Dashboard preview images
├── requirements.txt
└── README.md

Tech Stack
LayerToolData Cleaning & EDAPython (Pandas, Matplotlib, Seaborn)Data Storage & QueriesSQL (SQLite / PostgreSQL)VisualisationPower BI (DAX, KPI Cards, Slicers)EnvironmentJupyter Notebook

Dataset
Source: IBM HR Analytics Employee Attrition & Performance — Kaggle

1,470 employee records
35 features including Age, Department, JobRole, MonthlyIncome, YearsAtCompany, Attrition

Author
Francis Bobby Joshua Aaron
Data Analyst | M.Sc. Digital Business Analytics — EMLV Paris
LinkedIn • Portfolio
