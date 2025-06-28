# Customer-Segmentation-Sales-Insight

###  Overview
This project explores customer behavior using:
- **RFM Segmentation** (Recency, Frequency, Monetary)
- **Market Basket Analysis** (Association Rule Mining)
- **Exploratory Data Analysis (EDA)** with time series, trends, and product/category insights

The goal: Turn raw transactional data into **actionable business insights** that improve **customer retention**, **sales strategy**, and **inventory planning**.

---

###  Files Included
| File | Description |
|------|-------------|
| `Business_Report_RFM_EDA_partA.pdf` | Full report on EDA + RFM segmentation |
| `Business_Report_MBA_EDA_partB.pdf` | Full report on Market Basket Analysis |
| `Customer_Insights_Project_Summary_Final.pdf` | One-page PDF project summary |
| `Business_Report_RFM_EDA_partA.ipynb` | Full report on EDA + RFM segmentation |
| `Business_Report_RFM_EDA_partB.ipynb` | Full report on EDA + RFM segmentation |
| `Workflow_partA.knime ` | KNIME workflow | 
| `Workflow_partB.knime ` | KNIME workflow | 
| `Sales_Data.xlsx` | Dataset for Part A | 
|`dataset_group.csv`| Dataset for Part B |

---

### 🛠 Tools Used
- **Python** (Pandas, Matplotlib, Seaborn) – for EDA
- **KNIME** – for RFM scoring and Association Rule Mining
- **Excel** – data wrangling and aggregation
- **Tableau** – interactive dashboards and visual storytelling

---

###  Key Outcomes

####  RFM Segmentation
- Identified 5 segments: Best, Loyal, Potential Loyalists, At Risk, Lost
- Focused engagement on high RFM-score customers
- Re-engagement strategy proposed for churn-prone segments

####  Market Basket Analysis
- Found frequent product pairs:  
  `{Milk} → {Bread}` (Support: 12%, Confidence: 40%, Lift: 1.3)  
  `{Eggs, Milk} → {Bread}` showed the highest lift (1.5)
- Proposed bundle promotions and inventory optimization

####  EDA Insights
- Seasonality: Peak sales in Q4 across 3 years
- Product-line performance: Classic Cars and Motorcycles lead revenue
- Regional focus: USA, France, and Germany top contributors

---
#### Conclusion

This project demonstrates how data-driven strategies can transform raw sales and transaction data into powerful business insights. By integrating Exploratory Data Analysis (EDA), RFM segmentation, and Market Basket Analysis, we uncovered:

Who the most valuable and loyal customers are

Which product combinations drive the highest basket value

When and where sales peak, and why

How to design targeted, profitable marketing campaigns

Using tools like Python, KNIME, Excel, and Tableau, this end-to-end approach highlights the value of combining analytics and storytelling to drive decisions in sales, CRM, and retail operations.
