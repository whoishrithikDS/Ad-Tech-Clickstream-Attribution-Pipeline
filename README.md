# Ad-Tech-Clickstream-Attribution-Pipeline
This project simulates a real-world ad-tech data engineering pipeline that processes clickstream data to perform last-click attribution and revenue analysis. The pipeline is designed to mirror production-grade architectures used in digital advertising platforms.

**Architecture**

The pipeline follows a modern cloud-based data engineering workflow:

Data Generation → Databricks (PySpark ETL) → Amazon S3 (Parquet) → Amazon Athena → Airflow Orchestration

**Key Features**
Clickstream Data Simulation
Generated realistic user interaction data (~500K records/day) to mimic ad impressions, clicks, and conversions.
PySpark ETL (Databricks)
Sessionization of user activity
Last-click attribution logic
Revenue calculation and aggregation
Scalable distributed processing
Data Storage (Amazon S3)
Stored processed data in partitioned Parquet format
Optimized for cost-efficient querying
Analytics Layer (Amazon Athena)
Serverless SQL queries on S3
Partition pruning for performance optimization
**Workflow Orchestration (Apache Airflow)**
Automated pipeline using Dockerized Airflow
Triggered Databricks jobs via REST API
Performed Athena table refresh and validation
# Ad-Tech Clickstream Attribution V

## Overview

This project simulates a real-world **ad-tech data engineering pipeline** that processes clickstream data to perform **last-click attribution** and revenue analysis. The pipeline is designed to mirror production-grade architectures used in digital advertising platforms.

---

## Architecture

The pipeline follows a modern cloud-based data engineering workflow:

Data Generation → Databricks (PySpark ETL) → Amazon S3 (Parquet) → Amazon Athena → Airflow Orchestration

---

## Key Features

* **Clickstream Data Simulation**
  Generated realistic user interaction data (~500K records/day) to mimic ad impressions, clicks, and conversions.

* **PySpark ETL (Databricks)**

  * Sessionization of user activity
  * Last-click attribution logic
  * Revenue calculation and aggregation
  * Scalable distributed processing

* **Data Storage (Amazon S3)**

  * Stored processed data in **partitioned Parquet format**
  * Optimized for cost-efficient querying

* **Analytics Layer (Amazon Athena)**

  * Serverless SQL queries on S3
  * Partition pruning for performance optimization

* **Workflow Orchestration (Apache Airflow)**

  * Automated pipeline using Dockerized Airflow
  * Triggered Databricks jobs via REST API
  * Performed Athena table refresh and validation

---

## Tech Stack

* **Processing:** PySpark, Databricks
* **Storage:** Amazon S3 (Parquet)
* **Query Engine:** Amazon Athena
* **Orchestration:** Apache Airflow (Docker)
* **Languages:** Python, SQL
* **Integration:** REST APIs


---

Processing: PySpark, Databricks
Storage: Amazon S3 (Parquet)
Query Engine: Amazon Athena
Orchestration: Apache Airflow (Docker)
Languages: Python, SQL
Integration: REST APIs..

