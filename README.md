# Student Performance Dashboard & Ticketing System

A data-driven web application built with Streamlit for students and administrators.

## Features

- Role-based access for students and administrators
- Academic performance tracking
- Student feedback submission
- AI-powered sentiment analysis
- Automated email notifications
- Data processing and transformation workflows

## Architecture

- **Frontend:** Streamlit
- **Data processing:** Pandas
- **Visualization:** Matplotlib, NumPy
- **Sentiment analysis:** Hugging Face Transformers / PyTorch
- **Workflow automation:** Apache Airflow
- **Data transformation:** dbt
- **Storage:** CSV files and SQL database

## Data Flow

1. Administrator uploads student data.
2. Data is cleaned and processed.
3. Cleaned data is exported and loaded into dbt seeds.
4. dbt transforms the data.
5. Students view their scores and submit feedback.
6. Feedback is analyzed for sentiment.
7. An Airflow DAG triggers the relevant email workflow.

## Tech Stack

Python, Streamlit, Pandas, NumPy, Matplotlib, PyTorch, Transformers, Apache Airflow, dbt, SQL.
