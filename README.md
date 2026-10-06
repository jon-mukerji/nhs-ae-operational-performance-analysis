# NHS A&E Operational Performance Analysis

## Project Status
**Ongoing — October 2026**

This portfolio project analyses publicly available NHS England A&E attendance and emergency-admission data. The project is being developed incrementally as part of my MSc Data Science & AI learning and data-analytics portfolio.

## Current Scope
The current stage uses monthly NHS England A&E datasets covering **April to August 2026**.

Work completed / currently being developed:
- Collected the monthly NHS England A&E CSV datasets.
- Loaded the monthly datasets into Python using Pandas.
- Began inspecting dataset structure, columns, dimensions and data quality.
- Preparing the monthly files for combination and subsequent operational analysis.

## Planned Analysis
The next stages will be completed progressively:

- Data cleaning and validation in Python/Pandas
- Combine the monthly datasets into an analysis-ready dataset
- Engineer operational KPIs
- Analyse attendance and waiting-time trends
- Explore provider and regional performance
- Load prepared data into MySQL
- Answer operational questions using SQL
- Build a Power BI dashboard for stakeholder-facing reporting

> Planned items above are not presented as completed work.

## Business Questions
As the project develops, the analysis will explore questions such as:

- How do A&E attendances change month by month?
- How does four-hour performance vary over time?
- Which providers experience higher levels of operational pressure?
- How do long waits after Decision to Admit vary?
- What trends could be useful to an operational or management audience?

## Tools
- Python
- Pandas
- MySQL *(planned)*
- Power BI *(planned)*
- Jupyter Notebook / VS Code

## Repository Structure

```text
nhs-ae-operational-performance-analysis/
├── README.md
├── .gitignore
├── requirements.txt
├── data/
│   └── raw/
├── notebooks/
│   └── 01_data_loading_and_inspection.ipynb
├── sql/                       # added as SQL work is completed
└── powerbi/                   # added when dashboard work begins
```

## Data Source
The project uses publicly available **NHS England A&E Attendances and Emergency Admissions** monthly data for the 2026/27 reporting year.

Source: NHS England — A&E Attendances and Emergency Admissions.

The raw data remains the property of its original publisher. This repository is an independent educational/portfolio analysis and is not affiliated with or endorsed by NHS England.

## Portfolio Purpose
The purpose of this project is to develop and demonstrate an end-to-end data-analysis workflow using a real UK public-sector dataset, progressing from data preparation and exploratory analysis to SQL-based analysis and stakeholder-oriented Power BI reporting.

## Development Approach
This repository will be updated as each stage is completed. The commit history is intended to show the progression of the project rather than presenting unfinished work as completed.
