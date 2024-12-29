# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
This project focuses on building a modern data engineering pipeline for Uber data analytics using Google Cloud Platform (GCP). The pipeline leverages Mage.ai for data orchestration, BigQuery for scalable data warehousing, Looker Studio for insightful visualization, and Cloud Storage for efficient data handling and storage.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. Programming Language: Python
2. Scripting Language: SQL
3. Google Cloud Platform
   - BiqQuery
   - Cloud Storage
   - Looker Studio
   - Compute Instance
4. Mage.ai (Modern data pipeline tool)

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

### Additional Information about data
1. Original Data Source - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Data Model Image](data_model.jpeg)

## Scripts for project
1. [Extract Python file](mage-files/extract.py)
2. [Load Python file](mage-files/load.py)
3. [Transform Python file](mage-files/transform.py)
