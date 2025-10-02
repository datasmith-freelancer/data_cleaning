# Data Cleaning Practice Notebook

Hello Recruiter,

This Jupyter Notebook demonstrates my hands-on skills in data cleaning using pandas, based on a real-world café sales dataset. I created this notebook to practice and showcase my ability to handle messy data and prepare it for further analysis or machine learning tasks.

## What I Did

- **Robust Data Import:**
	- I implemented error handling when loading the `dirty_cafe_sales.csv` file, covering cases like missing files, empty files, and parsing errors.

- **Data Exploration:**
	- I displayed the first 5 rows and 100 random rows to get a feel for the dataset.
	- I counted missing values per column and listed all rows with at least one missing value.

- **Data Cleaning:**
	- I converted non-numeric values in `Quantity`, `Price Per Unit`, and `Total Spent` to numeric, coercing invalid entries to NaN.
	- I replaced missing values in these columns with 0.
	- For categorical columns like `Item`, `Payment Method`, `Location`, and `Transaction Date`, I replaced errors and missing values with meaningful placeholders (e.g., "Unknown Item").
	- I performed plausibility checks to ensure that `Quantity * Price Per Unit` matches `Total Spent`.

- **Saving Results:**
	- I saved the cleaned data as `clean_cafe_sales.csv`.
	- Rows that failed the plausibility check were saved separately as `transactions_invalid.csv`.

- **Reporting:**
	- I generated a cleaning report showing how many values were fixed or filled in each column.

## Why This Matters

This notebook demonstrates my ability to systematically identify and fix common data quality issues using pandas. I am comfortable with error handling, data type conversion, missing value imputation, and basic data validation. My workflow is robust and reproducible, making it easy to adapt to new datasets and requirements.

## Requirements
- Python 3.x
- pandas
- Jupyter Notebook or VS Code with Jupyter support

## How to Use
1. Open the notebook and run the cells step by step.
2. Follow the outputs and comments to understand each cleaning step.
3. After completion, you will find the cleaned data in `clean_cafe_sales.csv` and invalid rows in `transactions_invalid.csv`.

Thank you for reviewing my work!