# Real-time Data Streaming Pipeline with Apache Airflow, Kafka, Spark, Docker and Cassandra.

Description
This project implements a robust real-time data streaming pipeline using modern Apache open-source technologies: Apache Airflow, Kafka, Spark, Cassandra, all neatly containerized with Docker for simplified deployment and scalability. 
The pipeline facilitates seamless ingestion, processing, and storage of streaming data, orchestrated by Apache Airflow for efficient workflow management.

Project Architecture:
![Data engineering architecture](https://github.com/Heet09/RealTime-Data-Streaming-Using-Apache-Kafka/assets/64312275/ccd294fd-2fe7-4c06-947c-1dd679856281)



Key Features
  Apache Airflow: Orchestrates and schedules tasks, providing a centralized platform for workflow management.
  
  Apache Kafka: Acts as the messaging backbone for data ingestion, ensuring fault-tolerant and scalable message brokering.
  
  Apache Spark: Processes streaming data in real-time with its powerful in-memory computing capabilities, enabling complex data transformations and analytics.
  
  Apache Cassandra: Serves as the database for storing processed data, offering high availability and horizontal scalability.
  
  Docker: Containerizes all components (Airflow, Kafka, Spark, Cassandra) using Docker Compose for easy deployment across environments.

Project Structure
The project leverages Docker and Docker Compose for managing the containerized infrastructure. It includes the following components:

  zookeeper: Manages coordination services required by Kafka.
  
  broker: Hosts Kafka instances responsible for managing and storing streams of records.
  
  schema-registry: Manages schema metadata for Kafka, ensuring data compatibility and validation.
  
  control-center: Provides monitoring and management capabilities for Kafka clusters.
  
  webserver: Apache Airflow instance for designing, scheduling, and monitoring workflows.
  
  scheduler: Apache Airflow scheduler for managing task execution according to defined schedules.
  
  postgres: PostgreSQL database used by Airflow for metadata storage, ensuring reliability and data integrity.

Resources:
    Docker Compose Documentation: https://docs.docker.com/compose/
    Apache Kafka Official Site: https://kafka.apache.org/
    Apache Spark Official Site: https://spark.apache.org/
    Apache Airflow Official Site: https://airflow.apache.org/
    Cassandra: https://cassandra.apache.org/
    Confluent Docs: https://docs.confluent.io/home/overview.html
