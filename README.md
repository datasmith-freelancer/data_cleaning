# Data Cleaning Project – Café Sales Dataset  

Hi! 👋  

I built this project to demonstrate my **data cleaning skills** using Python and Pandas.  
The dataset I worked with (`dirty_cafe_sales.csv`) contained a variety of **realistic data quality issues**: missing values, inconsistent formats, wrong labels, and even logically incorrect records.  

---

## What I Did  

- **Data Inspection & Exploration**  
  - Loaded the dataset safely with proper error handling.  
  - Explored the data with `.head()`, `.info()`, `.describe()`, and random sampling to understand its structure and problems.  
  - Counted missing values and identified incomplete rows.  

- **Cleaning & Transformation**  
  - Converted numeric columns (`Quantity`, `Price Per Unit`, `Total Spent`) to the correct type and handled invalid values.  
  - Recalculated missing numeric fields when possible (e.g., computed `Price Per Unit` from `Total Spent / Quantity`).  
  - Cleaned categorical columns:  
    - Replaced invalid entries like `"ERROR"` or `"UNKNOWN"` with sensible defaults.  
    - Reconstructed product names (`Salad`, `Coffee`, `Tea`) based on price clues.  
    - Standardized payment methods and locations.  
  - Fixed and converted transaction dates, ensuring chronological order.  

- **Validation & Reporting**  
  - Added a plausibility check: verified if `Quantity × Price Per Unit = Total Spent`.  
  - Flagged and exported invalid transactions separately.  
  - Generated a cleaning report summarizing all fixes.  

- **Output Files**  
  - `clean_cafe_sales.csv` → fully cleaned dataset  
  - `transactions_invalid.csv` → records that failed validation  

---

## Why This Matters  

This project shows that I can:  

- Handle **dirty, real-world data** and make it usable.  
- Apply **systematic cleaning strategies** instead of quick fixes.  
- Ensure **data consistency, correctness, and reliability** before analysis.  
- Communicate results clearly (both in code and reporting).  

As a future **Data Analyst / Data Engineer**, I know that preparing clean, trustworthy data is the foundation for every analysis or machine learning project.  



✅ With this project, I want to demonstrate to recruiters that I can turn messy data into structured, reliable information — a critical step for any successful data-driven project.  
