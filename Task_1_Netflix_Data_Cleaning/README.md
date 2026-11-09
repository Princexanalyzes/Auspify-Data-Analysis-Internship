# Task 1: Netflix Data Cleaning & Preparation

## Project Overview
This project focuses on the initial data quality inspection, cleaning, and preprocessing of the Netflix content catalog (8,790 records and 10 features). The primary objective is to resolve disguised missing values, standardize datatypes, and deliver a sanitized dataset for downstream business analytics.

## Key Operations Performed
1. **Data Ingestion & Inspection:** Loaded raw records using Pandas and audited baseline attributes (`df.shape`, `df.info()`).
2. **Disguised Missing Value Detection:** Identified non-standard placeholders (`'Not Given'`) across categorical features (2,588 records in `director`, 287 records in `country`).
3. **Imputation & Standardization:** 
   - Replaced `'Not Given'` entries with `'Unknown'` to preserve row context for EDA.
   - Stripped unwanted whitespaces across textual fields.
   - Converted `date_added` into standard `datetime64[ns]` format.
4. **Export:** Exported the verified clean dataframe as `netflix_cleaned.csv` into the `output/` directory.

## Verified Summary
- **Total Records:** 8,790
- **Total Columns:** 10
- **Null Values:** 0
- **Deliverable:** `output/netflix_cleaned.csv`