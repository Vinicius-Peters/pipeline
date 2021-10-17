# ETL Pipeline 

## Ferramentas Utilizadas:

###### Linux environment, Airflow, Docker, Python, AWS S3, AWS Glue and AWS Athena

## Project objective:
Pipeline under development in order to get data from the data lake that is in an S3 bucket, clean the data as needed using Python and then go up to the Data Warehouse that is in another S3 bucket and perform queries with AWS Athena and AWS Glue.

## What was done: 
- Installation of Airflow on Docker in Linux environment.
- Python script for extracting data from the data lake, necessary transformations and inserting data into the data warehouse
- AWS Glue for structuring tables and AWS Athena for queries.

## What needs to be done
- Script automation with Airflow

## Future Updates:
- Use of spark for data processing
- Use of AWS Ec2 for Clustering

![Diagram](https://raw.githubusercontent.com/Vinicius-Peters/pipeline/main/Pipeline-1.0.png)
