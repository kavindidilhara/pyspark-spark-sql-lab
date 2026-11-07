# PySpark & Spark SQL Big Data Lab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kavindidilhara/pyspark-spark-sql-lab/blob/main/EEI6366_Lab.ipynb)

A hands-on notebook exploring big data processing with **PySpark** and **Spark SQL**. The lab runs on a retail dataset with over 150,000 records to practice distributed data manipulation, filtering, and aggregations.

## What's in the Lab
* **Environment Setup:** Configured Java and PySpark locally inside a Google Colab instance.
* **Data Ingestion:** Loaded a 150K-row CSV file, checked rows and columns, inspected the schema, and handled date conversions.
* **PySpark DataFrame API:** Practiced selecting columns, filtering completed orders, and running grouped aggregations by product category.
* **Spark SQL Queries:** Registered a temporary view (`sales_data`) to write standard SQL queries (`SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`) for finding top-performing categories.

## Tech Stack
* Python
* Apache Spark (`pyspark`) / Spark SQL
* Google Colab

## How to Run
Click the **Open In Colab** badge at the top to open the notebook directly in your browser, run the cells step-by-step, and upload the dataset when prompted!
