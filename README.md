# Support-Ticket-ETL-Pipeline-For-Careplus

This project is an end-to-end AWS-based ETL pipeline built for the **Customer Support (BPO) domain** to automate support ticket and log data processing and enable reliable analytics.

CarePlus generates large volumes of structured support ticket data and unstructured application log files. Previously, insights were derived manually using Excel, BI tools, and ad-hoc SQL queries, resulting in delayed and inconsistent KPI reporting.

To address this, this project implements a scalable data pipeline that ingests, cleans, transforms, and centralizes data into a single source of truth. The solution uses Amazon S3 as a data lake, AWS Lambda for event-driven log processing, AWS Glue for batch transformation of ticket data, and Amazon Redshift as the analytical data warehouse. The processed data powers near real-time Power BI dashboards for management reporting and decision-making.

This architecture eliminates manual data preparation, improves data consistency, and enables faster, more accurate insights across customer support operations.
