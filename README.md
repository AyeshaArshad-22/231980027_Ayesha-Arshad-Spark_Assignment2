# 🚖 NYC Taxi Trip Analytics using Apache Spark

A comprehensive **Big Data Analytics** project built with **Apache Spark (PySpark)** to analyze the **NYC Yellow Taxi Trip Records (January 2024)** dataset. This project demonstrates scalable data processing, exploratory data analysis, Spark SQL, DataFrame transformations, window functions, and performance optimization techniques.

---

## 📌 Project Overview

This project showcases how Apache Spark can efficiently process and analyze millions of taxi trip records. It covers the complete data analytics pipeline—from loading and cleaning the dataset to executing SQL queries, applying transformations, optimizing performance, and analyzing Spark execution using the Spark Web UI.

---

## 🎯 Objectives

* Load a large-scale dataset using Apache Spark.
* Perform Exploratory Data Analysis (EDA).
* Clean and preprocess real-world data.
* Apply Spark DataFrame transformations.
* Execute analytical queries using Spark SQL.
* Demonstrate Spark Window Functions.
* Optimize Spark performance using caching and repartitioning.
* Analyze execution through the Spark Web UI.

---

## 📂 Dataset

**Dataset:** NYC Yellow Taxi Trip Records (January 2024)

**Format:** Parquet

**Source:** https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

> **Note:** The dataset is not included in this repository because it exceeds GitHub's file size limit. Download `yellow_tripdata_2024-01.parquet` from the official NYC Taxi & Limousine Commission website and place it in your local project directory before running the notebook.

---

## 🛠 Technologies Used

* Apache Spark (PySpark)
* Python 3.x
* Jupyter Notebook
* Java (OpenJDK)
* Windows
* Spark SQL

---

## ✨ Project Features

* ✅ Dataset loading and schema inspection
* ✅ Exploratory Data Analysis (EDA)
* ✅ Data cleaning and preprocessing
* ✅ Spark DataFrame Transformations

  * Filter
  * Select
  * withColumn
  * orderBy
  * Drop
  * Distinct
  * GroupBy
  * Join
  * Alias
  * Repartition
* ✅ Spark SQL Queries
* ✅ Window Functions

  * `row_number()`
  * `rank()`
  * `dense_rank()`
* ✅ Performance Optimization

  * `cache()`
  * `repartition()`
  * `explain()`
* ✅ Spark UI Analysis

---

## 📁 Repository Structure

```text
.
├── Spark_Assignment.ipynb
├── 231980027_AyeshaArshad_SparkAssignment.pdf
├── README.md
├── execution_log.txt
├── screenshots/
│   ├── schema.png
│   ├── jobs.png
│   ├── stages.png
│   ├── storage.png
│   └── executors.png
└── output/
    ├── query1.csv
    ├── query2.csv
    └── query3.csv
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AyeshaArshad-22/231980027_Ayesha-Arshad-Spark_Assignment2.git
```

### 2. Navigate to the Project

```bash
cd 231980027_Ayesha-Arshad-Spark_Assignment2
```

### 3. Install Requirements

Make sure the following are installed:

* Python 3.x
* Java (JDK/OpenJDK)
* Apache Spark
* Jupyter Notebook

### 4. Download the Dataset

Download the January 2024 NYC Yellow Taxi dataset from:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Place the downloaded `yellow_tripdata_2024-01.parquet` file in your local project directory.

### 5. Run the Notebook

Launch Jupyter Notebook and open:

```text
Spark_Assignment.ipynb
```

Run all cells from top to bottom.

---

## 📊 Learning Outcomes

This project demonstrates practical experience with:

* Distributed data processing using Apache Spark
* Big Data Analytics workflows
* Spark SQL
* DataFrame APIs
* Window Functions
* Performance Optimization
* Spark Web UI Monitoring

---

## 📄 Project Report

A detailed report describing the implementation, methodology, SQL queries, Spark transformations, performance comparison, Spark UI analysis, and results is included in this repository.

---

## 👩‍💻 Author

**Ayesha Arshad**

BS Data Science

GitHub: https://github.com/AyeshaArshad-22

---

## 📜 License

This repository is shared for educational and learning purposes only.
