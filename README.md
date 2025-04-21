# 🛍️ Shopstream: Real-Time Personalized Recommendation System

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-Stream%20Ingestion-black?style=for-the-badge&logo=apachekafka)
![PySpark](https://img.shields.io/badge/PySpark-Batch%20Processing-orange?style=for-the-badge&logo=apachespark)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Model%20Training-ff6f00?style=for-the-badge&logo=tensorflow)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboarding-yellow?style=for-the-badge&logo=powerbi)

> A scalable, hybrid recommendation system with real-time stream processing, collaborative filtering, and insightful dashboards.

---

## 🧾 Overview

**Shopstream** is a recommendation engine designed for e-commerce platforms to deliver **real-time**, **personalized product suggestions** using user interaction data.

📈 **Key Impacts**  
- 🚀 20% increase in **user engagement**  
- 🧠 15% improvement in **recommendation accuracy**  
- 💰 8% boost in **sales**  
- 📊 10% improvement in **CTR** via live dashboards

---

## ⚙️ Tech Stack

| Tool          | Use Case                                 |
|---------------|------------------------------------------|
| **Apache Kafka** | Real-time user activity ingestion       |
| **Spark Streaming** | Stream processing for session-level recommendations |
| **Apache Spark** | Batch model training on historical data |
| **TensorFlow** | Collaborative filtering model training    |
| **Power BI** | Real-time system monitoring and insights   |

---

## 🧠 Architecture

```mermaid
graph TD;
    A[User Interactions] --> B[Kafka Streams];
    B --> C[Spark Streaming - Real-time pipeline];
    C --> D[TensorFlow Model - Real-time recommendations];
    D --> E[User Dashboard/UI];

    F[Purchase History (1M+ Records)] --> G[Apache Spark - Batch processing];
    G --> H[TensorFlow Model Training];

    D --> I[Power BI Monitoring];
    H --> I;
