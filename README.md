# Olympic Data Analytics | Azure End-To-End Data Engineering Project

ETl-Architecture

About Project The project is in two part

ETL of Tokyo Olympic data and implementing queries for analysis.
Dashboarding
Data Source Using GIT as our primary data source.

Azure services explored: Azure Data Factory

It used for a Data Pipeline
It provides integration service that integrates data from various sources.
Azure Data Lake Gen 2

It is an object storage.
Stores structured and unstructured data.
Azure Data bricks It is an analytical platform that provides an environment to transform the data using the power of Apache Spark.

Azure Synapse Analytics

Cloud sql data warehouse
Analyzing data with queries.
STEPS for ETL

Extract data from GIT.
Extraction is executed using ADF Pipeline
The extracted raw data will be stored in Azure Data Lake.
The raw data is transformed using Pyspark in Azure Data Bricks.
Transformed data is again stored in Azure Data Lake.
Target tables are created in Azure Synapse Analytics and transformed data are loaded to perform queries and analysis.
I have taken this project a step further by Dashboarding it in Tableau.

STEPS for Dashboarding 1.Extract the raw csv file from data lake using ADF pipeline in Azure Synapse Analytics. 2. Data pipeline transforms source data type and writes back to data lake in parquet form 3.Create spark database and point spark to parquet file. 4.Query spark table using server less sql 5.Tableau reads from server less sql and projects graph.

About
Olympic Data Analytics | Azure End-To-End Data Engineering Project

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 1 fork
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
100.0%
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
