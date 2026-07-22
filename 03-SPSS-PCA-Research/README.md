# Principal Component Analysis (PCA) of Client Satisfaction in Unemployment Benefit Services

## 📌 Project Overview

This project applies **Principal Component Analysis (PCA)** to a client satisfaction survey dataset related to unemployment benefit services.

The purpose of the analysis is to identify the underlying dimensions that explain how clients perceive the quality of service delivery. Instead of analyzing each survey question independently, PCA was used to reduce a set of 16 operational survey indicators into a smaller number of meaningful and interpretable service dimensions.

The analysis identified **four underlying service pillars**:

1. **Administrative & Information Transparency**
2. **Interpersonal Care & Respect**
3. **Caseworker Engagement & Effort**
4. **Agreement Follow-Through & Operational Reliability**

Together, the four retained components explain **52.11% of the total variance** in the 16 survey items.

The project combines statistical analysis, SPSS output interpretation, factor diagnostics, strategic recommendations, and potential Business Intelligence (BI) applications.

---

## 🎯 Research Objectives

The main objectives of this project are to:

- Examine the underlying structure of client satisfaction in unemployment benefit services.
- Determine whether the survey data are suitable for PCA.
- Identify the optimal number of components to retain.
- Reduce 16 survey indicators into a smaller set of meaningful dimensions.
- Interpret the resulting components using Varimax rotation.
- Evaluate communalities and individual measures of sampling adequacy.
- Assess how well the extracted component solution reproduces the observed correlation structure.
- Translate statistical findings into actionable management recommendations.
- Explore how PCA-derived dimensions could support Power BI, Tableau, or other BI dashboards.

---

## 📊 Dataset Overview

| Attribute | Description |
|---|---|
| Dataset | `dole-survey (1).xlsx` |
| Total Cases | 388 respondents |
| Total Variables | 23 |
| Survey Items Used in PCA | 16 |
| Survey Item Range | v1–v18 operational items selected for PCA |
| Demographic Variables | `sex`, `ssn` |
| Overall Outcome | `overall` |
| Saved Factor Scores | `FAC1_1` – `FAC4_1` |
| Primary Software | IBM SPSS Statistics |
| Additional Tools | Python, Excel |
| Extraction Method | Principal Component Analysis |
| Rotation Method | Varimax with Kaiser Normalization |
| Retained Components | 4 |
| Cumulative Variance Explained | 52.11% |

The PCA was performed on **16 operational survey indicators** measuring different aspects of the client experience.

---

## 🧪 Statistical Methodology

The PCA workflow followed the following sequence:

1. Dataset preparation and variable selection
2. Descriptive frequency analysis
3. Correlation matrix examination
4. KMO Measure of Sampling Adequacy
5. Bartlett's Test of Sphericity
6. Anti-image correlation and individual MSA analysis
7. Principal Component extraction
8. Eigenvalue analysis
9. Scree plot examination
10. Component retention using Kaiser’s Criterion
11. Varimax rotation
12. Rotated Component Matrix interpretation
13. Communality analysis
14. Reproduced correlation and residual analysis
15. Component transformation analysis
16. Component plot interpretation
17. Factor score generation
18. Strategic and managerial interpretation

---

# 🔍 Factorability Assessment

## KMO and Bartlett's Test

The dataset demonstrated sufficient statistical suitability for PCA.

### Kaiser-Meyer-Olkin (KMO)

**KMO = 0.712**

The KMO value indicates an acceptable level of sampling adequacy and suggests that the variables share sufficient common variance for factor extraction.

### Bartlett's Test of Sphericity

**χ² = 680.630**

**df = 120**

**p < 0.001**

Bartlett's Test was statistically significant, indicating that the correlation matrix is not an identity matrix. Therefore, meaningful relationships exist among the survey items, supporting the use of PCA.

### Conclusion

The combined KMO and Bartlett's results confirm that the dataset is suitable for Principal Component Analysis.

---

# 🔗 Correlation Structure

The correlation matrix revealed several meaningful clusters of related survey items.

### Cluster 1: Interpersonal Care & Respect

Strong relationships were observed among:

- Privacy
- Reception desk friendliness
- Feeling taken seriously
- Appropriate tone of written communication

### Cluster 2: Caseworker Engagement & Effort

Correlations were observed among:

- Caseworker motivation
- Time spent with clients
- Interview preparation
- Identification of suitable job opportunities

### Cluster 3: Administrative & Information Transparency

