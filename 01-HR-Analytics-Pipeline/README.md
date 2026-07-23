# 📊 HR Analytics Pipeline

A hands-on HR analytics and business intelligence project exploring employee demographics, workforce characteristics, job satisfaction, and employee attrition using multiple data analytics and visualization tools.

This project demonstrates a multi-tool analytics workflow covering data preparation, exploratory analysis, SQL-based analysis, dashboard development, data visualization, quality assurance, and professional reporting.

---

## 📌 Project Overview

The project uses an HR employee dataset containing information about employee demographics, education, department, job role, business travel, job satisfaction, and employee attrition.

The analysis focuses on understanding workforce composition and identifying patterns associated with employee attrition and retention.

The project was developed as a hands-on learning project using a structured tutorial workflow, with additional practice in organizing, documenting, validating, and presenting the work as an end-to-end analytics portfolio project.

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Analyze overall workforce characteristics.
* Examine employee attrition and retention patterns.
* Explore attrition across gender, departments, education fields, and age groups.
* Analyze employee job satisfaction across different job roles.
* Develop business intelligence dashboards using multiple visualization tools.
* Use SQL queries to calculate and validate key workforce metrics.
* Compare dashboard results against analytical outputs for quality assurance.
* Document the complete analytics workflow in a structured GitHub repository.

---

## 🗂️ Dataset

The HR dataset contains **1,470 employee records** and includes fields related to:

* Employee demographics
* Gender
* Marital status
* Age and age groups
* Department
* Education
* Education field
* Job role
* Business travel
* Employee count
* Attrition status
* Job satisfaction
* Active employee status

The project repository contains the source datasets used across the different analysis and dashboard workflows.

---

## 🛠️ Tools & Technologies

### Data Analysis & Preparation

* Microsoft Excel

### Database & Querying

* PostgreSQL
* SQL

### Business Intelligence & Visualization

* Microsoft Power BI
* Tableau

### Documentation & Version Control

* Microsoft Word
* GitHub
* GitHub Desktop

---

## 🔄 Project Workflow

```text
HR Dataset
    ↓
Data Preparation & Exploration
    ↓
Excel Analysis & Dashboard
    ↓
SQL-Based Workforce Analysis
    ↓
Power BI Dashboard
    ↓
Tableau Dashboard
    ↓
SQL-Based Validation & QA Testing
    ↓
Business Insights & Recommendations
    ↓
Professional Project Reporting
```

---

# 📊 1. Excel Analysis

Microsoft Excel was used to work with the HR dataset and develop an initial analytical dashboard.

The Excel workflow focused on exploring key workforce and attrition metrics, including:

* Total Employee Count
* Attrition Count
* Attrition Rate
* Active Employees
* Average Age
* Department-wise Attrition
* Employee Distribution by Age
* Attrition by Gender
* Education Field-wise Attrition
* Attrition across Age Groups and Gender

The Excel dashboard provided an initial visual overview of the HR dataset and served as part of the foundation for the subsequent Power BI and Tableau reporting workflows.

**Related project resources:**

* [View Excel Dashboard File](./Dashboards/HR%20DATA_Excel.xlsx)
* [View Excel Dashboard Screenshot](./Dashboards/Screenshots/excel%20dashboard%20.png)
* [View HR Data Files](./Data/)

---

# 🗄️ 2. SQL Analysis

PostgreSQL was used to explore the HR dataset and calculate key workforce and attrition metrics.

The SQL analysis included queries for:

* Employee Count
* Attrition Count
* Attrition Rate
* Active Employee Count
* Average Employee Age
* Attrition by Gender
* Department-wise Attrition
* Employee Distribution by Age
* Education Field-wise Attrition
* Attrition by Gender and Age Group
* Job Satisfaction by Job Role

A PostgreSQL `crosstab()` operation was also used to create a job satisfaction matrix showing employee distribution across satisfaction levels for different job roles.

The SQL query documentation included in this repository reflects the SQL workflow practiced during the project.

**Related project resources:**

* [View SQL Analysis Documentation](./SQL/HR_Analytics_SQL_Queries_Documentation.docx)
* [View HR Data Files](./Data/)

---

# 📈 3. Power BI Dashboard

An interactive HR Analytics dashboard was developed in Microsoft Power BI.

The dashboard presents key workforce indicators and visualizations covering:

* Employee Count
* Attrition Count
* Attrition Rate
* Active Employees
* Average Age
* Department-wise Attrition
* Employee Distribution by Age Group
* Attrition by Gender
* Education Field-wise Attrition
* Attrition across Age Groups and Gender
* Job Satisfaction by Job Role

The dashboard provides an interactive reporting environment for exploring workforce composition and employee attrition patterns.

**Related project resources:**

* [View Power BI Dashboard File](./Dashboards/new%20project%20hr%20analytics.pbix)
* [View Power BI Dashboard Screenshot](./Dashboards/Screenshots/powerbi_hr_analytics_dashboard.png)

---

# 📊 4. Tableau Dashboard

A corresponding HR Analytics dashboard was developed using Tableau.

The Tableau dashboard presents a visual analysis of:

* Overall workforce KPIs
* Department-wise attrition
* Employee age distribution
* Attrition by gender
* Job satisfaction by job role
* Education field-wise attrition
* Attrition patterns across age groups and gender

An education filter was also incorporated into the dashboard to support interactive exploration of the workforce data.

The Tableau packaged workbook is included in the repository together with a dashboard preview image.

