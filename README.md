# Real Time City Data Project

**End-to-end Big Data engineering project inspired by Yusuf Ganiyu’s tutorial video. Implemented using Python, Apache Spark, Kafka, and AWS, this project simulates and processes real-time urban data streams.**

---

## Project Overview
This project simulates a **smart city data pipeline** that collects, processes, and analyzes real-time urban data streams. It demonstrates:

- **Data ingestion:** Simulated city IoT sensor data streamed via Kafka topics (vehicle telemetry, GPS, traffic, weather, emergency incidents). 
- **Data processing:** Real-time ETL and preprocessing using Apache Spark Structured Streaming. 
- **Storage** Processed data is written as Parquet files to AWS S3 for downstream analytics.  
- **Insights:** Data is structured to enable further analysis or visualization (dashboards can be added in future).  

The project showcases how to build scalable, cloud-native data pipelines and handle streaming data for smart city applications.

---

## Architecture
Simulated IoT Sensors → Kafka → Spark Structured Streaming → AWS S3 (Parquet) → Downstream Analytics
<img width="800" height="306" alt="image" src="https://github.com/user-attachments/assets/19151f75-40fc-4171-80e2-6e6922db33cd" />

**Key components:**

- **Kafka** – Real-time data ingestion and topic-based stream management.  
- **Spark Streaming** – Process, validate, and transform streaming data in real-time.  
- **AWS S3** – Store structured Parquet datasets for fault-tolerant, scalable storage.  
- **Python** – ETL scripts, data simulation, and streaming utilities.
- **Docker:** – Containerized services for Kafka and Spark for easier deployment.

---

**Key Features & Learnings**

- Real-time streaming data ingestion and processing.
- Schema validation and event-time handling using watermarks.
- Cloud storage and analytics with AWS S3.
- Modular, reusable streaming pipelines using Spark and Python.
- Hands-on experience with Kafka, Spark Structured Streaming, and Python for big data engineering.
- Understanding of smart city IoT data flows and event-driven architecture.


**Future Improvements**

- Build real-time analytics dashboards to visualize city metrics.
- Implement anomaly detection for city events and traffic conditions.
- Automate deployment with Docker Compose or Kubernetes.
- Add CI/CD pipelines for automated testing of ETL/streaming jobs.
- Optionally integrate downstream analytics storage like Redshift for advanced BI.

  

**Acknowledgements**

Inspired by Yusuf Ganiyu’s Smart City Big Data tutorial video
