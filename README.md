# How to Run the Pipeline

## 1. Setup Environment

Ensure Python 3.8+ and Jupyter are installed.

Install required packages: **requirements.txt**

## 2. Run Notebook 1: create_categories.ipynb

This script:

- Loads raw datasets from.
- Creates medication categories.
- Saves cleaned and categorized data to db.

Run Notebook 2: pipeline.ipynb

This script:

- Loads the processed data from db.
- Performs ETL process.
- data analysis.
