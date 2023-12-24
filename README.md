

# Realtime Data Streaming 

## Introduction
Welcome to our comprehensive guide on building an end-to-end data engineering pipeline. This project is designed to take you through all stages of data engineering, from ingestion and processing to storage. Utilizing a robust and modern tech stack, this tutorial is perfect for those looking to gain hands-on experience in the field of data engineering. We leverage technologies like Apache Airflow, Kafka, Zookeeper, Spark, and Cassandra, all containerized using Docker for simplified deployment and scalability.

## System Architecture
The architecture of this project integrates various components to create a seamless data engineering workflow:

- **Data Source**: Utilizes the randomuser.me API to generate and supply random user data for our pipeline.
- **Apache Airflow**: Orchestrates the workflow, managing the data pipeline and storing initial data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Handle real-time data streaming from PostgreSQL to our processing engine.
- **Control Center and Schema Registry**: Assist in monitoring Kafka streams and managing their schemas.
- **Apache Spark**: Processes the streaming data using a cluster setup with master and worker nodes.
- **Cassandra**: Serves as the final storage solution where the processed data is stored.

## What You'll Learn
This project will guide you through:

- Setting up a data pipeline using Apache Airflow.
- Implementing real-time data streaming with Apache Kafka.
- Employing Apache Zookeeper for distributed synchronization.
- Data processing techniques leveraging Apache Spark.
- Utilizing Cassandra and PostgreSQL for data storage.
- Containerizing your data engineering setup with Docker for efficiency and scalability.

## Technologies
This project is built using the following technologies:
- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started
To begin with the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/airscholar/e2e-data-engineering.git
   ```
2. Navigate to the project directory:
   ```
   cd e2e-data-engineering
   ```
3. Run Docker Compose to start the services:
   ```
   docker-compose up
   ```

