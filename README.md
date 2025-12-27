# uber_data_analytics

**Project Overview**

This project focuses on performing large-scale data analytics on Uber ride data using cloud-based tools, primarily Google Cloud Platform (GCP). The analysis extracts actionable insights related to ride demand, trip patterns, fare distribution, and peak hours to support operational decision-making and urban mobility planning.
The project demonstrates the effectiveness of cloud-native data pipelines, automated ETL workflows, and interactive dashboards for real-world transportation data.


**Objectives**

Build a scalable cloud-based data pipeline for Uber ride data.

Perform automated data cleaning and transformation.

Analyze large datasets using BigQuery.

Create interactive Power BI dashboards.

Demonstrate the use of GCP tools for big data analytics.

**Dataset**

Source: NYC Taxi and Limousine Commission (TLC).

Data Type: Yellow and Green Taxi trip records.

**Methodology**

Data Acquisition - Downloaded NYC TLC taxi datasets.

Data Storage - Uploaded raw data to Google Cloud Storage.

Processing - Used Compute Engine instances for handling large datasets.

ETL Pipeline - Mage used for Extract, Transform, and Load automation.

Data cleaning, schema validation, and transformations applied.

Analytics - BigQuery used for fast SQL-based analysis.

Visualization - Power BI dashboards created for insights and reporting.

**Implementation Highlights**

Fact table design for efficient querying.

Automated Mage pipelines for transformation.

Exported transformed tables to BigQuery.

Interactive dashboards showcasing:
Total Trips
Total Revenue
Total Tips
Average Fare

