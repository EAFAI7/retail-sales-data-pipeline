# Retail Revenue Pipeline

Batch ETL pipeline for retail sales data using Databricks and Delta Lake.

## Project Overview

This project demonstrates a scalable batch data engineering workflow with retail sales data sourced from public datasets hosted on GitHub. The pipeline includes data ingestion, cleaning, transformation, and aggregation steps implemented in Databricks using Apache Spark and Delta Lake.

It’s designed as a portfolio piece showcasing skills critical for cloud data engineering roles, especially on Google Cloud Platform (GCP).

## Features

- Ingest CSV files directly from GitHub into Databricks Spark DataFrames  
- Auto schema inference and data validation  
- Data cleaning and business-rule based transformations  
- Delta Lake tables for reliable storage and easy versioning  
- Aggregated revenue metrics by product, category, and region  
- SQL queries and notebooks demonstrating the entire pipeline  

## Repo Structure

retail-revenue-pipeline/
├── data/ # Sample CSV files (sales, customers, products)
├── notebooks/ # Databricks notebooks for ingestion & processing
├── sql/ # SQL scripts for transformations and aggregations
├── scripts/ # Python scripts for data ingestion / automation
├── dashboard/ # BI dashboard configs or screenshots (optional)
├── README.md # This file