Relationships were identified among:

- Benefit information clarity
- Rights awareness
- Information accessibility
- Application process clarity
- Knowledge of who can answer benefit questions

### Cluster 4: Agreement Follow-Through & Reliability

Relationships were observed among:

- Agreements being followed through
- Clarity regarding remaining procedures
- Caseworker promise fulfillment

These correlation patterns provided an initial indication that client satisfaction is multidimensional rather than represented by a single underlying construct.

---

# 📉 Anti-Image Matrix & Individual MSA

The Anti-Image Correlation Matrix was examined to evaluate the sampling adequacy of individual variables.

Individual Measures of Sampling Adequacy ranged approximately from:

**0.582 to 0.773**

All variables exceeded the minimum acceptable threshold of **0.50**.

Therefore:

- No individual variable required removal.
- All 16 variables were retained.
- The dataset demonstrated adequate variable-level suitability for PCA.

---

# 📈 Factor Extraction

## Eigenvalue Analysis

Using **Kaiser's Criterion (Eigenvalue > 1.0)**, four components were retained.

| Component | Eigenvalue | Variance Explained |
|---|---:|---:|
| Factor 1 | 2.675 | 16.72% |
| Factor 2 | 2.308 | 14.43% |
| Factor 3 | 1.857 | 11.61% |
| Factor 4 | 1.496 | 9.35% |
| **Total** | | **52.11%** |

The four-component solution explains **52.11% of the total variance** across the 16 survey indicators.

This demonstrates that the original survey structure can be simplified into four broader dimensions while retaining a meaningful proportion of the information contained in the original variables.

---

# 📊 Scree Plot

The Scree Plot showed a noticeable decline in eigenvalues across the first four components, followed by a flattening of the curve beginning around Component 5.

The fifth component had an eigenvalue of approximately **0.916**, falling below the Kaiser retention criterion.

The Scree Plot therefore provides additional support for retaining a **four-component solution**.

---

# 🔄 Varimax Rotation

A **Varimax orthogonal rotation with Kaiser Normalization** was applied to improve interpretability and achieve a clearer component structure.

The rotated solution produced four interpretable service dimensions.

---

# 🧩 Four-Factor Solution

## Factor 1 — Administrative & Information Transparency

This factor represents the extent to which clients receive clear, accessible, and understandable information about their unemployment benefit and administrative procedures.

Key indicators include:

- Clear information about unemployment benefits
- Understanding of client rights
- Ease of finding benefit information
- Clarity regarding application progress
- Knowing who can answer benefit-related questions

### Interpretation

This factor represents the **information infrastructure of service delivery**.

Weaknesses in this dimension may result in:

- Client confusion
- Difficulty navigating administrative procedures
- Increased dependency on staff assistance
- Reduced confidence in the benefit process

### Management Implications

Potential interventions include:

- Improving online information architecture
- Simplifying benefit documentation
- Creating clear application-process roadmaps
- Improving "Who can answer my question?" contact information
- Developing searchable self-service resources

---

## Factor 2 — Interpersonal Care & Respect

This factor captures the human and relational aspects of the client experience.

Key indicators include:

- Reception desk friendliness
- Protection of client privacy
- Feeling taken seriously
- Appropriate tone of written communication

### Interpretation

This factor represents the **quality of interpersonal treatment** experienced by clients.

The factor demonstrates that client satisfaction is influenced not only by administrative efficiency but also by whether clients feel respected, heard, and treated professionally.

### Management Implications

Potential interventions include:

- Front-desk customer service training
- Privacy protection procedures
- Communication quality standards
- Clear and respectful letter templates
- Training in active listening and client dignity

---

## Factor 3 — Caseworker Engagement & Effort

This factor represents the quality and intensity of direct caseworker support.

Key indicators include:

- Caseworker motivation
- Time dedicated to the client
- Interview preparation
- Identification of suitable job opportunities

### Interpretation

This factor demonstrates the importance of **individualized caseworker attention**.

Clients are more likely to perceive the service positively when caseworkers:

- Spend sufficient time with them
- Prepare for consultations
- Provide relevant employment opportunities
- Actively motivate them

### Management Implications

Potential interventions include:

- Caseload management
- Improved appointment preparation procedures
- Data-driven job matching tools
- Better workload distribution
- Training focused on individualized client support

---

## Factor 4 — Agreement Follow-Through & Operational Reliability

This factor represents the consistency with which commitments and agreed procedures are implemented.

