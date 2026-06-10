# Subscriber Churn & ARPU Recovery Analysis — Kaveri Telecom

An end-to-end Data Analyst / Business Analyst portfolio project simulating a real corporate engagement: diagnosing rising churn and falling ARPU at a fictional Indian regional telecom operator, and delivering data-driven retention and revenue-recovery recommendations.

> **Status: In progress** — phases are committed as they are completed.

## Business Problem

Kaveri Telecom (fictional, ~8.2M subscribers across South India) has seen monthly churn rise from 2.1% to 3.4% and blended ARPU fall from ₹152 to ₹138 over four quarters — an estimated ₹190+ crore annualised revenue erosion. Leadership lacks visibility into **who** is leaving, **why**, and **which retention levers offer the best ROI**.

## Project Phases

| Phase | Deliverable | Status |
|---|---|---|
| 1. Business Context | Company scenario, problem, stakeholders, KPIs | ✅ Done |
| 2. Business Analysis | BRD: problem statement, business case, RCA, stakeholder analysis, process maps, user stories, requirements, RTM | 🔄 In progress |
| 3. Data Model | Data dictionary, ER diagram, schema, SQL DDL, synthetic datasets | ⏳ |
| 4. SQL Analysis | Joins, CTEs, window functions, cohort/funnel/retention/revenue analysis | ⏳ |
| 5. Data Cleaning (Python) | Profiling, missing values, outliers, feature engineering, validation | ⏳ |
| 6. Exploratory Data Analysis | Univariate → multivariate, correlation, trends, behaviour analysis | ⏳ |
| 7. BI Dashboards | Executive, operational, and customer dashboards (Power BI) | ⏳ |
| 8. Advanced Analytics | Churn prediction & customer segmentation | ⏳ |
| 9. Recommendations | Findings, strategy, financial impact, implementation roadmap | ⏳ |
| 10. Executive Presentation | Board-level deck | ⏳ |

## Tools & Techniques

SQL (SQLite/PostgreSQL) · Python (pandas, matplotlib, scikit-learn) · Power BI · AI-assisted analysis workflow (documented per phase)

## Repository Structure

```
01_business_context/      Business scenario, KPIs, strategic objectives
02_business_analysis/     BRD, FRD, process maps, requirements traceability
03_data_model/            Data dictionary, ER diagram, DDL scripts
04_sql_analysis/          Analysis queries with business insights
05_data_cleaning_python/  Cleaning & preparation notebooks
06_eda/                   Exploratory analysis notebooks & findings
07_dashboards/            Dashboard specs, mockups, DAX measures
08_advanced_analytics/    Churn model & segmentation
09_recommendations/       Consulting-style recommendations report
10_executive_presentation/ Board deck
data/                     Synthetic datasets (raw & processed)
```

## A Note on AI Usage

This project deliberately documents an AI-assisted analyst workflow: AI tools were used for drafting, code acceleration, and review, while all business decisions, definitions (e.g., the prepaid churn definition), analytical choices, and final interpretations are my own and are justified in each phase's documentation.

---
*All data is synthetic. Kaveri Telecom is a fictional company; any resemblance to real operators is coincidental.*
