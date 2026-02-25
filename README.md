

# 📊 Sales Performance Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## Overview

An interactive Tableau dashboard built to analyse retail sales performance across products, customers, and regions. Designed to give sales and operations teams a single view of key business metrics — enabling faster, data-driven decisions without relying on ad-hoc spreadsheet reporting.

---

## Business Questions Answered

- 📈 How is overall sales revenue trending month-over-month and year-over-year?
- 🏆 Which products and product categories are driving the most revenue?
- 👥 Who are the top customers by revenue contribution?
- 🌏 Which regions are over- or under-performing against targets?
- 🔍 Where are the biggest opportunities to grow sales or reduce churn?

---

## Dashboard Highlights

| View | Description |
|---|---|
| **Sales Overview** | High-level KPIs — total revenue, orders, average order value, and MoM growth |
| **Product Performance** | Revenue and volume breakdown by product and category |
| **Customer Analysis** | Top customers ranked by revenue, order frequency, and recency |
| **Regional Performance** | Geographic sales distribution with region-level comparisons |
| **Trend Analysis** | Time-series charts tracking sales velocity and seasonal patterns |

---

## Screenshots
<img width="1377" height="838" alt="Screen Shot 2021-09-06 at 4 32 43 pm" src="https://github.com/user-attachments/assets/4e972ec6-8e54-45e3-b595-82d3d961e477" />
<img width="1422" height="857" alt="Screen Shot 2021-09-06 at 4 32 35 pm" src="https://github.com/user-attachments/assets/bf0851e6-23b5-4103-9a05-a7a36c52ee67" />
<img width="1436" height="853" alt="Screen Shot 2021-09-06 at 4 32 24 pm" src="https://github.com/user-attachments/assets/2b2ccb1c-c011-4415-b15e-459403f97d31" />
<img width="1422" height="853" alt="Screen Shot 2021-09-06 at 4 32 13 pm" src="https://github.com/user-attachments/assets/01ec1972-f267-4286-b115-9804983dc223" />
<img width="1389" height="840" alt="Screen Shot 2021-09-06 at 4 32 03 pm" src="https://github.com/user-attachments/assets/fcfd15c5-7638-441e-8bad-816b852d97a5" />



---

## Data Sources

Three relational datasets joined in Tableau:

| Table | Description |
|---|---|
| `orders.xlsm` | Transaction-level order records including date, product, quantity, and revenue |
| `customer.xlsm` | Customer master data including region, segment, and account details |
| `product.xlsm` | Product catalogue with category, subcategory, and pricing information |

Data was cleaned and prepared in Excel before being modelled as a star schema in Tableau with `orders` as the central fact table joined to `customer` and `product` dimension tables.

---

## Key Insights

- Top 20% of customers accounted for ~65% of total revenue — highlighting a clear opportunity for customer retention focus
- Seasonal peaks observed in Q4, suggesting inventory and marketing alignment is critical in that period
- Certain product subcategories showed high order volume but low revenue contribution — candidates for margin review
- Regional analysis revealed underperforming territories with high customer counts but low average order value

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Tableau Desktop | Dashboard design, data visualisation, calculated fields |
| Microsoft Excel | Data preparation, cleaning, and relational data modelling |

---

## Author

**Abby Wang** — Senior Data Analyst & Analytics Engineer
[abbyting111@gmail.com](mailto:abbyting111@gmail.com) · [LinkedIn](https://www.linkedin.com/in/abbywong5524/) · [GitHub](https://github.com/Abby-tingzhi-wang)
