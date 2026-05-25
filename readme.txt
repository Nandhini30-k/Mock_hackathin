# Smart Insurance Risk & Claims Analytics Platform

## Problem Statement 6 – Hackathon Project

### Project Overview
This project focuses on building a **Smart Insurance Risk & Claims Analytics Platform** using **Snowflake Cloud Data Warehouse**, automated ETL pipelines, and interactive Power BI dashboards.

The platform is designed to process insurance claim data, analyze customer risk, identify fraud patterns, and generate business insights for insurance operations.

---

# Technologies Used

- Snowflake
- AWS S3
- Snowpipe
- Streams & Tasks
- SQL
- Power BI
- GitHub

---

# Architecture Overview

```text
AWS S3 Bucket
       ↓
Snowpipe Auto Ingestion
       ↓
RAW Layer
       ↓
STREAMS + TASKS
       ↓
CORE Layer
       ↓
MART Layer
       ↓
Power BI Dashboard
```

---

# Database Structure

## Schemas Created

```sql
AWSRAW
AWSCORE
AWSMART
```

---

# Data Pipeline Flow

## RAW Layer
- Stores raw insurance claim files from AWS S3
- Snowpipe automatically loads incoming files
- Initial validation performed

## CORE Layer
- Data cleansing and transformation
- Standardized customer and claims data
- Business rules applied

## MART Layer
- Analytical tables created
- KPI-ready datasets
- Optimized for Power BI reporting

---

# Features Implemented

## Snowflake Concepts
- Warehouses
- Databases & Schemas
- External Stages
- File Formats
- Snowpipe
- Streams
- Tasks

---

# ETL Automation

- Automated file ingestion from AWS S3
- Continuous data loading using Snowpipe
- Incremental processing using Streams
- Scheduled transformations using Tasks

---

# Governance & Security

- Role-based access control
- Data masking policy
- Secure schema management

---

# Analytics & Reporting

## Power BI Dashboard Includes:
- Total Claims
- Total Claim Amount
- Fraudulent Claims Analysis
- Risk Category Analysis
- Claims by Region
- Customer Insights
- Monthly Claims Trends

---

# SQL Implementation

## Key Operations
- Data loading
- Data transformation
- Aggregations
- Incremental processing
- KPI generation

---

# Business Use Cases

- Insurance risk analysis
- Fraud detection
- Claims monitoring
- Customer behavior analysis
- Operational reporting

---

# Project Workflow

1. Upload files to AWS S3
2. Snowpipe ingests data automatically
3. RAW tables store source data
4. Streams capture changes
5. Tasks process transformed data
6. CORE tables standardize data
7. MART tables generate reporting layer
8. Power BI visualizes insights

---

# Sample KPIs

| KPI | Description |
|---|---|
| Total Claims | Number of insurance claims |
| Fraud Rate | Percentage of suspicious claims |
| Average Claim Amount | Average amount claimed |
| High Risk Customers | Customers with high claim frequency |
| Approval Ratio | Approved vs Rejected claims |

---

# Repository Structure

```text
Smart-Insurance-Analytics
 ┣  SQL_Scripts
 ┣ 	Snowpipe_Setup
 ┣  Streams_Tasks
 ┣  PowerBI_Dashboard
 ┣  Dataset
 ┣  README.md
```

---

# Learning Outcomes

- Real-time data pipeline implementation
- Snowflake cloud architecture
- ETL automation
- Data warehousing concepts
- Power BI dashboard development
- Insurance analytics modeling

---

# Future Enhancements

- Real-time fraud alert system
- Machine learning risk prediction
- API integration
- Advanced customer segmentation

---

# Author

**Nandhini K**

Hackathon Project – Smart Insurance Risk & Claims Analytics Platform
