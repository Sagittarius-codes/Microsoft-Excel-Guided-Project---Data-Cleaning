# Freelancer Data Cleaning — Guided Project

A data cleaning project completed as part of a guided exercise, working with a real-world-style freelancer dataset sourced from Kaggle. The focus was on identifying and resolving common data quality issues found in raw datasets.

---

## Dataset

The dataset contains records of 250+ freelancers with information on their skills, experience, hourly rates, activity status, ratings, and client satisfaction scores.

**Source:** Kaggle (Freelancer dataset)  
**Tool used:** Microsoft Excel  
**File:** `Data_Cleaning_Guided_Project.xlsx`

---

## Data Quality Issues Addressed

| Column | Issue | Resolution |
|---|---|---|
| `name_raw` | Names with titles/suffixes (e.g. `Ms. Nicole Kidd`, `Lynn Curtis DDS`) | Stripped to first and last name only |
| `gender_raw` | Inconsistent values (`f`, `F`, `FEMALE`, `female`, `Female`, `m`, `M`, etc.) | Standardized to `Male` / `Female` |
| `hourly_rate (USD)_raw` | Mixed formats (`$40`, `USD 40`, `40`) | Extracted numeric value only |
| `is_active_raw` | Multiple representations (`yes`, `Y`, `True`, `1`, `no`, `N`, `False`, `0`) | Standardized to `Active` / `Not Active` |
| Various columns | Missing values across Age, Hourly Rate, Rating, Years of Experience | Identified and left for downstream handling |

---

## Skills Demonstrated

- Identifying data quality issues in raw datasets
- Standardizing inconsistent categorical values
- Extracting structured data from mixed-format text fields
- Handling missing values
- Organizing raw vs. cleaned columns for traceability

---

## Project Status

This was completed as a guided project to build foundational data cleaning skills. Future extensions planned:

- [ ] Recreate the cleaning logic in Python (pandas)
- [ ] Exploratory data analysis (EDA) with visualizations

---

## Author

**Abdullah**  
CS Undergraduate, COMSATS University  
Building a portfolio in data analytics and software development.
