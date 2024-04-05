# Fraud Data Pipeline with Airflow & Motherduck

This project is based on the knowledge acquired from the course **"The Complete Hands-on Introduction to Airbyte" by Marc Lamberti**. It's a great resource - You've probably taken a course by Marc before and know what I'm talking about - for anyone looking to understand how to build and maintaining a data pipeline with Airbyte and Airflow, among other technologies. 

I highly recommend purchasing this course to acquire the foundational knowledge necessary for creating and sustaining a project like this.

[The Complete Hands-on Introduction to Airbyte by Marc Lamberti](https://www.udemy.com/share/10aFV63@tA0Pxk1F1wboCxLh-osqchhF7obA8Cv1ITRS8dQmwLLC696845z9SSAIJ3LJvtyR/)

## Overview

This project demonstrates a comprehensive data engineering pipeline designed to detect and analyze fraudulent activities within users transactions dataset. Utilizing a blend of Python, SQL, Airbyte, Apache Airflow, Motherduck (DuckDB), and DBT Core, it exemplifies how to architect and implement a scalable and efficient ETL (Extract, Transform, Load) pipeline. The project is crafted with educational purposes in mind, aiming to guide newcomers through the intricacies of data engineering while also serving as a robust portfolio piece for more seasoned practitioners.

## Objectives

* **Data Collection**: Leverage Airbyte for connecting to various data sources and extracting raw data.
* **Workflow Orchestration**: Utilize Apache Airflow for scheduling, automating, and managing the pipeline's tasks efficiently.
* **Data Processing & Analysis**: Motherduck (DuckDB) for data processing and analysis, showcasing its capabilities in handling big data with ease.
* **Transformation**: Use DBT Core for transforming the raw data into a structured format, enabling effective data analysis and reporting.
* **Fraud Detection**: Implement algorithms and logic to identify potential fraudulent activities within the dataset.