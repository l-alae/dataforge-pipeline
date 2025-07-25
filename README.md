# 📊 DataForge – End-to-End Real-Time Data Pipeline

A fully containerized, distributed data engineering system designed to simulate real-time ingestion, processing, and storage of data using industry-standard tools such as Apache Kafka, Airflow, Spark, Cassandra, and Docker.

---

## 📂 Table of Contents

- [🧠 Overview](#overview)
- [🧱 System Architecture](#system-architecture)
- [🧪 Tech Stack](#tech-stack)
- [📈 Features](#features)
- [⚙️ How It Works](#how-it-works)
- [🛠 Future Improvements](#future-improvements)
- [👥 Contributions](#contributions)
- [📬 Contact](#contact)

---

## 🧠 Overview

**DataForge** is a real-time data pipeline prototype for educational and demonstrational use. It covers ingestion, streaming, processing, and distributed storage — ideal for learning core concepts in data engineering, containerized workflows, and system orchestration.

---

## System Architecture

![System Architecture](https://github.com/airscholar/e2e-data-engineering/blob/main/Data%20engineering%20architecture.png)

## 🧪 Tech Stack

| Tool              | Purpose                                |
|-------------------|----------------------------------------|
| Apache Airflow    | Workflow orchestration                 |
| Apache Kafka      | Real-time event streaming              |
| Apache Zookeeper  | Kafka coordination                     |
| Apache Spark      | Distributed stream processing          |
| Cassandra         | Final scalable NoSQL storage           |
| PostgreSQL        | Staging database for ingested data     |
| Docker            | Full environment containerization      |
| Python            | Scripts for ingestion, transformation  |

---

## 📈 Features

- ✅ Automated data ingestion from external API using Airflow
- ✅ Streaming architecture with Kafka and Zookeeper
- ✅ Scalable stream processing via Apache Spark
- ✅ Final data storage in Cassandra
- ✅ Dockerized deployment for portability

---

## ⚙️ How It Works

1. **Airflow** fetches random user data from `randomuser.me` API and stores it in PostgreSQL.
2. **Kafka** streams the new data entries in real time.
3. **Spark** (master + workers) processes the data and applies transformations.
4. **Cassandra** stores the processed results for querying and analytics.

---

## 🛠 Future Improvements

- [ ] Add schema validation via Confluent Schema Registry  
- [ ] Integrate Prometheus & Grafana for monitoring  
- [ ] Add authentication and access control  
- [ ] Build a REST API to query processed data from Cassandra

---


## 📬 Contact

**Alae**  
[GitHub Profile Link:(https://github.com/l-alae)]  
[Email: laita.alae@gmail.com]


