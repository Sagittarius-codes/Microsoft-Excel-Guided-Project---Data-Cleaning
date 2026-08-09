# Freelancer Data Analysis — Guided Project

A guided end-to-end Excel analytics project using a real-world-style freelancer dataset sourced from Kaggle. Covers data cleaning, pivot table analysis, and a summary dashboard.

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

## Workbook Structure

| Sheet | Description |
|---|---|
| `Data` | Raw and cleaned columns side by side |
| `Pivots` | PivotTables summarizing key metrics |
| `Dashboard` | Visual summary of insights |

---

## Pivot Tables Built

- **Average Rating by Primary Skill** — compares performance across skill categories
- **Freelancer Distribution by Experience Bucket** — shows experience spread (0-5 yrs up to 36-40 yrs)
- **Count by Hourly Rate Tier** — breakdown of freelancers across rate bands ($20–$100)
- **Count by Language** — freelancer distribution across 15 languages
- **Count by Country** — geographic spread across 22 countries

---

## Skills Demonstrated

- Identifying and resolving data quality issues in raw datasets
- Standardizing inconsistent categorical values
- Extracting structured data from mixed-format text fields
- Identifying missing values across multiple columns
- Building PivotTables for multi-dimensional analysis
- Designing a dashboard to communicate findings visually

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