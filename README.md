# End-to-End Dataflow Gen2 Financial Analytics | Power BI Service

An end-to-end Business Intelligence project demonstrating how **SQL Server**, **Power BI Dataflow Gen2**, **Power Query**, **DAX**, and **Power BI Service** work together to build a centralized cloud-based reporting solution.

The project follows an enterprise-style analytics workflow where data is ingested from SQL Server into a reusable Dataflow, transformed using Power Query, analyzed using DAX, and deployed to Power BI Service with automated scheduled refresh.

---

## Business Problem

Organizations often struggle with maintaining multiple reports connected directly to operational databases, resulting in duplicated transformations, inconsistent metrics, and difficult report maintenance.

A centralized data preparation layer helps ensure consistent business logic, improves report performance, and simplifies report development across teams.

---

## Solution

This project uses **Power BI Dataflow Gen2** as the centralized ETL layer.

The Dataflow imports data from SQL Server, performs data preparation using Power Query, and serves as the single source of truth for the Power BI report. The final report is published to Power BI Service with Scheduled Refresh enabled for automated data updates.

---

## Project Workflow

```text
                SQL Server
                     │
                     ▼
        Power BI Service (Dataflow Gen2)
                     │
                     ▼
      Power Query (Cloud Transformation)
                     │
                     ▼
           Power BI Desktop
                     │
                     ▼
              DAX Measures
                     │
                     ▼
      Interactive Financial Report
                     │
                     ▼
        Publish to Power BI Service
                     │
                     ▼
           Scheduled Refresh
```

---

## Tech Stack

- Microsoft SQL Server
- Power BI Service
- Power BI Desktop
- Dataflow Gen2
- Power Query
- DAX
- Microsoft Excel
- Power BI Workspace

---

## Key Features

- Built a centralized Dataflow Gen2 pipeline
- Connected SQL Server as the primary data source
- Performed cloud-based data transformation using Power Query
- Created reusable semantic data model
- Built business KPIs using DAX
- Developed interactive financial dashboards
- Validated calculations using Excel Pivot Tables
- Published reports to Power BI Service
- Configured Scheduled Refresh
- Managed reports within a dedicated Power BI Workspace

---

## Skills Demonstrated

### Data Engineering

- Dataflow Gen2
- ETL Workflow
- Cloud Data Preparation
- Workspace Management

### Data Transformation

- Power Query
- Data Profiling
- Data Cleaning
- Data Validation

### Business Intelligence

- DAX Measures
- KPI Development
- Dashboard Development
- Financial Analytics

### Deployment

- Power BI Service
- Report Publishing
- Scheduled Refresh

---

## Repository Structure

```text
powerbi-dataflow-financial-analytics-project
│
├── dataflow.pbix
├── loan_dataset.csv
├── README.md
└── screenshots
    ├── dataflow.png
    ├── financial_report.png
    ├── semantic_model.png
    └── sql_server_to_dataflow.png
```

---

# Dashboard Preview

## Dataflow

![Dataflow](screenshots/dataflow.png)

---

## SQL Server to Dataflow

![SQL Server to Dataflow](screenshots/sql_server_to_dataflow.png)

---

## Semantic Model

![Semantic Model](screenshots/semantic_model.png)

---

## Financial Analytics Dashboard

![Financial Dashboard](screenshots/financial_report.png)

---

## Project Deliverables

- End-to-End Dataflow Gen2 Pipeline
- Financial Analytics Dashboard
- Cloud-Based ETL Workflow
- SQL Server Integration
- Interactive Power BI Report
- Automated Scheduled Refresh
- Excel-Based Data Validation
- Power BI Service Deployment

---

## Project Highlights

- Enterprise-style reporting workflow
- Centralized cloud ETL using Dataflow Gen2
- SQL Server as operational data source
- Advanced DAX calculations
- Power Query transformations
- Semantic model development
- Interactive KPI dashboard
- Automated report refresh
- Business metric validation using Excel

---

## Future Enhancements

- Implement Incremental Refresh
- Add Row-Level Security (RLS)
- Deploy using Power BI Deployment Pipelines
- Connect multiple source systems
- Build executive dashboard with drill-through pages

---

## Learning Outcomes

This project strengthened my practical understanding of:

- Power BI Service
- Dataflow Gen2
- Cloud-based ETL
- Power Query
- DAX
- Semantic Modeling
- Dashboard Development
- Scheduled Refresh
- Enterprise Reporting Workflow

---

## Repository Features

- Enterprise BI Architecture
- Cloud Data Pipeline
- Interactive Financial Dashboard
- Automated Data Refresh
- Data Validation
- Business KPI Reporting
- Production-style Workflow

---

## Author

**Sagar Bairwa**

- GitHub: https://github.com/sagar-bairwa
- LinkedIn: https://linkedin.com/in/sagarbairwa

---

⭐ If you found this project helpful, consider giving it a star.
