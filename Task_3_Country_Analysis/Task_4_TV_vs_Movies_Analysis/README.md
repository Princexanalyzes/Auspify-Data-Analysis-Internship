# Task 4: TV Shows vs. Movies Statistical Comparison

## Project Overview
This task conducts a comprehensive statistical comparison between Movies and TV Shows on Netflix using the cleaned dataset (8,790 titles). It analyzes catalog distribution, multi-year content addition trends, and duration/season metrics.

---

## Key Statistical Findings
- **Dominant Format:** Feature films comprise roughly **69.7%** of the entire catalog, while TV series account for **30.3%**.
- **Historical Trajectory:** Content addition expanded exponentially from 2015 to 2019, with movies seeing the steepest acceleration before catalog stabilization.
- **Duration Insights:**
  - **Movies:** Average runtime centers at **98.8 minutes** (median: 98 minutes), with typical films falling between 85 and 115 minutes.
  - **TV Shows:** Approximately **67%** of all series consist of only **Season 1**, reflecting rapid pilot releases and episodic experimentation.

---

## Visualizations Generated
1. **Catalog Distribution (`visualizations/movies_vs_tv_distribution.png`):** Donut chart illustrating the proportional breakdown between Movies and TV Shows.
2. **Timeline Trend (`visualizations/content_trend_by_year.png`):** Multi-year trend line showing content additions since the start of Netflix's streaming focus.
3. **Duration Distributions (`visualizations/duration_analysis.png`):** Side-by-side histogram and countplot covering movie runtimes (minutes) and series season counts.

---

## Directory Structure
```text
Task_4_TV_vs_Movies_Analysis/
├── notebooks/
│   └── Task_4_TV_vs_Movies_Analysis.ipynb
├── visualizations/
│   ├── movies_vs_tv_distribution.png
│   ├── content_trend_by_year.png
│   └── duration_analysis.png
├── reports/
│   └── tv_vs_movies_summary.txt
└── README.md