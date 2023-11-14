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

<img width="599" alt="Screenshot 2023-11-13 at 22 44 15" src="https://github.com/nogibjj/Individual_Project3_LinHui/assets/83142133/5259d288-c285-4e3e-8b98-007a8be0e38a">


## Trigger schedule
<img width="328" alt="Screenshot 2023-11-13 at 22 44 33" src="https://github.com/nogibjj/Individual_Project3_LinHui/assets/83142133/d39c5dfb-7148-4b5e-afe1-8af43b6300fa">



## Visualization and comment
<img width="647" alt="Screenshot 2023-11-13 at 22 45 06" src="https://github.com/nogibjj/Individual_Project3_LinHui/assets/83142133/2bbbfbbf-6da7-4df3-a57a-9b90f74a7518">

Top artists tend to have similar amount of popular songs, and it'd be good to make a diversed playlist with top songs from those artists. It would help people to explore more out of the interest to ones they love.


## Video Demo
https://www.youtube.com/watch?v=TPOPWdORElQ
