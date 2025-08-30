# Airflow + PySpark + DynamoDB ETL Project

This project demonstrates how to build an end-to-end ETL pipeline using **Apache Airflow** for orchestration, **PySpark** for data processing, and **AWS DynamoDB** for storing processed results.  
It also includes sample CSV datasets and scripts for local development.

---

## 📊 Architecture

![Architecture](Airflow-Spark-Dynamo/architecture/Screenshot%20from%202025-08-30%2014-49-04.png)

---

## 📂 Project Structure

Airflow-Spark-Dynamo
│
├── architecture
│ ├── etl_using_airflow_pyspark.pdf # Detailed PDF documentation
│ └── Screenshot...png # Architecture diagram
│
├── dag-glue-workflow.py # Airflow DAG for orchestration
├── data
│ ├── songs.csv
│ ├── streams1.csv
│ ├── streams2.csv
│ └── users.csv
│
├── glue-dynamo.py # Loads data into DynamoDB
├── glue-pyspark.py # PySpark ETL transformations
└── local-docker-development.sh # Local Docker setup script


---

## ⚙️ Tech Stack
- **Apache Airflow** – Orchestration  
- **Apache Spark (PySpark)** – Data Transformation  
- **AWS DynamoDB** – Storage  
- **Docker** – Local Development  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   https://github.com/Goku6382798/Airflow-Spark-Dynamo/tree/main
   cd Airflow-Spark-Dynamo
