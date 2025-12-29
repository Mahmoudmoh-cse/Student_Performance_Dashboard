# DEPI_final_Project
Student Performance Dashboard &amp; Ticketing System 
The Student Performance Dashboard & Ticketing System is a comprehensive data-driven web application built using Streamlit.
It provides role-based access for students and administrators, integrates data processing pipelines, AI-powered sentiment analysis, and automated email notifications using Apache Airflow and DBT.

The system enables students to track academic performance and submit feedback, while administrators manage student data and monitor insights efficiently.
# System Architecture
Components

Frontend: Streamlit Web Application

Data Processing: Pandas

Visualization: Matplotlib & NumPy

Sentiment Analysis: Hugging Face Transformers

Workflow Automation: Apache Airflow

Data Transformation: DBT

Database: CSV files & SQL Database
# Data Flow Summary

Admin uploads data

Data cleaning & processing

Export to students_cleaned.csv

Copy to DBT seeds

dbt seed → Load data

dbt run → Transform data

Students view scores

Students submit feedback

Sentiment analysis

Airflow DAG triggered

Email sent based on sentiment
# Technical Stack

Python 3.x

Streamlit

Pandas

Matplotlib / NumPy

PyTorch & Transformers

Apache Airflow

DBT

SQL Database
