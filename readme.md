# NYC Taxi Trip Analytics using Apache Spark

## Overview

This project analyzes the **NYC Yellow Taxi Trip Records (January 2024)** dataset using **Apache Spark (PySpark)**. It demonstrates big data processing techniques, including data loading, exploratory data analysis (EDA), data cleaning, Spark DataFrame transformations, Spark SQL, window functions, and performance optimization.

## Objectives

* Load and process a large-scale dataset using Apache Spark.
* Perform exploratory data analysis (EDA).
* Clean and preprocess the dataset.
* Apply Spark DataFrame transformations.
* Execute analytical queries using Spark SQL.
* Demonstrate Spark Window Functions.
* Improve performance using caching and repartitioning.
* Analyze Spark execution through the Spark Web UI.

## Dataset

* **Dataset:** NYC Yellow Taxi Trip Records (January 2024)
* **Format:** Parquet
* **Source:** https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Technologies Used

* Python 3.x
* Apache Spark (PySpark)
* Jupyter Notebook
* Java (OpenJDK)
* Windows

## Project Structure

```text
231980027_AyeshaArshad_SparkAssignment2/
│
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
├── output/
│   ├── query1.csv
│   ├── query2.csv
│   └── query3.csv
└── data/
    └── yellow_tripdata_2024-01.parquet
```

## Features

* Dataset loading and schema inspection
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Spark DataFrame transformations
* Spark SQL queries
* Window Functions (`row_number()`, `rank()`, `dense_rank()`)
* Performance optimization using `cache()`, `repartition()`, and `explain()`
* Spark UI analysis

## How to Run

1. Install Python, Java, and Apache Spark.
2. Clone this repository.
3. Place the dataset in the `data/` folder.
4. Open `Spark_Assignment.ipynb` using Jupyter Notebook.
5. Update the dataset path if required.
6. Run all notebook cells sequentially.

## Learning Outcomes

This project provides practical experience with:

* Distributed data processing using Apache Spark
* Spark SQL and DataFrame APIs
* Big data analytics workflows
* Performance optimization techniques
* Spark Web UI monitoring and analysis

## Author

**Ayesha Arshad**

BS Data Science

## License

This project is intended for educational purposes only.
