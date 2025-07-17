# 📊 PhonePe Pulse Data Engineering Project

This project is built around the open-source [PhonePe Pulse](https://github.com/PhonePe/pulse) dataset, which provides financial transaction data across India — from large cities to remote villages. The primary goal of this project is to create a scalable, fault-tolerant data processing pipeline using **Apache Spark** on the **Databricks** platform.

---

## 🚀 Project Overview

This project demonstrates how to:

- Ingest large, nested JSON datasets
- Flatten and normalize semi-structured data using custom UDFs
- Handle schema evolution in JSON data
- Implement checkpointing for fault tolerance and recovery
- Leverage Databricks’ free-tier platform for data engineering workflows

---

## 🔧 Technologies Used

- **Apache Spark (PySpark)**
- **Databricks (Community Edition)**
- **Python**
- **Delta Lake**
- **PhonePe Pulse Dataset** (JSON format)

---

## 📁 Dataset Details

The dataset includes:

- **Aggregated Data:** Regional and temporal transaction summaries
- **Map Data:** Geospatial data representing regions and volumes
- **Top Data:** Top transactions categorized by users, merchants, and amounts

---

## 📂 Project Structure

```bash
phonepe-pulse-pipeline/
│
├── notebooks/
│   ├── User State Reading.dbc       # Load and read JSON files
│   ├── Users Data Reading.dbc       # Custom UDFs to flatten nested data
│
├── data/                             # [PhonePe Pulse](https://github.com/PhonePe/pulse)
│
├── README.md                         # Project documentation
│
└──
