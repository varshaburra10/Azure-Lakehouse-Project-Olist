# Azure Lakehouse Project - Olist E-Commerce Dataset

## Project Overview

This project demonstrates an end-to-end Azure Lakehouse architecture using the Olist E-Commerce dataset.

The solution implements a modern Data Engineering pipeline that ingests raw data from Azure Data Lake Storage Gen2 using Azure Data Factory, processes and transforms data using Azure Databricks and Delta Lake, and prepares curated datasets for analytics and reporting.

## Technologies Used

* Azure Data Lake Storage Gen2 (ADLS)
* Azure Data Factory (ADF)
* Azure Databricks
* PySpark
* Delta Lake
* Unity Catalog
* Azure SQL (Future Enhancement)
* Power BI (Future Enhancement)

## Architecture

Olist Dataset

↓

ADLS Gen2 (Raw Layer)

↓

Azure Data Factory

↓

ADLS Gen2 (Bronze Layer)

↓

Azure Databricks

↓

Delta Lake (Silver Layer)

↓

Business Transformations

↓

Gold Layer

↓

Power BI

## Current Progress

### Completed

* ADLS Gen2 Setup
* Azure Data Factory Setup
* Metadata Driven File Discovery
* Get Metadata Activity
* ForEach Activity
* Parameterized Datasets
* Dynamic File Processing
* Copy Activity
* Multi-file Ingestion Framework

### In Progress

* Databricks Bronze Layer
* Delta Lake Implementation
* Unity Catalog

### Planned

* Silver Layer Transformations
* Gold Layer Aggregations
* SQL Validation Layer
* Power BI Dashboard

## Author

Sai Sha
