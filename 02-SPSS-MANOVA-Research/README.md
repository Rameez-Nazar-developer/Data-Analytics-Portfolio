# Statistical Analysis of Training Methods Using MANOVA

## 📊 Project Overview

This project examines whether different training delivery conditions are associated with differences in two learning outcomes:

- **Design Modelling**
- **Technical Expertise**

A **one-way Multivariate Analysis of Variance (MANOVA)** was conducted using **IBM SPSS Statistics** to determine whether the three training conditions differed significantly when both learning outcomes were considered simultaneously.

The project demonstrates an end-to-end statistical analysis workflow, from research data and statistical testing through interpretation, documentation, and portfolio presentation.

---

## 🎯 Research Context

The analysis compares three training conditions:

1. **Trainer 1** – Live training delivered by Trainer 1
2. **Trainer 2** – Live training delivered by Trainer 2
3. **Recorded Sessions by Trainer 1** – Recorded training sessions delivered by Trainer 1

The purpose of the analysis was to investigate whether the training condition was associated with differences in participants' learning outcomes.

---

## 🎯 Research Objectives

The analysis was designed to:

1. Examine descriptive performance characteristics across the three training conditions.
2. Determine whether training condition has a statistically significant multivariate effect on the combined learning outcomes.
3. Examine the individual effects of training condition on Design Modelling and Technical Expertise.
4. Identify specific group differences using Tukey HSD post-hoc comparisons.
5. Compare the relative magnitude of the training effect across the two learning outcomes.
6. Interpret the practical implications of the statistical findings.

---

## 🗂️ Dataset

The original dataset used for the analysis is an IBM SPSS Statistics data file:

`Data/manova (1).sav`

The dataset contains:

- **Total observations:** 330
- **Training conditions:** 3
- **Observations per group:** 110

### Training Groups

| Training Group | Description | Sample Size |
|---|---|---:|
| Trainer 1 | Live training by Trainer 1 | 110 |
| Trainer 2 | Live training by Trainer 2 | 110 |
| Recorded Sessions by Trainer 1 | Recorded training sessions | 110 |
| **Total** | | **330** |

The dataset therefore represents a balanced research design.

---

## 📌 Variables

### Independent Variable

**Training_Group**

The categorical independent variable contains three training conditions:

- Trainer 1
- Trainer 2
- Recorded Sessions by Trainer 1

### Dependent Variables

**Design_Modelling**

A learning outcome measuring design and modelling performance.

**Technical_Expertise**

A learning outcome measuring technical performance or domain expertise.

---

## 🛠️ Tools & Technologies

The following tools and technologies were used in this project:

- **IBM SPSS Statistics** – Statistical analysis and MANOVA
- **Microsoft Excel** – Supporting data review and analysis assistance
- **GitHub** – Project version control and documentation
- **Markdown** – Project documentation
- **SPSS Viewer Output (.spv)** – Preservation of statistical analysis output

---

## 🔬 Statistical Methodology

The primary statistical method used was:

### One-Way MANOVA

A one-way MANOVA was conducted with:

- **Independent Variable:** Training_Group
- **Dependent Variables:** Design_Modelling and Technical_Expertise

The MANOVA was used because the analysis involved multiple related dependent variables evaluated simultaneously across three independent training groups.

### Follow-Up Analyses

Following the statistically significant MANOVA, the following analyses were examined:

- Univariate ANOVA
- Estimated Marginal Means
- Partial Eta Squared Effect Sizes
- Tukey HSD Post-Hoc Tests
- Homogeneous Subsets
- Profile Plots

---

# 📈 Key Statistical Results

## Multivariate MANOVA Result

The overall MANOVA was statistically significant.

Using Wilks' Lambda:

**Λ = 0.828, F(4, 652) = 16.117, p < .001**

The result indicates that the combined pattern of Design Modelling and Technical Expertise differed significantly across the three training conditions.

The null hypothesis that the three training groups have equal mean vectors across the two dependent variables was therefore rejected.

---

## Univariate ANOVA Results

### Design Modelling

**F(2, 327) = 5.146, p = .006**

Partial Eta Squared:

**ηp² = .031**

Approximately 3.1% of the variance in Design Modelling scores is associated with the Training_Group factor within the model.

The effect was statistically significant but relatively small.

---

### Technical Expertise

**F(2, 327) = 31.379, p < .001**

Partial Eta Squared:

**ηp² = .161**

Approximately 16.1% of the variance in Technical Expertise scores is associated with the Training_Group factor within the model.

The effect was substantially stronger than the effect observed for Design Modelling.

---

# 📊 Group Mean Comparisons

## Design Modelling

| Training Group | Mean |
|---|---:|
| Trainer 1 | 6.1909 |
| Trainer 2 | 5.5818 |
| Recorded Sessions by Trainer 1 | 5.3727 |

Observed pattern:

**Trainer 1 > Trainer 2 > Recorded Sessions**

However, only the difference between Trainer 1 and Recorded Sessions was statistically significant.

---

## Technical Expertise

| Training Group | Mean |
|---|---:|
| Trainer 1 | 8.6818 |
| Trainer 2 | 5.1091 |
| Recorded Sessions by Trainer 1 | 5.6364 |

