# I cleaned a raw, messy retail sales dataset (12,575 rows) and made it analysis-ready by:

# Handling missing values intelligently using the relationship Total Spent = Price × Quantity to recover missing numbers accurately, instead of guessing with averages, and applying sensible defaults ('Unknown', False) where no such relationship existed
# Removing duplicate rows to prevent double-counting
# Standardizing text formatting across category, payment method, and location columns
# Converting dates into a consistent format
# Cleaning column headers for uniformity
# Fixing data types so numeric and boolean columns work correctly in calculations
# Checking for outliers and keeping genuine high-value transactions rather than deleting valid data

# Key takeaway: Data cleaning is about making informed, explainable decisions not just filling gaps. 
# Checking for mathematical relationships between columns (like Price × Quantity = Total) before defaulting to averages produces far more accurate results.
# The final dataset is now clean and ready for analysis, visualization, or modelling.
