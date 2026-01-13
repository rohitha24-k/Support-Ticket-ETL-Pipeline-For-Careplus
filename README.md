# Support Ticket ETL Pipeline For Careplus 

## Overview
An event-driven AWS ETL pipeline built for the **Customer Support (BPO) domain** to automate ingestion, transformation, and analytics of support ticket and log data. The project creates a **single source of truth** for reliable, near real-time reporting.

---

## High-Level Architecture
- **Amazon S3** – Data lake for raw and curated data  
- **AWS Lambda** – Event-driven orchestration and log processing  
- **AWS Glue** – Batch transformation of structured ticket data  
- **Amazon Redshift** – Centralized data warehouse  
- **Power BI** – Analytics and dashboards  

Microsoft PowerBI : https://app.powerbi.com/view?r=eyJrIjoiZDYxNDJmYmYtMGE0NC00MDg0LTllZGUtYjU2MmE2ZmEyNDMyIiwidCI6IjgwOGNjODNlLWE1NDYtNDdlNy1hMDNmLTczYTFlYmJhMjRmMyIsImMiOjEwfQ%3D%3D&pageName=6c49076e5d54167ab0c8

---

## What This Project Does
- Ingests structured ticket CSVs and unstructured log files into S3  
- Uses Lambda triggers to orchestrate transformations  
- Converts logs to Parquet and cleans ticket data using Glue  
- Loads data incrementally into Redshift (no duplicates)  
- Powers near real-time Power BI dashboards  

---

## Key Outcome
Automated manual reporting workflows and enabled consistent, up-to-date insights through a centralized data warehouse

---

## Author
- Rohitha Konakalla
- Linkedin : https://www.linkedin.com/in/rohitha-konakalla/
- Email : rohithakonakalla96@gmail.com


