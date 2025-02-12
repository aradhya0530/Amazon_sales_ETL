# Amazon_sales_ETL

## Project Overview

This project implements an end-to-end ETL (Extract, Transform, Load) pipeline for Amazon sales data. The data is processed through various stages, leveraging cloud-based storage, transformation tools, and a data warehouse for analysis.

## Pipeline Workflow

## Data Extraction & Storage

Raw sales data is extracted and stored in Azure Blob Storage containers.

## ETL Pipeline Creation

A structured ETL pipeline is designed to automate data movement and transformations.

## Loading into Data Lake

The extracted data is ingested into an Azure Data Lake for scalable storage.

## Data Transformation using Databricks

Transformation tasks, such as data cleaning, feature engineering, and aggregations, are performed using Databricks (Apache Spark).

## Loading Processed Data Back to Data Lake

The transformed data is stored back in Azure Data Lake for further processing.

## Loading into Azure Synapse Analytics

Final transformed data is loaded into Azure Synapse Analytics for SQL-based querying and analysis.

## Technologies Used

Azure Blob Storage (for raw data storage)

Azure Data Lake (for data management)

Azure Data Factory (for building the ETL pipeline)

Databricks (for data transformation using Spark)

Azure Synapse Analytics (for SQL-based data analysis)
