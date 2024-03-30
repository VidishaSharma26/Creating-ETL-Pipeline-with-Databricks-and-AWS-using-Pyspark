## What is ETL PIPELINE?
1. ETL stands for Extract, transform and load.
2. The basic principle of ETL is that we have some source, we have some destination and we have our driver program. 
3. What driver program will do, it will extract the data from the source considering the E, then it will do some sort of transformations(it is optional), next is the load- so this driver program will load all the transformed data or the simple data to the target source
4. So ETL pipeline is the name of this complete pipeline in which we read the data from the source, performing any transformation and then loading that data to some output destination.
   
## Project Objective:
To create a simple Extract, Transform, Load (ETL) pipeline using Databricks to gain understanding of ETL concepts and components and the process of connecting PySpark code with a database.

## Tools:
1. Databricks: Platform for executing the ETL pipeline.
2. Databricks Notebook: PySpark script executed within Databricks environment for ETL operations.
3. DBFS: Databricks File System serving as the source of raw data.
4. PySpark: Python library used for data processing within Databricks.
5. AWS: Cloud platform for hosting the PostgreSQL database.
6. AWS RDS: Relational Database Service provided by AWS for hosting the PostgreSQL database.

## Pipeline Steps:
1. Data Extraction: Read data from the text file stored in DBFS using PySpark.
2. Data Transformation: Perform necessary transformations on the data using PySpark in our case we will count number of words present in a list.
3. Data Loading: For Data loading we will create the jdbc connection to the AWS RDS instance and also connect the AWS RDS instance with our local Postgres PgAdmin so that we 
   can query the transformed data through our local machine.

## Learning Objectives:
1. Understand the importance of data extraction, transformation, and loading.
2. Gain practical knowledge of using Databricks and AWS for ETL workflows.
3. Learn how to handle data across different platforms and services.

## Output-
After successfully creating a connection with AWS RDS instance, we can query the text file in our local Postgre PgAdmin


## Architecture-
![Architecture of ETL pipeline](https://github.com/VidishaSharma26/ETL-Pipeline-Loading-Text-file-from-DBFS-to-Postgres-Database-in-AWS-RDS-Simple-pyspark-project/assets/132566486/23c82b7d-cb04-425c-a2bd-2c44b159eba0)