Key indicators include:

- Agreements being followed through
- Caseworker promise fulfillment
- Clarity regarding remaining procedures

### Interpretation

This factor represents **organizational reliability and accountability**.

A positive interaction with a caseworker may lose value if agreed actions are not subsequently completed.

### Management Implications

Potential interventions include:

- Automated follow-up reminders
- Commitment tracking within CRM systems
- Written summaries of agreed actions
- Clear ownership of follow-up tasks
- Service-level agreement monitoring

---

# 📏 Communalities

Communalities indicate the proportion of variance in each variable explained by the retained components.

The extracted communalities ranged approximately from:

**0.420 to 0.649**

All 16 variables exceeded the empirical benchmark of **0.40**.

This indicates that every item has an acceptable level of shared variance with the four-component solution.

The results therefore support retaining all 16 survey indicators in the final PCA model.

The strongest shared variance was observed for the item relating to identifying suitable job opportunities, while the lowest retained communality remained above the acceptable threshold.

---

# 🔁 Reproduced Correlations & Residual Analysis

The reproduced correlation matrix was examined to determine how effectively the four-component solution reconstructs the original correlation structure.

The residual matrix showed that:

- **46 nonredundant residuals**
- **38.0%** exceeded an absolute residual value of **0.05**

The proportion remains below the commonly used 50% diagnostic benchmark.

This indicates that the four-component model provides a reasonably effective representation of the observed correlation structure, although some unexplained relationships remain.

---

# 📋 Rotated Component Structure

The final PCA solution can be summarized as follows:

| Factor | Dimension | Key Survey Indicators |
|---|---|---|
| Factor 1 | Administrative & Information Transparency | Benefit information, rights, information accessibility, application process, contact knowledge |
| Factor 2 | Interpersonal Care & Respect | Privacy, friendliness, feeling taken seriously, written communication tone |
| Factor 3 | Caseworker Engagement & Effort | Motivation, time, interview preparation, job opportunities |
| Factor 4 | Agreement Follow-Through & Reliability | Agreements, promises, remaining procedures |

The analysis demonstrates that client satisfaction is **multidimensional**.

---

# 💡 Key Research Findings

### Finding 1 — Client Satisfaction Is Multidimensional

The PCA identified four distinct dimensions rather than a single generalized satisfaction construct.

### Finding 2 — Information Transparency Is a Core Service Dimension

Clients' understanding of benefit information, rights, procedures, and available contacts forms a distinct dimension of service quality.

### Finding 3 — Interpersonal Treatment Matters

Privacy, friendliness, respect, and communication tone form a separate dimension that influences how clients experience the agency.

### Finding 4 — Caseworker Effort Is Distinct

Time investment, motivation, preparation, and relevant job matching represent a separate dimension of service delivery.

### Finding 5 — Follow-Through Builds Operational Trust

Clients distinguish between the quality of an interaction and whether commitments are actually fulfilled afterward.

---

# 📊 Descriptive Satisfaction Patterns

The descriptive survey analysis supports the four-factor structure.

### Information & Administrative Transparency

Several information-related indicators showed substantial neutral and negative responses, suggesting that clients may experience difficulty understanding rights, procedures, and benefit-related information.

### Caseworker Engagement

Caseworker-related items generally showed more favorable response distributions, particularly regarding the identification of suitable job opportunities and time dedicated to clients.

### Interpersonal Care

Interpersonal indicators showed comparatively stronger satisfaction, particularly regarding the tone of written communication and respectful treatment.

### Operational Reliability

Responses regarding promise fulfillment and agreement follow-through were more mixed, suggesting a potential gap between client interaction and subsequent execution.

---

# 🏢 Strategic Management Framework

The four-factor model can be translated into four operational management pillars.

| Factor | Service Pillar | Strategic Focus |
|---|---|---|
| F1 | Information Transparency | Digital information, process clarity, self-service |
| F2 | Interpersonal Care | Respect, privacy, communication quality |
| F3 | Caseworker Effort | Workload, preparation, job matching |
| F4 | Operational Reliability | Commitments, follow-up, accountability |

---

# 🛠️ Recommended Improvement Actions

## Factor 1 — Information Transparency

- Redesign digital self-service navigation.
- Simplify benefit information.
- Provide clear application-process roadmaps.
- Improve visibility of contact information.
- Create searchable FAQ resources.

## Factor 2 — Interpersonal Care

