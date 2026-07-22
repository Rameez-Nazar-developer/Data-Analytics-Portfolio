# 📊 Executive Profitability Analysis — Global Superstore

## 📌 Project Overview

This project presents an interactive **e-commerce sales and profitability analysis** built using **Google Looker Studio** and the **Global Superstore dataset**.

The objective of the project was to transform transactional retail data into an interactive business intelligence dashboard that enables users to explore:

* Sales performance
* Profitability
* Profit margins
* Product category performance
* Regional performance
* Customer segment performance
* Discount patterns
* Key business opportunities and risks

The project follows a practical analytics workflow:

**Raw Dataset → Data Cleaning → Exploratory Analysis → KPI Development → Interactive Dashboard → Business Insights → Strategic Recommendations**

The dashboard is designed from an **executive and business decision-making perspective**, focusing not only on revenue generation but also on identifying areas where discounts, product mix, and regional performance affect overall profitability.

---

## 🎯 Project Objectives

The main objectives of this project were to:

1. Analyze overall sales and profitability performance.
2. Identify high-performing and low-performing product categories.
3. Examine profitability differences across geographic regions.
4. Compare performance across customer segments.
5. Investigate the relationship between discounting and profitability.
6. Identify loss-making product sub-categories.
7. Build an interactive dashboard using Google Looker Studio.
8. Translate analytical findings into practical business recommendations.

---

## 🛠️ Tools & Technologies

| Tool                 | Purpose                                      |
| -------------------- | -------------------------------------------- |
| Google Looker Studio | Interactive dashboard and data visualization |
| Microsoft Excel      | Data preparation and cleaning                |
| CSV                  | Dataset storage and data exchange            |
| GitHub               | Project version control and documentation    |
| Markdown             | Project documentation                        |

---

## 📂 Project Structure

```text
04-Looker-Studio-Ecommerce-Analytics/
│
├── Data/
│   ├── Sample-Superstore-csv.csv
│   └── Superstore_Cleaned.csv
│
├── Dashboard/
│   ├── LOOKER_STUDIO_DASHBOARD.md
│   └── Executive_Profitability_Analysis__Global_Superstore.pdf
│
├── Documentation/
│   ├── Executive_Profitability_Analysis__Global_Superstore.docx
│   └── Executive_Profitability_Analysis__Global_Superstore.pdf
│
└── README.md
```

---

## 📊 Dataset Overview

The analysis uses the **Global Superstore / Sample Superstore** retail dataset.

The dataset contains:

* **9,994 transaction records**
* **21 analytical attributes**
* **5,009 unique orders**
* **793 unique customers**
* Coverage across **49 U.S. states**
* **531 cities**
* 4 primary regions

The dataset captures the retail order lifecycle, including:

* Order information
* Shipping information
* Customer information
* Geographic information
* Product categories
* Sales
* Quantity
* Discounts
* Profit

### Dataset Dimensions

The variables can be grouped into four major analytical dimensions:

### 1. Order & Shipping

* Row ID
* Order ID
* Order Date
* Ship Date
* Ship Mode

### 2. Customer Profile

* Customer ID
* Customer Name
* Segment

### 3. Geography

* Country
* State
* City
* Postal Code
* Region

### 4. Product & Financial Performance

* Product ID
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit

---

## 💰 Executive KPI Summary

| KPI                   |                 Result |
| --------------------- | ---------------------: |
| Total Sales           |          $2,297,200.86 |
| Total Net Profit      |            $286,397.02 |
| Overall Profit Margin |                 12.47% |
| Total Units Sold      |                 37,873 |
| Unique Orders         |                  5,009 |
| Unique Customers      |                    793 |
| Average Discount Rate |                 15.62% |
| Geographic Coverage   | 49 States / 531 Cities |

These KPIs provide an overall view of the business's sales scale, profitability, customer reach, and discounting behavior.

---

# 📈 Key Analytical Findings

## 1. Product Category Performance

The analysis identified significant differences between revenue generation and profitability across the three major product categories.

| Category        |       Sales |      Profit | Profit Margin |
| --------------- | ----------: | ----------: | ------------: |
| Technology      | $836,154.03 | $145,454.95 |        17.40% |
| Office Supplies | $719,047.03 | $122,490.80 |        17.04% |
| Furniture       | $741,999.80 |  $18,451.27 |         2.49% |

### Technology

Technology was the strongest overall category, generating the highest sales and total profit.

High-performing sub-categories included:

* Copiers
* Accessories
* Phones

