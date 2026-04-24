# Pakistan Unemployment Analysis

## Task 2 — Unemployment Analysis with Python

### Overview
This project analyzes unemployment trends in Pakistan using data from
Pakistan Bureau of Statistics (PBS) Labour Force Survey 2024-25.
The project investigates the impact of Covid-19 on employment sectors
and forecasts future unemployment rates using Machine Learning.

---

## Dataset

- Source: Pakistan Bureau of Statistics (PBS)
- Survey: Labour Force Survey 2024-25
- Coverage: All four provinces of Pakistan
- Time Period: 2012 - 2025
- Link: https://www.pbs.gov.pk

---

## Project Structure

| File | Description |
|------|-------------|
| unemployment_analysis.ipynb | Main analysis with Matplotlib charts |
| dashboard.ipynb | Interactive Plotly dashboard |
| data_cleaning.ipynb | Data preprocessing and cleaning |

---

## Features

- National unemployment trend analysis (2012-2025)
- Provincial comparison — Punjab, Sindh, KPK, Balochistan
- Gender gap analysis — Male vs Female unemployment
- Urban vs Rural unemployment comparison
- Youth unemployment analysis (Age 15-24)
- Covid-19 sectoral income impact analysis
- Machine Learning forecast (2026-2030)
- Labour participation rate analysis
- Average monthly wage comparison by province

---

## Key Findings

- National unemployment rate reached 7.1% in 2025, highest since 2003
- KPK recorded highest provincial unemployment at 9.6%
- Female unemployment at 8.9% remains higher than male at 5.6%
- Youth unemployment at 12.4% is nearly double the national average
- Construction sector was hardest hit by Covid-19 with 52.3% income decline
- Agriculture sector was least affected with only 6.5% income decline
- Punjab recorded highest average monthly wage at Rs 22,100
- Approximately 6 million jobs were lost during Covid-19 lockdown in 2020

---

## Technologies Used

| Library | Purpose |
|---------|---------|
| Python 3 | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Static data visualization |
| Plotly | Interactive data visualization |
| Scikit-learn | Machine Learning model |

---

## Machine Learning Model

- Algorithm: Polynomial Regression (Degree 3)
- Purpose: Forecast national unemployment rate from 2026 to 2030
- Result: Unemployment rate projected to reach approximately 7.5% by 2030

---

## How to Run

1. Install required libraries:
pip install matplotlib pandas numpy plotly scikit-learn
2. Open Jupyter Notebook
3. Run unemployment_analysis.ipynb for main analysis
4. Run dashboard.ipynb for interactive charts
5. Run data_cleaning.ipynb for data preprocessing

---

## Covid-19 Impact Summary

| Sector | Income Decline |
|--------|---------------|
| Construction | 52.3% |
| Urban Non-Farm | 48.7% |
| Rural Non-Farm | 47.2% |
| Manufacturing | 38.1% |
| Agriculture | 6.5% |

---

## Provincial Summary 2025

| Province | Unemployment Rate | Average Wage |
|----------|------------------|--------------|
| Punjab | 7.3% | Rs 22,100 |
| Sindh | 5.3% | Rs 19,200 |
| KPK | 9.6% | Rs 17,850 |
| Balochistan | 5.5% | Rs 15,420 |

---

## ML Forecast Results

| Year | Predicted Rate |
|------|---------------|
| 2026 | 7.2% |
| 2027 | 7.3% |
| 2028 | 7.4% |
| 2029 | 7.4% |
| 2030 | 7.5% |

---

## Author

- Name: Vikram Sootahar
- Subject: Data Science and Python Analytics
- Project: Task 2 — Unemployment Analysis with Python
- Institution: CodeAlpha
