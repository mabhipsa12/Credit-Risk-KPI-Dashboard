# 📊 Credit Default Risk Analytics Project 🚀
## Project Description
This repository contains the documentation for an end-to-end credit card customer analysis project. I performed detailed data profiling in Excel, extracted crucial insights with advanced SQL queries, and then visualized key credit behavior and default trends in interactive Power BI dashboards.

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement & Objectives](#problem-statement--objectives)
- [Data & Methodology](#data--methodology)
- [Key Findings & Strategic Recommendations](#key-findings--strategic-recommendations)
- [Technical Validation & Quality Assurance](#technical-validation--quality-assurance)
- [Project Documentation](#project-documentation)
- [Data Source](#data-source)
- [Contact](#contact)
- [Dashboard Snapshot](#Dashboard-Snapshot)

---
## Project Overview
This project focused on developing a dynamic KPI reporting system designed to monitor customer repayment behavior, identify high-risk customers, and analyze trends in billing and payments. The ultimate goal was to provide decision-makers with actionable insights to assess potential credit risk and monitor portfolio health effectively.

## Problem Statement & Objectives
**Problem Statement:** 
To effectively mitigate and understand the underlying drivers of credit default risk and its associated financial impacts, this project aimed to analyze customer repayment behavior and credit utilization patterns using credit card data. The objective was to design a robust KPI reporting dashboard that identifies key drivers of default risk, repayment delays, and bill-payment trends across various customer segments (age, gender, education, and marital status), ultimately deriving actionable insights to support enhanced risk assessment and improved decision-making in credit management.

**Project Objectives:**
- Monitor customer repayment behavior.
- Identify high-risk customers based on repayment delay and default likelihood.
- Analyze trends in billing and payments over a 6-month period.
- Segment customer behavior based on demographics such as age, gender, marital status, and education.
- Support decision-makers in identifying potential credit risk and portfolio health.

## Data & Methodology
The analysis utilized a dataset of 30,000 customer records. The project followed a structured approach:
1.  **SQL for Data Acquisition & Pre-processing:** Involved extracting raw data, cleaning inconsistencies, and transforming it to create new, insightful features (e.g., `repayment_category`, `max_delay_segment`, `utilization_ratio`).
2.  **Excel for Data Profiling & Initial Insights:** Used Pivot Tables to conduct preliminary exploratory data analysis, validate data transformations, and identify initial correlations and patterns.
3.  **Power BI for Dashboard Development:** Built an interactive KPI reporting dashboard with dynamic filters and cross-filtering capabilities to visualize trends, demographic risk profiles, and behavioral drivers.

## Key Findings & Strategic Recommendations
Some of the critical insights derived from the analysis include:
-   **Overall Portfolio Health:** Overall default rate of **22.12%**, average credit utilization of **30.58%**, and total loan amount of **5.02 billion**.
-   **Monthly Trends:** Fluctuations in monthly default rates (e.g., dropped from April to May, spiked till August, then dropped in September). Bill amounts showed a degrading trend, while payment amounts remained relatively stable.
-   **Demographic Risk Profiles:** Higher default rates consistently observed among **Males (24.17%)**, **High School educated customers (25.16%)**, the **50+ Age Group (consistently highest rate)**, and **Married customers (23.47%)**.
-   **Behavioral Risk Drivers:** Payment delay severity (`MAX_Delay_Segment`) was identified as a core predictor of default. Worsening delay trends and high credit utilization were also strong indicators of increased risk.

Based on these findings, actionable recommendations were proposed, including:
-   Enhancing underwriting and onboarding for high-risk demographic segments.
-   Implementing a tiered, proactive collections and intervention strategy based on delay severity and trends.
-   Optimizing credit limit management and monitoring utilization patterns.
-   Developing segment-specific financial wellness and support programs.
-   Establishing robust monitoring and regular policy reviews.

## Technical Validation & Quality Assurance
All KPIs and findings in the Power BI dashboard were rigorously cross-verified against direct SQL queries on the cleaned dataset to ensure accuracy and reliability.
https://github.com/mabhipsa12/Credit-Risk-KPI-Dashboard/blob/main/CREDIT%20CARD%20SQL%20QUERRIES.docx

## Project Documentation
For a detailed breakdown of the project, including methodology, specific findings, and comprehensive recommendations, please refer to the full documentation:
Link:
https://github.com/mabhipsa12/Credit-Risk-KPI-Dashboard/blob/main/Credit%20Default%20Risk%20Analytics%20Project%20Documentation.docx

## Data Source
The dataset used for this analysis is:
https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset/data

## Contact
Feel free to connect with me for any questions or collaborations:
- **LinkedIn:** (http://www.linkedin.com/in/abhipsa-mishra-x01)
- **Email:** abhipsamishra001@gmail.com

## Dashboard Snapshot

<img width="1265" height="717" alt="Screenshot 2025-07-23 000729" src="https://github.com/user-attachments/assets/fe743a46-e359-41b4-8638-bba80daa288d" />