- Conduct front-desk customer service training.
- Strengthen privacy procedures.
- Review written communication templates.
- Promote respectful and accessible language.

## Factor 3 — Caseworker Engagement

- Review caseworker caseloads.
- Improve appointment preparation.
- Introduce job-matching decision support tools.
- Encourage individualized consultation planning.

## Factor 4 — Operational Reliability

- Introduce automated follow-up reminders.
- Track client commitments in CRM systems.
- Provide written appointment summaries.
- Monitor completion of promised actions.

---

# 🗓️ Implementation Roadmap

## Phase 1 — Quick Wins (Months 1–3)

Focus:

- Information Transparency
- Interpersonal Care

Actions:

- Simplify correspondence templates.
- Improve digital information navigation.
- Clarify benefit rights and procedures.

## Phase 2 — Core Process Refinement (Months 4–6)

Focus:

- Caseworker Engagement
- Operational Reliability

Actions:

- Introduce appointment action summaries.
- Improve commitment tracking.
- Strengthen caseworker preparation.
- Improve job matching processes.

## Phase 3 — Continuous Governance (Months 7–12)

Focus:

- All four service dimensions

Actions:

- Launch ongoing satisfaction monitoring.
- Build factor-based dashboards.
- Conduct quarterly performance reviews.
- Monitor service quality trends over time.

---

# 📈 BI & Dashboard Integration

The PCA results can be integrated into Business Intelligence tools such as:

- Power BI
- Tableau
- Looker Studio

Instead of monitoring 16 individual survey questions independently, organizations can monitor four broader service dimensions.

Potential dashboard KPIs include:

| Factor | Example KPI |
|---|---|
| F1 | Information Transparency Score |
| F2 | Interpersonal Care Score |
| F3 | Caseworker Engagement Score |
| F4 | Operational Reliability Score |

The dashboard can also include filters for demographic and operational characteristics such as:

- Sex
- Age
- Regional office
- Benefit duration
- Other available respondent characteristics

This allows management to identify whether specific groups experience different service quality patterns.

---

# 🐍 Python Reproducibility

The PCA workflow can be reproduced programmatically using Python libraries including:

- `pandas`
- `numpy`

The computational workflow includes:

1. Loading the correlation matrix.
2. Performing eigenvalue decomposition.
3. Sorting eigenvalues.
4. Extracting the first four components.
5. Calculating unrotated component loadings.
6. Applying Varimax rotation.
7. Generating a formatted rotated loading matrix.

This creates an additional reproducibility layer alongside the SPSS analysis.

---

# ⚠️ Methodological Limitations

Several limitations should be considered when interpreting the results.

### Variance Explained

The four-factor solution explains **52.11%** of total variance. Although this represents a meaningful proportion in applied social science research, approximately **47.89%** remains unexplained.

### Cross-Loadings

Some variables may have secondary relationships with other dimensions. Therefore, factor assignments should be interpreted conceptually alongside statistical loadings.

### Orthogonal Rotation

Varimax rotation assumes that extracted factors are uncorrelated. In real-world service environments, information transparency, interpersonal care, caseworker effort, and reliability may naturally influence one another.

### Missing Data

Survey items contain a small proportion of missing responses.

The saved standardized regression factor scores contain fewer complete cases than the original dataset, indicating that missing-value handling should be considered when using factor scores in downstream analysis.

### Causal Interpretation

PCA identifies patterns of shared variance but does not establish causal relationships between service dimensions and client satisfaction.

---

# 📌 Data Integrity Notes

The original dataset contains:

- **388 total respondents**
- **23 variables**
- **16 PCA survey indicators**
- **Small amounts of item-level missing data**
- **Standardized regression factor scores generated by SPSS**

The factor scores have:

- Mean approximately **0**
- Standard deviation approximately **1**

This confirms their standardized nature.

---

# 📂 Repository Structure

```text
03-SPSS-PCA-Research/
│
├── Data/
│
├── Documentation/
│   ├── Screenshots/
│   │   ├── communalities.png
│   │   ├── component_plot.png
│   │   ├── kmo.png
│   │   ├── scree_plot.png
│   │   ├── rotated_component_matrix.png
│   │   └── other SPSS output screenshots
│   │
│   ├── Principal Component Analysis (PCA) of Client Satisfaction in Unemployment Benefit Services.docx
│   └── Principal Component Analysis (PCA) of Client Satisfaction in Unemployment Benefit Services.pdf
│
├── Output/
│
└── README.md
