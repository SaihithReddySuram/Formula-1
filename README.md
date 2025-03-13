# Formula-1
Project Overview
This project automates the ingestion, transformation, and analysis of Formula 1 race data using Azure Data Factory (ADF) and Databricks. The pipeline fetches race statistics, processes them in Databricks, and makes them available for analysis and reporting.

Prerequisites

Azure Subscription
Azure Data Factory Instance
Azure Blob Storage (for raw data storage)
Azure Databricks Workspace

Installation & Setup

1. Setup Azure Blob Storage
Create a Storage Account in Azure.
Create a container (e.g., f1-data) to store raw files.

2. Configure Azure Data Factory
Create a new Data Factory Instance.
Set up Linked Services for Blob Storage and Databricks.
  Develop Pipelines for:
    Extracting data from APIs / CSV files.
    Loading raw data into Blob Storage.
    Triggering Databricks jobs.

3. Develop Databricks Notebooks
Set up Databricks Workspace and create a cluster.
  Develop PySpark notebooks to:
    Read raw data from Blob Storage.
    Clean, transform, and aggregate the data.
    Write processed data to Delta Tables.

4. Automate Pipelines in ADF

Schedule data refresh using ADF Triggers (e.g., daily or hourly updates).
Monitor pipeline execution in ADF Monitoring.

5. Data Consumption & Visualization

Query processed data using Databricks SQL.

https://adb-4018443758320461.1.azuredatabricks.net/browse/folders/2397766008898624?o=4018443758320461