Observed pattern:

**Trainer 1 > Recorded Sessions ≈ Trainer 2**

Trainer 1 demonstrated a substantially higher mean Technical Expertise score than both other training conditions.

---

# 🔍 Tukey HSD Post-Hoc Results

## Design Modelling

| Comparison | Mean Difference | p-value | Result |
|---|---:|---:|---|
| Trainer 1 vs Trainer 2 | 0.6091 | .057 | Not Significant |
| Trainer 1 vs Recorded Sessions | 0.8182 | .006 | Significant |
| Trainer 2 vs Recorded Sessions | 0.2091 | .710 | Not Significant |

### Interpretation

Trainer 1 significantly outperformed Recorded Sessions in Design Modelling.

The differences between:

- Trainer 1 and Trainer 2
- Trainer 2 and Recorded Sessions

were not statistically significant at α = .05.

---

## Technical Expertise

| Comparison | Mean Difference | p-value | Result |
|---|---:|---:|---|
| Trainer 1 vs Trainer 2 | 3.5727 | < .001 | Significant |
| Trainer 1 vs Recorded Sessions | 3.0455 | < .001 | Significant |
| Trainer 2 vs Recorded Sessions | -0.5273 | .525 | Not Significant |

### Interpretation

Trainer 1 significantly outperformed both Trainer 2 and Recorded Sessions in Technical Expertise.

There was no statistically significant difference between Trainer 2 and Recorded Sessions.

---

# ⭐ Key Findings

### 1. Significant Overall Multivariate Effect

Training condition had a statistically significant effect on the combined outcomes of Design Modelling and Technical Expertise.

### 2. Technical Expertise Showed the Strongest Training Effect

The effect size for Technical Expertise was substantially larger:

**ηp² = .161**

compared with:

**ηp² = .031**

for Design Modelling.

### 3. Trainer 1 Produced the Highest Mean Scores

Trainer 1 achieved the highest observed mean for both outcomes:

- Design Modelling: **6.1909**
- Technical Expertise: **8.6818**

### 4. Trainer 1 Had a Strong Advantage in Technical Expertise

Trainer 1 significantly outperformed:

- Trainer 2 by **3.5727 points**
- Recorded Sessions by **3.0455 points**

Both differences were statistically significant at **p < .001**.

### 5. Live Trainer 1 Training Outperformed Recorded Sessions

Trainer 1 significantly outperformed Recorded Sessions in:

- Design Modelling (**p = .006**)
- Technical Expertise (**p < .001**)

### 6. Trainer 2 and Recorded Sessions Did Not Differ Significantly

No statistically significant differences were found between Trainer 2 and Recorded Sessions for either:

- Design Modelling (**p = .710**)
- Technical Expertise (**p = .525**)

---

# 💡 Practical Interpretation

The findings suggest that training delivery conditions and instructor characteristics may be important considerations when designing learning and development programs.

The strongest differences were observed for Technical Expertise, where participants in the Trainer 1 condition achieved substantially higher scores than participants in the other two conditions.

One possible explanation is that live instructor-led training may provide greater opportunities for:

- Real-time interaction
- Immediate clarification
- Feedback
- Guided practice
- Instructor support

These factors may be particularly relevant when developing technical competencies.

However, the findings represent associations observed within this dataset and should not be interpreted as definitive evidence that one training method directly caused better performance.

Additional research would be required to establish causal relationships and account for factors such as:

- Prior participant experience
- Individual ability
- Motivation
- Learning preferences
- Instructor characteristics
- Training environment
- Participant engagement

---

# ⚠️ Limitations

Several limitations should be considered when interpreting the results.

### Observational Interpretation

The analysis demonstrates associations between training condition and learning outcomes but does not, by itself, establish causality.

### Generalizability

The dataset contains 330 observations, and the findings may not generalize to other populations, organizations, industries, or training environments.

### Limited Outcome Measures

Only two learning outcomes were analyzed:

- Design Modelling
- Technical Expertise

Other potential outcomes, such as satisfaction, engagement, knowledge retention, and long-term performance, were not examined.

### Potential Confounding Factors

Differences between groups may potentially be influenced by factors other than training delivery method, including participant experience, motivation, ability, learning preferences, and instructor characteristics.

### Statistical Assumptions

MANOVA relies on assumptions including:

- Independence of observations
- Appropriate measurement scales
- Multivariate normality
- Homogeneity of covariance matrices

The conclusions should therefore be interpreted within the scope of the assumptions and diagnostic procedures performed during the original analysis workflow.

---

# 📁 Project Structure

```text
02-SPSS-MANOVA-Research/
│
├── Data/
│   └── manova (1).sav
│
├── Documentation/
│   ├── Screenshots/
│   │   ├── descriptive-statistics.png
│   │   ├── multivariate-tests.png
│   │   ├── between-subjects-effects.png
│   │   ├── estimated-marginal-means.png
│   │   ├── tukey-hsd.png
│   │   ├── homogeneous-subsets.png
│   │   └── profile-plots.png
│   │
│   └── MANOVA_Statistical_Analysis_Report.docx
│
├── Output/
│   └── Output1manova.spv
│
└── README.md
