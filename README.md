# Auspify Data Analysis Internship: Netflix Content & Business Insights

An end-to-end data analytics project conducted during the Auspify Tech Internship. This repository covers data auditing, cleaning, exploratory data analysis (EDA), content trend evaluation, and executive-level business reporting on the global Netflix titles dataset using Python.

---

## 📌 Project Overview

This repository documents the structured workflow of analyzing Netflix's streaming catalog. The objective was to clean uncurated raw streaming metadata, identify regional content distribution patterns, analyze production shifts between TV shows and movies, and formulate data-driven strategic recommendations for platform expansion.

---

## 📂 Repository Structure

```text
├── Task_1_Netflix_Data_Cleaning/
│   ├── data/
│   │   └── Dataset.csv                      # Raw source dataset
│   ├── notebooks/
│   │   └── Task_1_Data_Cleaning.ipynb       # Data profiling, deduplication & imputation
│   ├── output/
│   │   └── netflix_cleaned.csv              # Sanitized analysis-ready dataset
│   └── README.md
│
├── Task_3_Country_Analysis/
│   ├── notebooks/
│   │   └── Task_3_Country_Analysis.ipynb    # Country-level content distribution analysis
│   ├── reports/
│   │   └── country_analysis_summary.txt     # Analytical findings & regional takeaways
│   ├── visualizations/
│   │   ├── top_10_countries.png
│   │   └── movie_tv_split_top5.png
│   └── README.md
│
├── Task_4_TV_vs_Movies_Analysis/
│   ├── notebooks/
│   │   └── Task_4_TV_vs_Movies_Analysis.ipynb # Volume shift, duration metrics & yearly trends
│   ├── reports/
│   │   └── tv_vs_movies_summary.txt
│   ├── visualizations/
│   │   ├── movies_vs_tv_distribution.png
│   │   ├── content_trend_by_year.png
│   │   └── duration_analysis.png
│   └── README.md
│
└── Task_6_Netflix_Business_Insights_Report/
    ├── reports/
    │   └── netflix_business_insights_report.txt # Executive summary & monetization strategies
    ├── visualizations/
    │   └── executive_business_dashboard.png     # Consolidated performance metrics
    └── README.md
