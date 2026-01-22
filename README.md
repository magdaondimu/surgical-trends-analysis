📊  Surgical Trends, Case Mix, and Diagnosis Burden Analysis (2022–2025)

📌## Project Overview
This project analyzes multi-year hospital theatre data to understand surgical workload, case mix, and diagnosis burden from 2022 to 2025. The analysis focuses on describing trends in surgical volume, patient demographics, clinical characteristics, and perioperative practices to support hospital planning and decision-making.
The project uses real-world routine clinical data and emphasizes data cleaning, transparency, and reproducibility, reflecting the challenges commonly encountered in health data analytics.

🎯## Objectives

The main objectives of this project are to:

Analyze overall surgical volume and trends over time

Describe patient demographics (age groups and sex)

Examine the balance between elective and emergency surgeries

Assess surgical workload by specialty

Identify common diagnoses and surgical procedures

🧠 ## Why This Project Matters

Surgical services consume a large proportion of hospital resources and are a key indicator of population health needs. Understanding who is being operated on, for what conditions, and under what circumstances is essential for:

Theatre scheduling and capacity planning

Workforce allocation

Emergency preparedness

Quality improvement and audit

This project demonstrates how routine hospital data can be transformed into actionable insights through systematic analysis.
Explore anesthesia utilization patterns

Generate insights that can inform theatre planning, staffing, and resource allocation

🗂️ ## Project Structure

surgical-trends-analysis/
│
├── notebooks/
│   ├── 02_data_cleaning_pipeline.ipynb
│   └── 03_eda_and_insights.ipynb
│
├── data/
│   └── README.md
│
└── README.md

🧹 ## Data Cleaning Pipeline

The data cleaning notebook focuses on:

Standardizing column names across years

Parsing and validating date fields

Cleaning and converting mixed age formats into numeric age in years

Creating clinically meaningful age groups

Handling missing or inconsistent anesthesia records using clinically informed rules

Building a reusable pipeline applicable across multiple years

Raw data files are not included in this repository due to patient confidentiality and data protection requirements.

📈 ## Exploratory Data Analysis (EDA)

The EDA notebook explores:

Univariate Analysis

Surgical volume by year and month

Distribution by sex and age group

Elective vs emergency surgery patterns

Specialty distribution

Common diagnoses and surgical procedures

Anesthesia utilization

Bivariate and Multivariate Analysis (in progress)

Relationships between specialty and urgency

Demographic patterns across surgical types

Trends over time by clinical and operational dimensions

🛠️ ## Tools & Skills Demonstrated

Python (pandas, matplotlib, seaborn)

Data cleaning and feature engineering

Exploratory data analysis

Health data reasoning and clinical context

Reproducible analytical workflows

Clear documentation and reporting

🔒 ## Data Privacy & Ethics

All analyses are conducted on de-identified routine hospital data.

No raw data or patient-identifiable information is shared in this repository.

🚀 ## Status

✔ Data cleaning pipeline completed

✔ Univariate EDA in progress

⏳ Bivariate and multivariate analysis forthcoming

📬 ## Contact

This project was developed as part of a health data analytics portfolio.

Feedback and collaboration opportunities are welcome.








