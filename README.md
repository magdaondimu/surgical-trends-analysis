<img width="800" height="533" alt="image" src="https://github.com/user-attachments/assets/4a01c9fa-360c-4bea-bf04-3882131f8d73" />

# Surgical Trends and Case Mix Analysis with Anesthesia Utilization (2022–2025)

**Author:** Magdalene Ondimu  
**Context:** Tertiary Referral Hospital in Kenya  
**Domain:** Surgical Theatre Analytics | Health Data Science | Operational Planning  

---

## 📌 Project Overview

This portfolio project analyzes surgical theatre activity between **2022 and 2025**, focusing on:

- Surgical volume trends over time  
- Emergency vs elective workload burden  
- Specialty-driven case mix patterns  
- Anaesthesia utilization (GA vs Regional vs Local)  
- Forecasting future theatre demand for capacity planning  

The goal is to demonstrate how theatre datasets can be transformed into **actionable operational insights** to support:

- Theatre scheduling optimization  
- Workforce and anaesthesia planning  
- Emergency preparedness  
- Executive-level decision-making  

---

## 🎯 Objectives

1. Understand surgical workload patterns over time  
2. Quantify the proportion of emergency surgery and its operational impact  
3. Identify dominant specialties driving theatre demand  
4. Evaluate anaesthesia workload distribution across case mix  
5. Forecast future surgical demand and translate projections into capacity needs  

---

## 🗂 Dataset Description

The cleaned master dataset contains theatre case records with the following variables:

- `YEAR_MONTH` — Monthly surgery period  
- `AGE_YEARS`, `AGE_GROUP` — Patient age demographics  
- `SEX` — Patient sex  
- `TYPE_OF_SURGERY` — Emergency (EM) vs Elective (EL)  
- `SPECIALTY` — Surgical specialty/service line  
- `ANESTHESIA` — Anaesthesia method (GA, SA, Spinal, Local, etc.)  

Derived variables were created for analysis:

- `SURGERY_TYPE_CLEAN` (Emergency/Elective)  
- `SPECIALTY_CLEAN`  
- `ANESTHESIA_GROUP` (General/Regional/Local/Sedation)  

---

## 📓 Project Structure

| Notebook | Title | Focus |
|---------|-------|-------|
| **01** | Data Cleaning Pipeline | Data preparation, standardization, feature engineering |
| **02** | Exploratory Data Analysis + Trends | Volume trends, case mix, specialty burden, anaesthesia patterns |
| **03** | Insights, Conclusions & Recommendations | Executive interpretation, KPIs, leadership recommendations |
| **04** | Forecasting & Theatre Capacity Planning | SARIMAX/ETS forecasting + session-based capacity projections |

---

## 🔍 Key Findings

### ✅ High Emergency Burden
Emergency surgeries consistently represent a large share of total theatre activity, with some periods exceeding **70% emergency dominance**, increasing elective disruption risk.

### ✅ Concentrated Specialty Workload
A small number of specialties account for the majority of theatre volume, supporting specialty-based scheduling templates.

### ✅ Anaesthesia Workload Dominated by GA
General Anaesthesia accounts for the largest proportion of surgeries, with a significant regional/spinal workload requiring balanced workforce expertise.

### ✅ Forecasting Supports Planning
Time-series forecasting suggests sustained high demand into 2026, with peak months requiring proactive staffing and theatre allocation.

---

## 📈 Forecasting & Capacity Planning (Notebook 04)

Forecasting models were evaluated using a 6-month holdout window:

- SARIMAX achieved strong performance for volume prediction  
- Emergency demand showed higher volatility but remained forecastable  
- Capacity translation indicates sustained weekly theatre session requirements  

This provides leadership with a framework for:

- Surge planning during high-risk months  
- GA staffing alignment  
- Emergency buffer theatre protection  

---

## ✅ Recommendations for Theatre Leadership

