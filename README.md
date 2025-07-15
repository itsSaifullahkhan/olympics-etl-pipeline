ETL CSV Cleaning using AWS Glue, Athena, Pandas & S3

This project demonstrates a fully automated ETL pipeline for processing CSV files stored in Amazon S3. Using AWS Glue Crawlers and Athena, raw data is cataloged and queried, then cleaned using Python (Pandas), and finally uploaded back to S3 using Boto3.



 🛠️ Tech Stack

- AWS S3 – Source and destination for data
- AWS Glue Crawler – To catalog raw CSV files
- Amazon Athena – SQL-based data querying
- Python – For transformation
- Pandas – Data cleaning and manipulation
- Boto3 – Python SDK to interact with AWS



 📌 Pipeline Steps

1. Upload raw CSV files to S3 (`raw/` folder)
2. Run AWS Glue Crawler to create Data Catalog
3. Query the data using Amazon Athena
4. Use Python + Pandas to clean/filter data
5. Upload final cleaned data to S3 (`cleaned/` folder)
