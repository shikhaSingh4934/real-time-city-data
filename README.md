# Real Time City Data Project

**End-to-end Big Data engineering project inspired by Yusuf Ganiyu’s tutorial video. Implemented using Python, Apache Spark, Kafka, and AWS to process and analyze real-time urban data.**

---

## Project Overview
This project simulates a **smart city data pipeline** that collects, processes, and analyzes real-time urban data streams. It demonstrates:

- **Data ingestion:** Simulated city sensor data streamed via Kafka.  
- **Data processing:** Real-time ETL and transformations using Apache Spark.  
- **Storage & analysis:** Data stored in AWS S3 and/or Redshift for analysis.  
- **Insights:** Example dashboards and reports to monitor city metrics.  

The project showcases how to build scalable, cloud-native data pipelines and handle streaming data for smart city applications.

---

## Architecture
Sensors → Kafka → Spark Streaming → AWS S3 / Redshift → Analysis / Visualization
<img width="1385" height="554" alt="image" src="https://github.com/user-attachments/assets/98d0e05e-7eb9-4584-be43-61c85b226018" />

**Key components:**

- **Kafka** – Real-time data ingestion.  
- **Spark Streaming** – Process and transform streaming data.  
- **AWS S3 / Redshift** – Store structured and unstructured data.  
- **Python** – ETL scripts, data processing, utilities.  

---

**Key Features & Learnings**

- Real-time streaming data ingestion and processing.
- Cloud storage and analytics with AWS services.
- Modular and reusable ETL pipelines.
- Hands-on experience with Kafka, Spark, and Python for big data engineering.
- Understanding of smart city data flows and monitoring.

**Acknowledgements**

Inspired by Yusuf Ganiyu’s Smart City Big Data tutorial video

**Future Improvements**

- Add more real-time analytics dashboards.
- Include anomaly detection for city metrics.
- Containerize the pipeline using Docker for easier deployment.
- Implement CI/CD for automated testing of ETL pipelines.
