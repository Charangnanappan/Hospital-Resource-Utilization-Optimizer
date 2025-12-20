# Hospital Resource Utilization Optimizer  
### Patient-flow–driven Healthcare Analytics (Azure + PySpark + Power BI)

## 📌 Project Overview

Hospitals operate with limited resources such as beds, staff, and facilities.  
Efficient utilization of these resources depends heavily on **patient flow patterns**.

This project implements an **end-to-end cloud data engineering and analytics pipeline** to analyze hospital admission data and derive insights that support **resource utilization planning**, using historical patient data as demand signals.

## 🎯 Business Objective

To help hospital administrators:
- Understand admission trends over time
- Identify emergency vs OPD demand patterns
- Analyze length of stay as a proxy for bed utilization
- Observe outcome distributions (discharge, mortality)
- Support data-driven operational planning

> 📌 Note: Patient flow is used as a **proxy** to estimate hospital resource utilization (beds, staff workload).

## 🧠 Key Analytics Questions Answered

- How do admissions vary by month and year?
- What is the average length of stay and how does it change over time?
- What proportion of admissions are emergency vs OPD?
- How do outcomes differ across demographics?
- How does patient demand fluctuate across time periods?

## 🏗️ Architecture

Google Colab (Data Cleaning)

Azure Data Lake Gen2 (Raw Layer)

Azure Databricks (PySpark Processing)

Delta Lake (Curated & Gold Layers)

Power BI Dashboards

## 🛠️ Tools & Technologies

**Data Engineering**
- Azure Data Lake Gen2
- Azure Databricks
- PySpark
- Delta Lake

**Analytics & Visualization**
- Power BI Desktop
- DAX Measures

**Development**
- Google Colab (initial data preparation)
- GitHub (documentation & version control)

## 📊 Dashboards Created (Power BI)

- Executive Summary (KPIs & slicers)
- Monthly Admission Trends
- Weekly Patterns
- Gender-based Analysis
- Admission Outcome Analysis
- Emergency vs OPD Comparison
- Rural vs Urban Distribution

> Dashboards are fully interactive using slicers for year, month, gender, and admission type.


## 📈 Key Metrics

- Total Admissions
- Average Length of Stay (proxy for bed utilization)
- Emergency Admission Percentage
- Mortality Rate

## 🔍 Project Scope Clarification

This project focuses on **patient-flow–driven resource utilization**:
- Direct resource metrics (beds, doctors, equipment) are not explicitly available
- Length of stay and admission volume act as **indirect indicators**
- The architecture is scalable to integrate real-time or operational hospital data

## 🚀 Future Enhancements

- Integrate real-time admission feeds
- Add predictive forecasting for bed demand
- Include staffing and equipment utilization data
- Apply ML models for capacity optimization

## Summary

> “This project demonstrates how cloud-based data engineering and analytics can be used to analyze hospital patient flow and support resource utilization planning. Using Azure, PySpark, Delta Lake, and Power BI, I built an end-to-end pipeline and interactive dashboards that translate patient demand into operational insights.”


## 📎 Author

**Charan Gnanappan**  
Master’s in Data Analytics  
