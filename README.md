# Bike Data Lakehouse

This project demonstrates the implementation of a complete Data Lakehouse using Databricks, Apache Spark, and the Medallion Architecture.

The pipeline transforms raw CSV data into clean and analytics-ready datasets through Bronze, Silver, and Gold layers.

## Technologies

- Python
- PySpark
- Apache Spark
- Databricks
- Delta Lake
- Git & GitHub

## Architecture & Concepts

The project follows a modern Data Lakehouse architecture using Databricks and the Medallion pattern.

Key concepts covered:
- Bronze, Silver, Gold layers
- Distributed processing with Apache Spark
- PySpark and Spark SQL workflows
- Data engineering orchestration
- ETL pipeline automation
- Unity Catalog integration
- Lakehouse vs Data Warehouse vs Data Lake
- Analytics maturity and scalability
- Data Mesh concepts
- Business-ready dimensional modeling

### Architecture Diagrams

#### High-Level Lakehouse Architecture
<img width="1216" height="1088" alt="photo_2026-05-07_17-03-38" src="https://github.com/user-attachments/assets/ee2b6557-742a-48a9-afcf-df8768c5b783" />


#### Databricks Workflow
<img width="1280" height="820" alt="photo_2026-05-07_17-05-11" src="https://github.com/user-attachments/assets/722e6048-5405-479b-9501-a7a6c395140b" />


#### Spark Processing Engine
<img width="983" height="1179" alt="photo_2026-05-07_17-03-40" src="https://github.com/user-attachments/assets/4415c533-f702-4202-a193-9836254fdf5b" />
<img width="1280" height="823" alt="photo_2026-05-07_17-03-42" src="https://github.com/user-attachments/assets/606bd215-e72f-412d-b2c6-223ef8e61816" />


#### Analytics Maturity
<img width="1280" height="944" alt="photo_2026-05-07_17-03-41" src="https://github.com/user-attachments/assets/dcf8d432-97ce-4dcf-9af7-e4482f71ad54" />


## Features

- End-to-end ETL pipeline
- Bronze, Silver, and Gold data layers
- Data quality validation
- Dimensional modeling
- Automated orchestration with Databricks Jobs
- GitHub integration with Databricks Repos

## Repository Structure

```bash
.
├── bronze/
├── silver/
│   ├── crm/
│   └── erp/
├── gold/
├── orchestration/
├── datasets/
└── README.md
```

## Learning Objectives

This project helped me practice:
- Building scalable Lakehouse architectures
- Using PySpark for distributed data processing
- Data transformation and validation
- ETL pipeline orchestration
- Data modeling using fact and dimension tables
- Managing projects with GitHub and Databricks

## Author

Abdullah Fathy  
Electrical Engineering Student at Sohag University  
Transitioning into Data Engineering
