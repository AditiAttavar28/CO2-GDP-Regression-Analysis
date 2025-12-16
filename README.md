# CO₂ Emissions and GDP Per Capita — Regression Analysis

## Overview
This repository contains a **Business Analytics course project** analyzing the relationship between **CO₂ emissions per capita** and **economic development (GDP per capita)** using multivariable linear regression.

The objective is to test whether carbon-intensive activity remains a statistically and economically significant driver of prosperity after controlling for demographic and structural factors.

---

## Research Question
**Does higher CO₂ emissions per capita lead to higher GDP per capita?**

- **Dependent Variable:** GDP Per Capita  
- **Main Independent Variable:** CO₂ Emissions Per Capita  
- **Controls:** Year, Birth Rate, Renewable Energy Share, Extreme Poverty Share

---

## Data
- **Source:** [Our World in Data](https://ourworldindata.org/)
- **Coverage:** 70 countries, 1990–2023  
- **Observations:** 1,308 rows  

Datasets were merged by **Country** and **Year** and cleaned to avoid multicollinearity.

---

## Methodology
- Multivariable linear regression
- Removal of redundant CO₂ variables to address multicollinearity
- Residual and correlation diagnostics

---

## Key Results
- **CO₂ Per Capita Coefficient:** ≈ **$14,922**  
- **Statistical Significance:** p < 0.05  
- **95% CI:** (13,910, 15,933)  
- **R²:** ~0.58  

**Interpretation:** Holding other variables constant, a 1-metric-ton increase in CO₂ emissions per capita is associated with an increase of approximately **$14,922 in GDP per capita**.

---

## Files in This Repository
```text
co2-gdp-regression-analysis/
│── notebooks/
│   └── co2_gdp_regression_analysis.ipynb
│── docs/
│   └── co2_gdp_regression_analysis_report.pdf
│── data/
│   └── final_dataset.xlsx
│── README.md
