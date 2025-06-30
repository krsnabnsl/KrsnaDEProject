Project Name: Retail Data Lake with Medallion Architecture (Not Yet Finalized)

Data Sources:
- Kafka: Real-time transaction stream
- MySQL: Product Catalog
- S3: Inventory Snapshots
- API: Pricing service

Technologies:
- Python, PySpark, SQL
- Databricks (Community Edition)
- Open-source Kafka
- GitHub for CI/CD

Architecture: Medallion (Bronze → Silver → Gold)
- Bronze: Raw data with minimal schema enforcement
- Silver: Cleaned & deduplicated
- Gold: Fact & Dimension tables for reporting

Modeling: Star Schema in Gold Layer
- `fact_sales`, `dim_product`, `dim_customer`, `dim_time`

Orchestration: Databricks Workflows

Validation: Python scripts for schema & quality checks
