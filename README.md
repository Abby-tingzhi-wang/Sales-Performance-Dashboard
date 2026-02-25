

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

![Dashboard Overview](Screen%20Shot%202021-09-06%20at%204.32.03%20pm.png)
![Product Performance](Screen%20Shot%202021-09-06%20at%204.32.13%20pm.png)
![Customer Analysis](Screen%20Shot%202021-09-06%20at%204.32.24%20pm.png)
![Regional View](Screen%20Shot%202021-09-06%20at%204.32.35%20pm.png)
![Trend Analysis](Screen%20Shot%202021-09-06%20at%204.32.43%20pm.png)

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