**Related project resources:**

* [View Tableau Dashboard File](./Dashboards/HR_Analytics_Tableau_Dashboard.twbx)
* [View Tableau Dashboard Screenshot](./Dashboards/Screenshots/tableau_hr_analytics_dashboard.png)

---

# 🧪 5. Quality Assurance & Validation

Quality assurance testing was performed by comparing selected dashboard metrics and visual outputs against SQL query results.

The validation process covered **11 analytical tests** for both the Power BI and Tableau reporting workflows.

The tested areas included:

1. Employee Count
2. Attrition Count
3. Attrition Rate
4. Active Employee Count
5. Average Age
6. Attrition by Gender
7. Department-wise Attrition
8. Employee Distribution by Age / Age Group
9. Education Field-wise Attrition
10. Attrition by Gender and Age Group
11. Job Satisfaction Rating

The documented QA test results recorded:

* **Total Tests:** 11
* **Passed:** 11
* **Failed:** 0
* **Blocked:** 0
* **Not Executed:** 0

**Related project resources:**

* [View Power BI QA Testing Documentation](./QA-Testing/PowerBI_HR_Analytics_QA_Testing.docx)
* [View Tableau QA Testing Documentation](./QA-Testing/Tableau_HR_Analytics_QA_Testing.docx)
* [View QA Testing Folder](./QA-Testing/)

---

# 📌 Key Workforce Insights

The analysis of the HR dataset highlighted several workforce and attrition patterns.

### Overall Workforce

* Total employees analyzed: **1,470**
* Active employees: **1,233**
* Attrition count: **237**
* Overall attrition rate: **16.12%**
* Average employee age: approximately **37 years**

### Departmental Attrition

Research & Development accounted for the largest share of total employee exits due to its larger workforce size.

Sales showed a higher relative attrition rate compared with the other major departments, indicating a potential area for further investigation.

### Age & Attrition

Younger employees showed higher levels of attrition, with employees in the early-career age groups representing a significant proportion of total employee exits.

This suggests that employee retention strategies may benefit from focusing on early-career workforce segments.

### Job Roles

Attrition varied considerably across job roles. Some operational and sales-oriented roles showed higher attrition levels, while several senior and management-oriented roles demonstrated comparatively lower turnover.

### Job Satisfaction

The analysis also explored job satisfaction levels across different job roles and workforce segments.

These findings provide an opportunity to investigate whether employee engagement and job satisfaction may be associated with retention patterns.

> These observations are descriptive findings from the dataset and should not be interpreted as proof of causal relationships.

---

# 📄 6. Project Documentation & Reports

A formal project report was prepared to document the overall HR Analytics Pipeline, including the project objectives, methodology, analytical workflow, tools used, findings, insights, and recommendations.

Both editable and PDF versions of the report are available.

**Related project resources:**

* [View Project Documentation Folder](./Documentation/)
* [View Project Report — DOCX](./Documentation/HR_Analytics_Pipeline_Project_Report.docx)
* [View Project Report — PDF](./Documentation/HR_Analytics_Pipeline_Project_Report.pdf)

---

# 📁 7. Project Repository Structure

```text
01-HR-Analytics-Pipeline/

├── Data/
│   ├── HR Data.xlsx
│   ├── HR Data (tableau).xlsx
│   └── hrdata (1).csv
│
├── SQL/
│   └── HR_Analytics_SQL_Queries_Documentation.docx
│
├── Dashboards/
│   ├── HR DATA_Excel.xlsx
│   ├── HR_Analytics_Tableau_Dashboard.twbx
│   ├── new project hr analytics.pbix
│   │
│   └── Screenshots/
│       ├── excel dashboard .png
│       ├── powerbi_hr_analytics_dashboard.png
│       └── tableau_hr_analytics_dashboard.png
│
├── QA-Testing/
│   ├── PowerBI_HR_Analytics_QA_Testing.docx
│   └── Tableau_HR_Analytics_QA_Testing.docx
│
├── Documentation/
│   ├── HR_Analytics_Pipeline_Project_Report.docx
│   └── HR_Analytics_Pipeline_Project_Report.pdf
│
└── README.md
```

---

# 📚 Learning & Attribution Note

This project was completed as part of a hands-on learning process using a structured tutorial workflow.

The tutorial provided guidance on the dataset, dashboard development approach, SQL analysis, and SQL-based validation process. The SQL queries and QA testing templates included in the repository were adapted and documented as part of following and practicing the tutorial workflow.

The project is presented as a learning and portfolio project to demonstrate practical exposure to:

* Excel-based data analysis
* PostgreSQL and SQL querying
* Power BI dashboard development
* Tableau dashboard development
* Data visualization
* Dashboard validation
* Quality assurance testing
* Professional project documentation
* GitHub project organization

The purpose of including the project is to demonstrate the practical workflow and tools explored during the learning process while maintaining transparency about the use of tutorial resources.

---

# 🚀 Project Status

**Status:** Completed — Portfolio Version

The project has been organized into a structured GitHub repository containing:

* Source datasets
* Excel analysis and dashboard
* SQL analysis documentation
* Power BI dashboard
* Tableau dashboard
* Dashboard screenshots
* QA testing documentation
* Formal project report in DOCX format
* Formal project report in PDF format

---

## 📬 Contact

For more information about my projects and learning journey, please visit my GitHub profile:

**GitHub:**
https://github.com/Rameez-Nazar-developer
