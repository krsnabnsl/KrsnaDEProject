Overview - 
This project implements a robust Retail Analytics Platform using the Medallion Architecture (Bronze → Silver → Gold) to process and analyze retail data efficiently.
We ingest raw data from Amazon S3, perform structured streaming transformations with Databricks Auto Loader, and apply Slowly Changing Dimensions (SCD) to maintain historical data integrity.

Technologies Used - 
Databricks
Delta Lake
Structured Streaming (Auto Loader)
Apache Spark (PySpark)
Amazon S3
Medallion Architecture
SCD Type-2 Implementation