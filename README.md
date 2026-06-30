# Data Cleaning and Preprocessing

Cleaned a messy 12,575-row retail sales dataset using Python (Pandas) recovered missing values via the Price × Quantity = Total relationship, removed duplicates, standardized formatting, and fixed data types to make it analysis-ready.

## Dataset
**Retail Store Sales: Dirty for Data Cleaning** (Kaggle)
https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning

## Tools Used
Python (Pandas, NumPy) in Jupyter Notebook

## Steps Performed
- Identified and handled missing values — used the relationship `Total Spent = Price × Quantity` to recover missing numbers accurately, and applied sensible defaults (`'Unknown'`, `False`) where no such relationship existed
- Removed duplicate rows to prevent double-counting
- Standardized text formatting across category, payment method, and location columns
- Converted dates into a consistent format
- Cleaned column headers for uniformity
- Fixed data types so numeric and boolean columns work correctly in calculations
- Checked for outliers and kept genuine high-value transactions rather than deleting valid data

## Conclusion
Data cleaning is about making informed, explainable decisions not just filling gaps. Checking for mathematical relationships between columns (like Price × Quantity = Total) before defaulting to averages produces far more accurate results. The final dataset is now clean and ready for analysis, visualization, or modelling.
