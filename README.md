## What is ETL PIPELINE?
1. ETL stands for Extract, transform and load.
2. The basic principle of ETL is that we have some source, we have some destination and we have our driver program. 
3. What driver program will do, it will extract the data from the source considering the E, then it will do some sort of transformations(it is optional), next is the load- so this driver program will load all the transformed data or the simple data to the target source
4. So ETL pipeline is the name of this complete pipeline in which we read the data from the source, performing any transformation and then loading that data to some output destination.
   
## Project Objective:
To create a simple Extract, Transform, Load (ETL) pipeline using Databricks to gain understanding of ETL concepts and components and the process of connecting PySpark code with a database.

## Tools:
1. Databricks: Cloud-based big data processing platform that provides an integrated environment for data engineering and analytics tasks and to perform ETL pipelines.
2. Databricks Notebook: Interactive web-based interface within Databricks for writing and executing code, including PySpark scripts, SQL queries, and visualizations.
3. DBFS:  Distributed file system provided by Databricks for storing and accessing data within the Databricks environment.
4. PySpark:Python API for Apache Spark, a distributed computing framework for processing large datasets.
5. AWS: Cloud platform for hosting the PostgreSQL database.
6. AWS RDS (Amazon Relational Database Service): Fully managed relational database service provided by Amazon Web Services (AWS) for hosting PostgreSQL databases.
7. PostgreSQL Database: Open-source relational database management system used for storing and managing structured data

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


