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

## Architecture

The project follows the Medallion Architecture:

- Bronze Layer: Raw data ingestion from source CSV files
- Silver Layer: Data cleaning, validation, and transformation
- Gold Layer: Business-ready dimensional models for analytics

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
