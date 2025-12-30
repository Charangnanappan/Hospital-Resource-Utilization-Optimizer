# Hospital Resource Utilization Optimizer  
### Patient-flow–driven Healthcare Analytics (Azure • PySpark • SQL Server • Power BI • Python/Colab)

## 📌 Project Overview

The Hospital Resource Utilization Optimizer is an end-to-end healthcare analytics project focused on analyzing hospital admission data to understand patient flow and its impact on hospital resource utilization. The project identifies admission trends, department workload, length-of-stay patterns, and long-stay patient behavior to support informed operational planning.

The workflow combines cloud-based data engineering on Azure, SQL-based analytics, and business-focused visualization using Power BI. Patient flow metrics are used as a proxy to evaluate hospital resource demand such as bed utilization and staff workload.

## 🎯 Business Objective

To help hospital administrators and operations teams:
Understand admission trends across time
Compare Emergency vs OPD demand patterns
Analyze Length of Stay as a proxy for bed utilization
Identify long-stay patients impacting capacity
Support data-driven hospital resource planning
Note: Patient flow and length of stay are used as indirect indicators of hospital resource utilization due to the absence of direct operational metrics.

> 📌 Note: Patient flow is used as a **proxy** to estimate hospital resource utilization (beds, staff workload).

## 🧠 Key Analytics Questions Answered

- How do admissions vary by month and year?
- What is the average length of stay and how does it change over time?
- What proportion of admissions are emergency vs OPD?
- How do outcomes differ across demographics?
- How does patient demand fluctuate across time periods?

## 🏗️ Architecture

Google Colab – Initial data cleaning and feature engineering using Python
Azure Data Lake Gen2 – Storage of cleaned admission data (raw layer)
Azure Databricks (PySpark) – Data exploration and validation
Delta Lake – Curated and analytics-ready datasets
SQL Server (SSMS) – SQL-based KPI analysis and aggregation
Power BI – Interactive dashboards and business insights

## 🛠️ Tools & Technologies

**Data Engineering**
Azure Data Lake Gen2
Azure Databricks
PySpark
Delta Lake

**Analytics & Visualization**
SQL Server (SSMS)
SQL
Power BI Desktop
DAX Measures

**Development**
Power BI Desktop
DAX Measures

## 📊 Dashboards Created (Power BI)

Executive Summary (Key KPIs & slicers)
Monthly Admission Trends
Weekly Admission Patterns
Emergency vs OPD Comparison
Gender-based Admission Analysis
Admission Outcome Distribution
Rural vs Urban Admission Analysis
Dashboards are fully interactive using slicers for year, month, gender, and admission type.

## 📈 Key Metrics

Total hospital admissions
Average Length of Stay (ALOS), calculated with and without outliers
Department-wise admission distribution (Emergency vs OPD)
Monthly admission trends and peak demand periods
Long-stay patient analysis (7–30 days) impacting bed utilization

## 🔍 Project Scope Clarification

This project focuses on patient-flow–driven resource utilization analytics:
Direct resource metrics (beds, staff, equipment) are not explicitly available
Admission volume and length of stay act as proxy indicators
The architecture is scalable and can integrate operational hospital systems in the future

## 🚀 Future Enhancements
Integrate real-time admission data feeds
Implement forecasting models for bed demand
Include staffing and equipment utilization datasets
Apply machine learning for capacity optimization

## Summary
This project demonstrates how cloud-based data engineering, SQL analytics, and visualization can be combined to analyze hospital patient flow and support resource utilization planning. Using Azure, PySpark, SQL Server, and Power BI, I built an end-to-end analytics pipeline that converts raw admission data into actionable operational insights.


## 📎 Author

**Charan Gnanappan**  
Master’s in Data Analytics  
