# Data Engineering Zoomcamp

This repo contains homework and notes for the [Data Engineering Zoomcamp - 2024 cohort](https://github.com/DataTalksClub/data-engineering-zoomcamp) by [Datatalks.Club](https://datatalks.club/).

***

### [Module 1: Introduction & Prerequisites](1_basics_n_setup)

* Course overview
* Introduction to GCP
* Docker and docker-compose
* Running Postgres locally with Docker
* Setting up infrastructure on GCP with Terraform
* Preparing the environment for the course
* Homework


### [Module 2: Workflow Orchestration](2_workflow_orchestration/)

* Data Lake
* Workflow orchestration
* Workflow orchestration with Mage
* Homework


### [Module 3: Data Warehouse](3_data_warehouse)


* Data Warehouse
* BigQuery
* Partitioning and clustering
* BigQuery best practices
* Internals of BigQuery
* Integrating BigQuery with Airflow
* BigQuery Machine Learning


### [Module 4: Analytics engineering](4_analytics_engineering/)

* Basics of analytics engineering
* dbt (data build tool)
* BigQuery and dbt
* Postgres and dbt
* dbt models
* Testing and documenting
* Deployment to the cloud and locally
* Visualizing the data with google data studio and metabase

### [Module 5: Batch processing](5_batch_processing)

* Batch processing
* What is Spark
* Spark Dataframes
* Spark SQL
* Internals: GroupBy and joins

### [Module 6: Streaming](6_stream_processing)

* Introduction to Kafka
* Schemas (avro)
* Kafka Streams
* Kafka Connect and KSQL


### [Module 7: Project](7_project)

Putting everything we learned to practice

* Week 7 and 8: working on your project
* Week 9: reviewing your peers


## Overview

### Architecture diagram
<img src="images/architecture/arch_2.png"/>

### Technologies
* *Google Cloud Platform (GCP)*: Cloud-based auto-scaling platform by Google
  * *Google Cloud Storage (GCS)*: Data Lake
  * *BigQuery*: Data Warehouse
* *Terraform*: Infrastructure-as-Code (IaC)
* *Docker*: Containerization
* *SQL*: Data Analysis & Exploration
* *Mage*: Workflow Orchestration
* *dbt*: Data Transformation
* *Spark*: Distributed Processing
* *Kafka*: Streaming

## Tools

For this course, you'll need to have the following software installed on your computer:

* Docker and Docker-Compose
* Python 3
* Google Cloud SDK
* Terraform

[![My Skills](https://skillicons.dev/icons?i=py,docker,postgres,html,css,gcp,vscode)](https://skillicons.dev)

See [Module 1](week_1_basics_n_setup) for more details about installing these tools