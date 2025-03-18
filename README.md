ETL Pipeline with Data Fusion, Airflow, and BigQuery
This project demonstrates an ETL (Extract, Transform, Load) pipeline utilizing Data Fusion, Airflow, and BigQuery to manage and process data efficiently.

Data Fusion: Acts as the data integration platform for building and orchestrating data pipelines. It simplifies connecting to various data sources and applying transformations through a visual interface.
Airflow: Manages workflow automation and scheduling. It handles pipeline dependencies, retries, and task execution logic.
BigQuery: Serves as the data warehouse for storing and querying processed data at scale.

Workflow Overview:
Data Extraction: Data Fusion pulls data from source systems (e.g., cloud storage, databases).
Transformation: Data Fusion applies transformations such as data cleansing, aggregation, and enrichment.
Loading: The transformed data is loaded into BigQuery for analysis.
Orchestration: Airflow triggers and monitors the Data Fusion pipeline execution, ensuring proper sequencing and handling failures gracefully.

Key Features:
Scalable and serverless architecture
Automated scheduling and monitoring
Efficient data processing with minimal coding effort
