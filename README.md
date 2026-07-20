# Data-Analytics-Portfolio
MBA (HR &amp; Data Analytics) Portfolio | Interactive dashboards, data cleaning, and business insights using SQL, Power BI, Tableau, and Excel.
# 📌 MASTER PROJECT STATE & CONTINUITY LOG

## 📅 Project Architecture Overview
This workspace represents a 4-Project Data Analytics & Applied Research Portfolio built using GitHub Desktop, Visual Studio Code, SQL, Power BI, Tableau, SPSS, and Excel.

---

## 🏆 The 4 Core Projects (In Order of Priority)

### 1. End-to-End HR Analytics Pipeline
* **Tools:** Excel, SQL (PostgreSQL), Power BI, Tableau Desktop.
* **Core Files:** `HR DATA_Excel.xlsx`, `queries.docx`, `SQL Test Document_Power BI.docx`, `SQL Test Document_Tableau.docx`.
* **Key Achievements:**
  * Cleaned and structured HR demographic data in Excel.
  * Authored complex SQL queries (`crosstab`, aggregations, joins) for attrition metrics.
  * Built matching dynamic reports in both Tableau and Power BI.
  * Executed 11 rigorous QA SQL validation tests per report (**100% Pass Rate / Exact Match**).

### 2. SPSS Advanced Statistical Research: MANOVA (Training Methods)
* **Tools:** SPSS Statistics.
* **Core Files:** `manova (1).sav`, `Output1manova.spv`.
* **Variables:** IV = `Training_Group` (Trainer 1, Trainer 2, Recorded); DVs = `Technical_Expertise`, `Design_Modelling`.
* **Key Findings:**
  * Overall MANOVA: Statistically significant ($\text{Wilks' }\Lambda = 0.828, F = 16.117, p < .001, \eta^2 = .090$).
  * Technical Expertise ($\eta^2 = 16.1\%$): Live training by Trainer 1 ($\mu = 8.68$) significantly outperformed Trainer 2 ($\mu = 5.11$) and Recorded Sessions ($\mu = 5.64$).
  * Design Modelling ($\eta^2 = 3.1\%$): Trainer 1 ($\mu = 6.19$) significantly outperformed Recorded Sessions ($\mu = 5.37$).

### 3. SPSS Advanced Statistical Research: PCA / Factor Analysis (Client Satisfaction)
* **Tools:** SPSS Statistics, Excel.
* **Core Files:** `pcm.xlsx` (`dole-survey (1).sav`).
* **Variables:** 16 Customer Evaluation Survey Items ($N = 388$).
* **Key Findings:**
  * KMO Measure: **0.712** (Good sampling adequacy).
  * Bartlett's Test: $\chi^2(120) = 680.630, p < .001$.
  * Reduced 16 variables into **4 core satisfaction factors** explaining **52.11%** total variance (Varimax rotation):
    1. *Information Provision & Rights Clarity* (14.33%)
    2. *Personal Advisor Support & Guidance* (13.80%)
    3. *Service Respect & Staff Courtesy* (13.74%)
    4. *Reliability & Process Follow-Through* (10.24%)

### 4. E-Commerce Regional Sales Performance
* **Tools:** Google Looker Studio.
* **Dataset:** Superstore E-Commerce Dataset.
* **Key Achievements:** Interactive sales, profit margin, category, and regional performance dashboard.

---

## 📂 Repository Folder Structure
```text
├── 01-HR-Analytics-Pipeline/
│   ├── SQL/
│   ├── Dashboards/
│   ├── Data/
│   └── QA-Testing/
├── 02-SPSS-MANOVA-Research/
├── 03-SPSS-PCA-Factor-Analysis/
├── 04-Looker-Studio-Ecommerce/
├── README.md
└── PROJECT_STATE.md
