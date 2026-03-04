# A/B Test Analysis
Analyzed the performance of a new recommendation engine through an A/B test to determine if it significantly improved user conversion across the sales funnel.
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
││
└── visuals/                  # Exported charts, dashboard screenshots, ERD diagrams


```



---



## 4. Data processing and methodology

The data is sourced from the trending_by_time.csv file, which includes record IDs, regions, dates, category titles, and video counts.

Data Connection: Established a connection to the CSV file within Tableau Desktop.

Data Wrangling: Converted the trending_date field into a standardized Date/Time format for accurate time-series analysis.

Calculated Fields: Developed Table Calculations to compute the "Percent of Total" for the relative trend history area chart.

Filtering Logic: Implemented global filters for trending_date and region to ensure synchronized interactivity across all dashboard components.


`visuals/Captura de pantalla 2026-03-04 000520.png`


<img width="1237" height="347" alt="Captura de pantalla 2026-03-04 000520" src="https://github.com/user-attachments/assets/099547b0-04fa-453f-9509-09ed71cd0560" />

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


`visuals/Captura de pantalla 2026-03-03 234335.png`

<img width="1013" height="541" alt="Captura de pantalla 2026-03-03 234335" src="https://github.com/user-attachments/assets/2779e75f-c676-41e7-954f-43ae299933a9" />

---


## 6. Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| Dashboard | Dashboard in tableau | `notebooks/Sprint-15S-2.ipynb` |



---


## 7. Final verdict and recommendations

Result: Verdict: The dashboard successfully integrates temporal, categorical, and geographical data, providing a specialized tool for daily marketing planning.


---


## 8. Author

**Cristian Barrientos**

- 🔗 [https://www.linkedin.com/in/cristian-barrientos-pomposo/](https://www.linkedin.com/in/cristian-barrientos-pomposo/)
- 💼 [https://github.com/cris971107](https://github.com/cris971107)
- 📧 cristian971107@hotmail.com



