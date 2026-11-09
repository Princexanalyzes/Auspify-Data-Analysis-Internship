# Task 3: Country-Wise Netflix Content Analysis

## Project Overview
This task analyzes the geographical distribution of content available on Netflix using the cleaned dataset generated in Task 1 (8,790 records). The focus is on identifying leading content-producing countries and evaluating format preferences (Movies vs. TV Shows) across top markets.

---

## Key Findings & Insights
- **Global Leader:** The **United States** leads with **3,240 titles**, dominating both movie production and original series.
- **Strong Regional Hub:** **India** ranks second globally with **1,057 titles**, exhibiting a strong skew toward feature-length Bollywood and regional cinema over episodic series.
- **European & Global Presence:** The **United Kingdom** (638 titles), **Pakistan** (421 titles), and **Canada** (271 titles) complete the leading production hubs.

---

## Visualizations Generated
1. **Top 10 Content Producing Countries (`visualizations/top_10_countries.png`):** Horizontal ranking of content volume per country.
2. **Movies vs. TV Shows Split across Top 5 Nations (`visualizations/movie_tv_split_top5.png`):** Multi-variable comparative analysis of content formats across key markets.

---

## Directory Structure
```text
Task_3_Country_Analysis/
├── notebooks/
│   └── Task_3_Country_Analysis.ipynb
├── visualizations/
│   ├── top_10_countries.png
│   └── movie_tv_split_top5.png
├── reports/
│   └── country_analysis_summary.txt
└── README.md