🛒 Building a Retail Data Pipeline
A data engineering project that designs and builds an end-to-end pipeline to ingest, validate, transform, and load retail transaction data into a structured format ready for analysis.

📌 Project Overview
Retail businesses generate large volumes of transactional data daily. Without a reliable pipeline, this data is scattered, inconsistent, and difficult to analyse. This project builds an automated data pipeline that takes raw retail data, cleans and transforms it, and loads it into a structured output — enabling downstream reporting and business insights.

🎯 Objectives

Ingest raw retail transaction data from CSV files
Validate and clean the data (handle nulls, duplicates, type mismatches)
Transform the data into a structured, analysis-ready format
Load the processed data into a target destination
Automate the pipeline using Python and Shell scripting


🛠️ Tools & Technologies
Category Tools
Language Python 3
Data Manipulation pandas
Database PostgreSQL / Snowflake SQL
Version ControlGit
Platform DataCamp DataLab

📁 Project Structure
retail-data-pipeline/
│
├── data/
│   ├── raw/               # Raw input CSV files
│   └── processed/         # Cleaned and transformed output
│
├── notebooks/
│   └── pipeline.ipynb     # Main project notebook
│
│
└── README.md

⚙️ Pipeline Steps
1. Data Ingestion

Load raw retail transaction CSV files using pandas
Inspect schema, data types, and initial row counts

2. Data Validation & Cleaning

Identify and handle missing values
Remove duplicate records
Standardise date formats and column naming conventions
Validate data types (e.g. prices as floats, quantities as integers)

3. Data Transformation

Calculate derived fields (e.g. total order value = quantity × unit price)
Aggregate transactions by product category and time period
Filter out invalid or out-of-range records

4. Data Loading

Write the cleaned, transformed dataset to a structured output (CSV / database table)
Confirm row counts and schema integrity post-load



📊 Key Outputs

Cleaned transaction dataset ready for analysis
Summary aggregations by product category and date
Pipeline execution log confirming successful run


💡 Key Learnings

How to design a modular, reusable ETL pipeline
Data quality checks and validation strategies in pandas
Using Python for pipeline automation
Working with real-world messy retail data

# Clone the repository
git clone (https://github.com/DebbieBash/Building_a_retail_data_pipeline)


# Install dependencies
pip install pandas

# Run the pipeline
bash scripts/pipeline.sh
Or open notebooks/pipeline.ipynb in Jupyter / DataLab and run all cells.

👩🏾‍💻 Author
Deborah Bashorun
Data Engineering Bootcamp — DataCamp, 2026


📎 Project Link
