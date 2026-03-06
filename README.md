# EHR Data Engineering Pipeline

## Overview

This project implements a **data engineering pipeline for Electronic Health Record (EHR) data**.
The system processes healthcare datasets, cleans and transforms the data, and stores it in a structured SQL database for analysis and visualization.

The project was developed as part of a **Data Engineering course project**.

## Features

* Data cleaning and preprocessing for multiple healthcare datasets
* Structured transformation of EHR data
* SQL database creation and storage
* Data integration from multiple sources
* Simple web interface for data exploration

## Technologies

* Python
* SQL
* Data Cleaning
* ETL Pipelines
* Healthcare Data Processing

## Project Structure

ehr-data-engineering-pipeline/
│
├── patients_cleaning.py
├── diagnoses_cleaning.py
├── medications_cleaning.py
├── observations_cleaning.py
├── procedures_cleaning.py
├── ehr_journeys.py
│
├── finaldb.sql
│
├── webpage.py
│
├── Project_Report.pdf
├── PosterDataEng.pdf
└── README.md

## How to Run

Clone the repository:

git clone https://github.com/yourusername/ehr-data-engineering-pipeline.git

Install dependencies:

pip install pandas sqlite3 flask

Run the data processing scripts:

python patients_cleaning.py
python diagnoses_cleaning.py
python medications_cleaning.py
python observations_cleaning.py
python procedures_cleaning.py

Create the database:

Run the SQL script in SQLite:

finaldb.sql

Run the web interface:

python webpage.py

## Learning Goals

* Designing a healthcare data pipeline
* Data cleaning and preprocessing
* ETL pipeline design
* Database integration
* Handling real-world healthcare datasets
