# Maternal Health in Pakistan & South Asia

A two-part data analysis project exploring maternal health from two angles: **country-level mortality trends** and **individual-level clinical risk factors**. Built as a portfolio project to apply Python/Pandas-based data analysis to a real, socially relevant issue in a Pakistani context.

## Why This Project

Maternal mortality is a critical public health indicator, and Pakistan's progress on it tells an interesting and underexplored story — strong improvement followed by stagnation. This project combines two datasets to look at both the big picture (national trends over 30 years) and the individual picture (what clinical factors actually drive high-risk pregnancies).

## Project Structure

```
maternal-health-pakistan/
├── README.md
├── maternal_health_pakistan_part1.ipynb   # Country-level mortality trends
├── part2_clinical_risk_factors.ipynb      # Individual clinical risk factors
└── data/
    ├── MaternalMortality.csv
    └── Dataset.csv
```

## Part 1: Country-Level Mortality Trends (1990–2021)

**Question:** How has Pakistan's maternal mortality changed over time, and how does it compare to its South Asian neighbors?

**Key findings:**
- Pakistan's maternal mortality ratio dropped from 418 to 140 (per 100,000 live births) between 1990 and 2021 — a 66.5% improvement.
- Despite this, Pakistan's progress has **stalled since 2017**, remaining flat at 140 for five consecutive years while neighboring countries continued to improve.
- **Nepal had the most dramatic improvement in the region (80.9%)**, despite starting from a far worse position than Pakistan in 1990.
- Pakistan started ahead of India and Bangladesh in 1990 but has since fallen behind both — its early advantage has eroded.
- Sri Lanka has consistently had the lowest mortality ratio in the region, though its relatively low *percentage* improvement reflects an already strong starting point, not stagnation — a useful reminder that improvement % and current performance measure different things.

## Part 2: Clinical Risk Factors (Patient-Level Data)

**Question:** What clinical indicators are most associated with a pregnancy being classified as High Risk?

**Key findings:**
- **Mental health concerns** show the strongest association with High Risk classification (~7.7x difference in High Risk rate between groups) — though the unusually clean magnitude suggests some caution treating this as a precise real-world figure.
- **Blood sugar** shows the next-strongest association, consistent with the known link between gestational diabetes and pregnancy risk.
- **BMI** is consistently higher in the High Risk group, after correcting a data quality issue (22 patient records had an impossible BMI of 0, which were removed).
- **Heart rate** shows a moderate, consistent gap between risk groups.
- **Age** shows only a weak overall association, with effects concentrated mainly among older patients — consistent with "advanced maternal age" as a recognized risk factor.

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

## Data Sources

- Maternal Mortality Ratio dataset (World Bank / UN-derived, via Kaggle)
- Maternal Health and High-Risk Pregnancy Dataset (clinical patient data, via Kaggle)

## About Me

I'm a Computer Science student building toward a career in data analytics. This project is part of my portfolio as I work on real-world analysis projects and prepare for freelance and junior analyst roles.

[LinkedIn](https://linkedin.com/in/mahma-rani1) · [GitHub](https://github.com/mahmarani)