- Implement forecast-informed monthly theatre planning  
- Protect elective lists during emergency surges  
- Strengthen anaesthesia workforce alignment (GA + Regional capacity)  
- Develop an operational KPI dashboard for continuous monitoring  
- Expand theatre datasets to include duration, cancellations, and outcomes  

---

## ⚠️ Limitations

- No case duration or turnover time data  
- No cancellation reasons or post-operative outcomes  
- Forecasting accuracy depends on historical stability and should be updated as new data becomes available  

---

## 🚀 Next Steps

Future work could extend this project into:

- Theatre efficiency benchmarking (utilization, delays, overtime)  
- Predictive cancellation modelling  
- Specialty-level forecasting  
- Interactive dashboard deployment (Power BI / Tableau)

---

## 📌 Author

**Magdalene Ondimu**  
Health Data Science | Surgical Analytics | AI for Healthcare  

---

⭐ If you found this project helpful or inspiring, feel free to connect or collaborate.


# 📊  Surgical Trends, Case Mix, and Diagnosis Burden Analysis (2022–2025)

## 📌 Project Overview
This project analyzes multi-year hospital theatre data to understand surgical workload, case mix, and diagnosis burden from 2022 to 2025. The analysis focuses on describing trends in surgical volume, patient demographics, clinical characteristics, and perioperative practices to support hospital planning and decision-making.
The project uses real-world routine clinical data and emphasizes data cleaning, transparency, and reproducibility, reflecting the challenges commonly encountered in health data analytics.

## 🎯 Objectives

The main objectives of this project are to:

**Analyze overall surgical volume and trends over time**

**Describe patient demographics (age groups and sex)**

**Examine the balance between elective and emergency surgeries**

**Assess surgical workload by specialty**

**Identify common diagnoses and surgical procedures**

## 🧠  Why This Project Matters

Surgical services consume a large proportion of hospital resources and are a key indicator of population health needs. Understanding who is being operated on, for what conditions, and under what circumstances is essential for:

**Theatre scheduling and capacity planning**

**Workforce allocation**

**Emergency preparedness**

**Quality improvement and audit**

This project demonstrates how routine hospital data can be transformed into actionable insights through systematic analysis.
Explore anesthesia utilization patterns

Generate insights that can inform theatre planning, staffing, and resource allocation

## 🗂️  Project Structure

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

## 🧹 Data Cleaning Pipeline

The data cleaning notebook focuses on:

**Standardizing column names across years**

**Parsing and validating date fields**

**Cleaning and converting mixed age formats into numeric age in years**

**Creating clinically meaningful age groups**

**Handling missing or inconsistent anesthesia records using clinically informed rules**

**Building a reusable pipeline applicable across multiple years**

**Raw data files are not included in this repository due to patient confidentiality and data protection requirements.**

## 📈 Exploratory Data Analysis (EDA)

The EDA notebook explores:

**Univariate Analysis**

Surgical volume by year and month

Distribution by sex and age group

Elective vs emergency surgery patterns

Specialty distribution

Common diagnoses and surgical procedures

Anesthesia utilization

**Bivariate and Multivariate Analysis (in progress)**

Relationships between specialty and urgency

Demographic patterns across surgical types

Trends over time by clinical and operational dimensions

## 🛠️Tools & Skills Demonstrated

Python (pandas, matplotlib, seaborn)

Data cleaning and feature engineering

Exploratory data analysis

Health data reasoning and clinical context

Reproducible analytical workflows

Clear documentation and reporting

## 🔒Data Privacy & Ethics

All analyses are conducted on de-identified routine hospital data.

No raw data or patient-identifiable information is shared in this repository.

## 🚀Status

✔ Data cleaning pipeline completed

✔ Univariate EDA in progress

⏳ Bivariate and multivariate analysis forthcoming

## 📬Contact

This project was developed as part of a health data analytics portfolio.

Feedback and collaboration opportunities are welcome.








