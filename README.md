# mysql-glue-athena-pipeline
An end-to-end data engineering pipeline using AWS Glue, MySQL, S3, Athena, and Terraform. Includes ETL, data modeling (star schema), and Jupyter-based dashboarding.


# MySQL → AWS Glue → Athena Pipeline

This project automates data extraction from MySQL and pipelines it into AWS Glue for processing and querying in Amazon Athena.

## Features

- MySQL to S3 via AWS Glue
- Glue Crawler for table schema
- Queryable with Amazon Athena

## Requirements

- AWS CLI configured
- Python 3.x
- boto3, pandas, etc.

## Usage

```bash
python extract_and_upload.py
