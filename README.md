# almabetter
Almabetter Project Repository
# 🌍 World Bank Global Education Analysis

This project explores and analyzes global education indicators using World Bank datasets. It focuses on uncovering patterns and relationships across countries and over time, with an emphasis on literacy rates, enrollment ratios, and education expenditure.

---

## 📌 Project Summary

The goal of this project is to perform an exploratory data analysis (EDA) on global education data from the World Bank to:

- Clean and merge relevant datasets
- Identify missing or inconsistent data
- Visualize trends across countries and regions
- Perform statistical tests to examine relationships between key indicators
- Generate actionable insights for policymakers, educators, and researchers

---

## 📁 Dataset

World Bank EdStats datasets:
- `EdStatsData.csv`: Main indicator dataset
- `EdStatsCountry.csv`: Metadata about countries
- `EdStatsSeries.csv`: Metadata about education indicators

All data was downloaded from the [World Bank EdStats website](https://databank.worldbank.org/source/education-statistics-%5e-all-indicators).

---

## 🧪 Key Indicators Analyzed

- **Gross enrolment ratio, primary, both sexes (%)**
- **Literacy rate, adult total (% of people ages 15 and above)**
- **Government expenditure on education (% of GDP)**
- **Pre-primary school enrollment**
- **Education completion rates**

---

## 📈 Analysis Performed

- Data cleaning and preprocessing (handling missing values, merging datasets)
- Country-level filtering for specific case studies
- Correlation matrix for all numerical indicators
- **Pearson correlation test** between:
  - Gross enrolment ratio and literacy rate
- Visualizations:
  - Heatmaps
  - Line plots
  - Bar charts
  - Missing data visualizations

---

## 🧪 Statistical Test

A Pearson correlation test was used to examine the strength and direction of the relationship between two indicators:

```python
from scipy.stats import pearsonr
r, p = pearsonr(x, y)