The category demonstrates strong profitability and represents an important driver of overall business performance.

### Office Supplies

Office Supplies represents a high-volume segment of the business.

Strong-performing products such as:

* Paper
* Labels

contribute significantly to profitability despite the category's relatively lower average transaction value.

### Furniture

Furniture represents the most significant profitability concern.

Although the category generated approximately **$742,000 in sales**, it produced only approximately **$18,451 in profit**, resulting in a profit margin of just **2.49%**.

Loss-making sub-categories included:

* Tables
* Bookcases

This indicates that high sales volume does not necessarily translate into healthy profitability.

---

## 2. Regional Performance

Regional analysis revealed substantial differences in profitability.

| Region  |       Sales |      Profit | Profit Margin | Avg. Discount |
| ------- | ----------: | ----------: | ------------: | ------------: |
| West    | $725,457.82 | $108,418.45 |        14.94% |        10.93% |
| East    | $678,781.24 |  $91,522.78 |        13.48% |        14.54% |
| South   | $391,721.91 |  $46,749.43 |        11.93% |        14.73% |
| Central | $501,239.89 |  $39,706.36 |         7.92% |        24.04% |

### Key Finding

The **West region** demonstrated the strongest overall performance, combining high sales with a healthy profit margin and comparatively lower discounting.

The **Central region** represents a major profitability concern.

It recorded:

* The highest average discount rate: **24.04%**
* The lowest profit margin: **7.92%**

This suggests a potential relationship between aggressive discounting and reduced profitability.

---

## 3. Customer Segment Performance

The analysis identified three primary customer segments.

| Segment     | Share of Sales |         Sales |      Profit | Profit Margin |
| ----------- | -------------: | ------------: | ----------: | ------------: |
| Consumer    |          50.6% | $1,161,401.35 | $134,119.21 |        11.55% |
| Corporate   |          30.7% |   $706,146.37 |  $91,979.13 |        13.03% |
| Home Office |          18.7% |   $429,653.15 |  $60,298.68 |        14.03% |

### Key Finding

The **Consumer segment** generates the largest proportion of total sales.

However, the **Home Office segment** demonstrates the highest profit margin.

This suggests an opportunity to examine whether the business can increase its focus on higher-margin customer segments while maintaining the scale of the Consumer customer base.

---

## 4. Discounting & Profitability

One of the most important findings from the analysis is the potential profitability erosion associated with heavy discounting.

Several product areas showed high average discounts while generating weak or negative profitability.

Examples include:

* Binders
* Tables
* Bookcases

### Key Finding

High discounts can increase sales volume while simultaneously reducing or eliminating profit.

Therefore, revenue growth should not be evaluated independently from:

* Discount rates
* Profit margins
* Product-level profitability
* Regional discounting patterns

The analysis suggests that management should focus on **profitable revenue growth rather than revenue growth alone**.

---

# 🔎 Strategic Business Insights

## Insight 1 — Revenue Does Not Equal Profitability

Furniture demonstrates that strong revenue performance can coexist with weak profitability.

Management should therefore monitor both:

* Sales
* Profitability

when evaluating business performance.

---

## Insight 2 — Discounting Requires Greater Control

The Central region's high discount rate and low profit margin suggest that promotional strategies should be reviewed.

Potential actions include:

* Setting discount thresholds
* Reviewing promotional campaigns
* Monitoring discount-to-profit relationships
* Establishing category-specific discount limits

---

## Insight 3 — Product Portfolio Optimization

High-margin products such as:

* Copiers
* Phones
* Paper
* Accessories

represent important profitability drivers.

At the same time, loss-making products such as:

* Tables
* Bookcases
* Certain Supplies

may require pricing, discount, or portfolio-level intervention.

---

## Insight 4 — Regional Strategy Should Be Differentiated

Different regions demonstrate different profitability profiles.

Therefore, a single national discount strategy may not be optimal.

Regional strategies should consider:

* Local demand
* Discount sensitivity
* Product mix
* Customer segment composition
* Profitability targets

---

## Insight 5 — Customer Segment Profitability Should Influence Strategy

Although Consumers generate the largest share of revenue, Home Office customers demonstrate a higher profit margin.

This suggests that customer strategy should consider not only sales volume but also:

* Customer profitability
* Long-term value
* Purchase behavior
* Product mix
* Discount dependency

---

# 📊 Interactive Looker Studio Dashboard

The project includes an interactive dashboard created using **Google Looker Studio**.

