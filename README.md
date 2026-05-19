# Sleep Health & Lifestyle Analytics Dashboard

## Overview
This project analyzes a real-world dataset of 374 participants to identify which lifestyle factors most strongly affect sleep quality — including stress level, occupation, physical activity, and BMI.

**Dataset:** Sleep Health and Lifestyle Dataset — Kaggle (by Laksika Thamilan)

---

## Dashboard Preview
![Sleep Health Analytics Dashboard](dashboard.png)

---

## Key Findings
- **Stress is the strongest predictor of poor sleep** — quality drops from 9.0 at stress level 3 down to 5.9 at stress level 8
- **Occupation matters significantly** — Engineers averaged the highest sleep quality (8.4/10) while Sales Representatives averaged the lowest (4.0/10)
- **Optimal physical activity is 60–74 min/day** — associated with the highest average sleep quality (7.9), more than very high activity levels
- **Normal BMI correlates with better sleep** — Normal BMI averaged 7.6 sleep quality vs 6.4 for Obese category
- **Overall average sleep quality: 7.3/10** across 374 participants with an average duration of 7.1 hours

---

## Metrics Analyzed
- Sleep quality (1–10 scale)
- Sleep duration (hours per night)
- Stress level (1–10 scale)
- Physical activity level (minutes per day — grouped into 4 buckets)
- Occupation (11 job categories)
- BMI category (Normal, Overweight, Obese)
- Sleep disorders (None, Insomnia, Sleep Apnea)

---

## Tools Used
| Tool | Purpose |
|---|---|
| Apple Numbers | Pivot tables, charts, dashboard design |
| Microsoft Excel | Data cleaning, IF formulas, activity grouping |
| Kaggle | Dataset sourcing and documentation |

---

## Techniques Applied
- Pivot tables for multi-variable aggregation
- IF formula for activity level bucketing (Low / Moderate / Active / Very Active)
- Find & Replace for BMI category standardization
- Clustered bar charts for multi-metric comparison
- Dashboard design with KPI summary cards
- Data limitation analysis (low sample size occupations flagged)

---

## Data Source
| Detail | Info |
|---|---|
| Dataset | Sleep Health and Lifestyle Dataset |
| Source | Kaggle — kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset |
| Author | Laksika Thamilan |
| Records | 374 participants |
| Columns | 13 (Gender, Age, Occupation, Sleep Duration, Sleep Quality, Physical Activity, Stress Level, BMI, Blood Pressure, Heart Rate, Daily Steps, Sleep Disorder) |

---

## Files in This Repository
| File | Description |
|---|---|
| `Sleep_health_and_lifestyle_dataset.csv` | Original Kaggle dataset |
| `Sleep_Health_Analytics.numbers` | Apple Numbers workbook with all pivot tables and dashboard |
| `Sleep_Health_Analytics.xlsx` | Excel export of the workbook |
| `dashboard.png` | Final dashboard screenshot |

---

## About
Built by **Nour Tawil** · B.S. Data Analytics, Southern New Hampshire University
This is the second project in my data analytics portfolio, focused on health and lifestyle analytics using real Kaggle data.
Connect with me on [LinkedIn](www.linkedin.com/in/nour-tawil01)
