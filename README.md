# data-engineer-project
“This GitHub project showcases an end-to-end ETL pipeline using Azure Data Factory, Databricks (PySpark), Delta Lake, and SQL. It demonstrates ingestion, transformation, validation, incremental load, and multi-layer architecture (Bronze–Silver–Gold). Highlights strong cloud data engineering and pipeline optimization skills.”
Online Retail ETL Pipeline (GCP + Airflow)
Overview
This project demonstrates an end-to-end batch ETL pipeline for an Online Retail dataset using Google Cloud Platform (GCP) and Apache Airflow (Cloud Composer).

The pipeline is designed to:

Transform online retail data using Python
Orchestrate tasks using Airflow
Load cleaned data into BigQuery for analytics
This is a daily scheduled batch pipeline.

What the Pipeline Does
Reads online retail data
Cleans and transforms the data using Python
Loads processed data into BigQuery
Manages execution using an Airflow DAG
Tech Stack
Google Cloud Platform (GCP)
Apache Airflow (Cloud Composer)
Google Cloud Storage (GCS)
BigQuery
Python
Pandas
Project Structure
dags/
├── online_retail_etl_pipeline.py
│
├── transformation/
│   └── clean_retail_data.py
│
├── loading/
│   └── load_to_bigquery.py
│
├── config/
│   └── config.yaml
│
└── README.md
