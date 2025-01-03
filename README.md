# Data-Engineering-Project---YouTube-Analysis(AWS/.Json/.CSV) By Edwina Singh

# Overview
This project focuses on securely managing, streamlining, and performing analysis on structured and semi-structured YouTube video data, based on video categories and trending metrics. The goal is to extract valuable insights from this data to support decision-making and trend analysis.

# Project Goals
 1. Data Ingestion: Develop a mechanism to ingest YouTube video data from various sources to s3 bucket.
 2. ETL System: Convert raw data into a clean, structured format suitable for analysis through a robust ETL pipeline.
 3. Data Lake: Centralize the storage of data from multiple sources into a data lake for efficient querying and management.
 4. Scalability: Ensure that the system can scale as the volume of data grows.
 5. Cloud: Leverage AWS cloud services for processing large volumes of data, overcoming the limitations of local infrastructure.
 6. Reporting: Build an interactive dashboard to provide insights and answers to key questions based on the YouTube data.

# Services to be Used
 1. AWS IAM: Identity and Access Management service for securely controlling access to AWS resources and services.
 2. Amazon S3: Object storage service offering high scalability, data availability, security, and performance for storing raw and processed data.
 3. AWS Glue: Serverless data integration service designed to discover, prepare, and combine data for analytics, machine learning, and application development.
 4. AWS Athena: Interactive query service that enables direct querying of data stored in Amazon S3, without needing to load it into a database.
 5. AWS Lambda: Serverless computing service that allows execution of code without the need to manage infrastructure, suitable for processing data transformations.
 6. Amazon QuickSight: Scalable, serverless business intelligence service for creating visual dashboards and generating insights from data.

# Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

 # Architecture Diagram

![architecture](https://github.com/user-attachments/assets/713749bc-5603-4240-8e2a-04df2df4aeea)