The dashboard provides an executive-level view of the Global Superstore business and allows users to explore key performance indicators and business patterns interactively.

### 🔗 Open the Interactive Dashboard

[Open the Interactive Looker Studio Dashboard](https://datastudio.google.com/reporting/29624b81-e27b-48b7-b37b-6a7bf20152a7)

The dashboard can be used to explore:

* Sales performance
* Profit performance
* Profit margins
* Product category trends
* Regional performance
* Customer segment performance
* Discount patterns
* Business profitability

A PDF export of the dashboard is also available in the `Dashboard/` folder.

---

# 📁 Project Resources

### 📊 Dashboard

* [Interactive Looker Studio Dashboard](https://datastudio.google.com/reporting/29624b81-e27b-48b7-b37b-6a7bf20152a7)
* [Dashboard Documentation](Dashboard/LOOKER_STUDIO_DASHBOARD.md)
* [Dashboard PDF Export](Dashboard/Executive_Profitability_Analysis__Global_Superstore.pdf)

### 📂 Data

* [Source Dataset](Data/Sample-Superstore-csv.csv)
* [Cleaned Dataset](Data/Superstore_Cleaned.csv)

### 📄 Documentation

* [Executive Profitability Analysis — DOCX Report](Documentation/Executive_Profitability_Analysis__Global_Superstore.docx)
* [Executive Profitability Analysis — PDF Report](Documentation/Executive_Profitability_Analysis__Global_Superstore.pdf)

---

# 💡 Business Recommendations

Based on the analysis, the following actions are recommended:

### 1. Review High-Discount Products

Investigate products and sub-categories where high discount rates are associated with weak or negative profitability.

### 2. Optimize Central Region Discounting

Conduct a detailed review of the Central region's promotional and pricing strategies.

### 3. Improve Furniture Profitability

Review pricing, shipping costs, product mix, and discount policies for Furniture, particularly Tables and Bookcases.

### 4. Strengthen High-Margin Product Categories

Continue supporting high-performing products and categories such as Technology, Copiers, Phones, Paper, and Accessories.

### 5. Monitor Profitability Alongside Revenue

Adopt a balanced KPI framework that evaluates:

* Sales
* Profit
* Profit Margin
* Discount Rate

rather than relying on revenue alone.

### 6. Develop Segment-Specific Strategies

Evaluate customer segments based on both revenue contribution and profitability.

---

# ⚠️ Project Limitations

The analysis should be interpreted with the following limitations in mind:

* The dataset represents historical transactional activity and may not reflect current market conditions.
* The analysis identifies relationships and performance patterns but does not establish causality.
* The dataset does not contain all potential business drivers, such as operational costs, customer acquisition costs, or external market conditions.
* Profitability analysis is based on the profit field provided in the dataset.
* Discounting and profitability relationships should be investigated further before making causal conclusions.
* The dashboard provides analytical insights but does not replace detailed financial or operational investigation.

---

# 🚀 Future Improvements

Potential future extensions of this project include:

* Adding time-series forecasting.
* Developing customer lifetime value analysis.
* Performing customer segmentation.
* Building predictive profitability models.
* Investigating statistical relationships between discounts and profit.
* Adding geographic mapping and regional drill-downs.
* Creating automated dashboard data refresh workflows.
* Connecting Looker Studio directly to a cloud-based data source.
* Comparing current performance against historical benchmarks.

---

# 🧠 Skills Demonstrated

This project demonstrates practical experience in:

* Data cleaning
* Data preparation
* Exploratory data analysis
* KPI development
* Business performance analysis
* Profitability analysis
* Product analysis
* Regional analysis
* Customer segmentation analysis
* Discount analysis
* Data visualization
* Interactive dashboard development
* Google Looker Studio
* Business storytelling
* Strategic recommendations
* GitHub project documentation

---

## 📌 Conclusion

The Global Superstore analysis demonstrates how transactional e-commerce data can be transformed into actionable business intelligence.

The analysis highlights that **sales growth alone is not sufficient to evaluate business performance**. Profitability is influenced by product mix, discounting strategies, regional performance, and customer segment behavior.

The interactive Looker Studio dashboard provides a practical mechanism for exploring these relationships, while the supporting documentation and reports provide a detailed analytical interpretation of the results.

Overall, the project demonstrates an end-to-end analytics workflow:

**Data → Cleaning → Analysis → KPI Development → Dashboard → Insights → Recommendations**

This project forms part of the broader **Data Analytics & Applied Research Portfolio**, demonstrating practical application of data analytics and business intelligence techniques.
