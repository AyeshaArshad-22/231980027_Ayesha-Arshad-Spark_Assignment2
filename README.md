# NYC Taxi Trip Analytics using Apache Spark

## Overview

This project demonstrates large-scale data analytics using **Apache Spark (PySpark)** on the **NYC Yellow Taxi January 2024** dataset. The project covers the complete data analysis workflow, including data loading, exploratory data analysis (EDA), data cleaning, Spark DataFrame transformations, Spark SQL queries, window functions, and performance optimization techniques.

## Dataset

* **Dataset:** NYC Yellow Taxi Trip Records (January 2024)
* **Format:** Parquet
* **Source:** [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

File:
yellow_tripdata_2024-01.parquet)
## Technologies Used

* Python 3.x
* Apache Spark (PySpark)
* Jupyter Notebook
* Java (OpenJDK)
* Windows

## Project Features

* Load and explore the dataset
* Perform Exploratory Data Analysis (EDA)
* Clean and preprocess data
* Apply Spark DataFrame transformations
* Execute Spark SQL queries
* Use Window Functions

  * `row_number()`
  * `rank()`
  * `dense_rank()`
* Optimize performance using:

  * `cache()`
  * `repartition()`
  * `explain()`
* Analyze Spark UI (Jobs, Stages, Storage, Executors)

## Repository Structure

```
.
├── Spark_Assignment.ipynb
├── report.pdf
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

## How to Run

1. Install Python and Java.
2. Install Apache Spark.
3. Clone this repository:

   ```bash
   git clone https://github.com/AyeshaArshad-22/231980027_Ayesha-Arshad-Spark_Assignment2
   ```
4. Open `Spark_Assignment.ipynb` in Jupyter Notebook.
5. Update the dataset path if necessary.
6. Run all notebook cells sequentially.

## Learning Outcomes

* Working with large datasets using Apache Spark
* Performing distributed data processing
* Using Spark SQL for analytical queries
* Applying DataFrame transformations
* Understanding Window Functions
* Improving Spark performance with caching and repartitioning
* Monitoring execution using the Spark Web UI

## License

This project is shared for educational purposes only.
