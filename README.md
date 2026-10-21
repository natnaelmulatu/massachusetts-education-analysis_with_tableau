# Massachusetts K-12 Education & School Districts Analysis

An end-to-end data analytics project examining Massachusetts public school districts. This repository investigates the relationship between per-pupil expenditures, student-to-teacher ratios, educator compensation, and academic performance metrics (MCAS proficiency rates and graduation outcomes) across various districts.

---

## 📊 Project Overview & Objectives

Public education funding and resource allocation are subject to continuous debate. This analysis aims to move past anecdotal assumptions by utilizing granular district-level data to evaluate:

* **Resource Impact:** How strongly core inputs (spending per pupil, staffing ratios) correlate with student achievement outcomes.
* **Compensation vs. Performance:** Whether higher average teacher salaries align with superior district performance metrics.
* **Socioeconomic Demographics:** Evaluating how demographic and economic indicators interact with academic achievement across districts.
* **Interactive Storytelling:** Translating complex educational statistics into clear, actionable, and visually compelling Tableau dashboards for stakeholders, policymakers, and educators.

---

## 🛠️ Tech Stack & Methodology

* **Data Wrangling & Cleaning:** Python (Pandas, NumPy) for ingestion, missing value imputation, data type standardization, and merging disparate district datasets.
* **Exploratory Data Analysis (EDA):** Statistical profiling, correlation matrices, and distribution analysis to uncover underlying trends and outliers.
* **Data Visualization & BI:** Tableau Public for building interactive, drill-down dashboards and storytelling layouts.
* **Version Control:** Git & GitHub for workflow management and documentation.

---

## 📂 Repository Structure

```text
├── Data_Dictionary_Massachusetts_schools.pdf                 # Dictionary that explains column names of the dataset
├── MA_Schools.xlsx                                           # Main dataset used for analysis
├── Tableau_Dashboard_Presentation                            # Video explaining the analysis made on the project 
├── Data_Vizualization_for_MIT_Education_Project.twbx         # Dashboard created in Tableau for analysis
└── README.md                                                 # Project documentation

```

---

## 🔍 Key Findings & Insights

* **Diminishing Returns on Spending:** While adequate funding is foundational, raw per-pupil spending alone does not guarantee higher MCAS proficiency. Districts that couple strategic funding with targeted instructional strategies demonstrate superior outcomes.
* **The Educator Factor:** Average teacher salary exhibits a notable positive association with district retention rates and academic performance, highlighting the importance of competitive compensation in attracting and retaining top-tier teaching talent.
* **Class Size Dynamics:** Moderate student-to-teacher ratios correlate with improved individualized support, though administrative efficiency plays a critical role in how classroom resources are ultimately deployed.

*(For a deep-dive narrative breakdown of the findings, read the companion article: [Data-Driven Insights on Education: Analyzing School & Busting Myths](https://www.linkedin.com/pulse/data-driven-insights-education-analyzing-school-busting-nate-mulatu-hx1pe/))*

---

## 📈 Tableau Dashboard

Explore the fully interactive visualization suite on Tableau Public:
👉 **[View the Dashboard on Tableau Public](https://public.tableau.com/app/profile/natnael.mulatu/viz/DataVizualizationforMITEducationProject/Dashboard1)** 

### Dashboard Features:

* **Statewide Overview:** High-level KPIs tracking average spending, graduation rates, and proficiency trends.
* **District Comparison Tool:** Multi-metric scatter plots allowing users to benchmark specific districts against state averages.
* **Expenditure Breakdown:** Visualizing how operational dollars are distributed across instruction, administration, and support services.
