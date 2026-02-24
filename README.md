

# Azure Lakehouse Data Engineering Pipeline (Azure Data Factory + Databricks + Delta Lake)

## Project Overview

This project implements a scalable Azure Lakehouse Data Engineering pipeline using Azure Data Factory, Azure Databricks, and Azure Data Lake Storage Gen2. The pipeline follows the Medallion Architecture to ingest, store, and transform data efficiently using cloud-native data engineering tools.

The solution demonstrates real-world data engineering workflows including incremental ingestion, distributed data processing using Spark, and structured storage using Delta Lake.

---

## Architecture

<img width="1536" height="1024" alt="Project_Architecture" src="https://github.com/user-attachments/assets/7c3a1340-6b14-4087-823f-7f831f9fa4c2" />


Data Flow:

Azure SQL Database → Azure Data Factory → ADLS Gen2 (Bronze Layer) → Azure Databricks → Silver Layer (Delta Tables)

---

## Tech Stack

- Azure Data Factory
- Azure Databricks
- PySpark
- Spark Structured Streaming
- Delta Lake
- Azure Data Lake Storage Gen2
- Azure SQL Database
- Unity Catalog

---

## Key Features Implemented

### Data Ingestion (Bronze Layer)

- Built incremental data ingestion pipelines using Azure Data Factory
- Extracted structured data from Azure SQL Database
- Stored raw data in Azure Data Lake Storage Gen2
- Designed scalable and reusable ingestion pipelines

### Data Transformation (Silver Layer)

- Used Azure Databricks for distributed data processing
- Implemented Spark Structured Streaming with Autoloader
- Cleaned and transformed raw data using PySpark
- Stored processed data in Delta Lake format

### Data Storage and Lakehouse Architecture

- Implemented Bronze and Silver layers of Medallion Architecture
- Used Delta Lake for reliable and scalable storage
- Ensured schema evolution and fault-tolerant data processing

### Governance and Data Management

- Integrated Unity Catalog for structured data management
- Organized data into logical lakehouse layers
- Designed modular Databricks notebooks for reusable transformations

---<img width="1920" height="1080" alt="Screenshot (356)" src="https://github.com/user-attachments/assets/73841898-5681-4c8c-b960-24def0993196" />
<img width="1920" height="1080" alt="Screenshot (357)" src="https://github.com/user-attachments/assets/bb02a813-5a2c-45f2-8b89-0ad7be008ebc" />
<img width="1920" height="1080" alt="Screenshot (358)" src="https://github.com/user-attachments/assets/40385f37-3cb2-46ce-97d2-09bc7932ecdc" />
<img width="1920" height="1080" alt="Screenshot (359)" src="https://github.com/user-attachments/assets/bcd4d703-3054-4648-95d8-1ab3d23f5206" />




