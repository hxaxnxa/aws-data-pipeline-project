# aws-data-pipeline-project
A complete data pipeline solution to upload, transform, and visualize CSV data using AWS services (Lambda, S3, Glue, Athena, QuickSight).

# End-to-End Data Pipeline Project for CSV Processing & Visualization

## Project Overview
This project is designed to demonstrate an end-to-end workflow for processing CSV data using AWS. It covers data ingestion, transformation, storage, and visualization.

## Workflow Steps
1. **CSV Creation**: Generated a CSV file with sample data.
2. **Web App Development**: Developed an HTML/JavaScript web app for file uploads.
3. **AWS Lambda Integration**: Implemented a Lambda function for file storage in S3.
4. **Glue Crawler Setup**: Configured Glue Crawler to create a schema table from the uploaded CSV.
5. **ETL Job Creation**: Developed and deployed an AWS Glue ETL job to transform data and store it in Parquet format.
6. **Data Analysis with Athena**: Executed SQL queries using AWS Athena.
7. **Visualization with QuickSight**: Built interactive dashboards to visualize the data.

## Getting Started
Follow the instructions in the [Setup Guide](./SETUP.md) to deploy and test the pipeline.

