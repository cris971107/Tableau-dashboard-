# YouTube Trending Analysis Dashboard
This project analyzes a dataset of 1,155 records of YouTube trending videos. Using Tableau, I developed a strategic dashboard for Advertising Planning Managers to identify which content categories are dominating specific regions, allowing for data-driven ad placement.

---

## ⚙️ Project Type Flags

- [x] Exploratory Data Analysis (EDA)
- [ ] SQL Analysis / Querying
- [x] Dashboard / Data Visualization
- [ ] Data Pipeline / ETL
- [ ] Predictive Modelling / Machine Learning
- [x] Data Cleaning / Wrangling
- [ ] End-to-End (multiple of the above)
- [ ] Other: ___________

---

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Repository Structure](#3-repository-structure)
4. [Data Processing & Methodology](#4-data-drocessing-and-methodology)
5. [Key Insights](#5-key-insights)
6. [Deliverables](#6-deliverables)
7. [Final Verdict & Recommendations](#8-final_recomendations)
8. [Author](#7-author)

---

## 1. Project Overview

This project involves the design and development of an interactive dashboard to analyze historical YouTube trending data. The primary goal is to provide Video Advertising Planning Managers with a tool to identify content trends across different regions over time to optimize ad placement strategies.

---

## 2. Objectives

Primary Objective:
Analyze the historical trends of YouTube videos by comparing absolute volumes against percentage-based proportions to identify dominant content categories.

Secondary Objective 1:
Enable regional market analysis by tracking and visualizing video trends across different countries (US, CA, GB) to support daily advertising planning.

Secondary Objective 2:
Clean and process raw CSV interaction data within Tableau to ensure metrics such as videos_count and temporal aggregations are accurate for final visualization.

---

## 3. Repository Structure

```
[project-root]/
│
├── docs/                     # Original, unmodified source data - never edited
│
├── deliverables/             # Jupyter, R Markdown, Colab notebooks, Results, Evidence...
│
└── visuals/                  # Exported charts, dashboard screenshots, ERD diagrams


```



---



## 4. Data processing and methodology

The data is sourced from the trending_by_time.csv file, which includes record IDs, regions, dates, category titles, and video counts.

Data Connection: Established a connection to the CSV file within Tableau Desktop.

Data Wrangling: Converted the trending_date field into a standardized Date/Time format for accurate time-series analysis.

Calculated Fields: Developed Table Calculations to compute the "Percent of Total" for the relative trend history area chart.

Filtering Logic: Implemented global filters for trending_date and region to ensure synchronized interactivity across all dashboard components.


---


## 5. Key insights

<!--
  Findings + implications. Not just what happened - what it means.

  WHAT GOOD LOOKS LIKE:
  ✅ "Return rates, not sales volume, explain Region A's underperformance.
      Region A's return rate on home goods was 34% - more than double the
      company average. Revenue was not lost at the point of sale; it was
      lost post-sale through refunds. This points to a fulfilment or
      product quality issue specific to that region, not a demand problem."

  WHAT TO AVOID:
  ❌ "Region A had lower revenue than other regions in Q4."
     (That's an observation. It describes what happened.
      An insight says what it means and where to look next.)

  Aim for 3–6 insights. Quality over quantity.
-->

Category Dominance: The 100% stacked area chart allows managers to see the "market share" of categories like Entertainment or Music, regardless of total volume fluctuations.

Geographic Distribution: The pie chart reveals the relative weight of each country (US, CA, GB) in the trending ecosystem.

Cross-Regional Patterns: The highlight table identifies specific niches where certain categories outperform others in specific countries.

<img width="3166" height="1155" alt="Captura de pantalla 2026-03-04 122717" src="https://github.com/user-attachments/assets/5156b3a1-8805-45d9-b7e7-20b0755152ea" />

---


## 6. Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| Dashboard | Dashboard in tableau | `visuals/Captura de pantalla 2026-03-04 122717.png` |



---


## 7. Final verdict and recommendations

Result: Verdict: The dashboard successfully integrates temporal, categorical, and geographical data, providing a specialized tool for daily marketing planning.


---


## 8. Author

**Cristian Barrientos**

- 🔗 [https://www.linkedin.com/in/cristian-barrientos-pomposo/](https://www.linkedin.com/in/cristian-barrientos-pomposo/)
- 💼 [https://github.com/cris971107](https://github.com/cris971107)
- 📧 cristian971107@hotmail.com



