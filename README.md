# Databricks ETL Pipeline

Pipeline steps:

1. Use Databricks features to explore a raw dataset.

2. Create a Databricks notebook to ingest raw source data and write the raw data to a target table.

3. Create a Databricks notebook to transform the raw source data and write the transformed data to a target table.

4. Create a Databricks notebook to load the transformed data and plot results, with proper error handling and data validation.

5. Automate the data pipeline with a Databricks job.

## Delta Lake
The transformed data is stored as Delta Lake file, as it's a reliable form with high performace.
It's retrieved from `dbfs:/user/hive/warehouse/prepared_song_data`


## Notebooks
Scripts are available in this repo.


## Spark SQL
Spark SQL offers high-performance, scalable data processing across diverse sources, with seamless integration in the Apache Spark ecosystem. It's used for data processing in this project.


## Error handling and data validation
Try-except is used in the program to make sure file is read without error, and data quality is good to proceed with.


## Workflow job



## Trigger schedule



## Visualization and comment



## Video demo
