![Dashboard Preview](mev-market-dashboard.PNG)
# 🏪 Maven Market Sales Performance Dashboard
### Power BI Business Intelligence Report

---

## 1. 📌 Project Objective
Analyze Maven Market's retail sales data to track revenue, profit, transactions, and product returns — helping management make faster, data-driven business decisions.

---

## 2. 🗂️ Dataset Overview

| Table | Description |
|---|---|
| `Transactions_Data` | Sales records — revenue, profit, transactions |
| `Return_Data` | Product return records |
| `Products` | Product brand and category info |
| `Stores` | Store location details (city, state, country) |
| `Calendar` | Date table for time-based analysis |

---

## 3. ⚙️ Process

- Connected and cleaned 5 related tables in Power BI
- Built a star-schema data model with proper relationships
- Created DAX measures for KPIs and month-over-month comparisons
- Designed an interactive 2-page dashboard with slicers, maps, and charts

---

## 4. ❓ Business Questions & KPIs Solved

| Question | Finding |
|---|---|
| What is the total revenue vs target? | Tracked via Revenue Target gauge |
| Which product brands drive the most profit? | Identified via pivot table by brand |
| What is our product return rate? | Monitored per brand using Return Rate % |
| How are sales trending month-over-month? | Compared using Last Month vs Current KPIs |
| Which store locations perform best? | Visualized on map by city/state/country |

---

## 5. 📊 Dashboard Insights

- **KPI Cards** — Total Revenue, Total Profit, Total Transactions, Total Returns with month-over-month comparison
- **Brand Performance Table** — Shows Transactions, Profit, Profit Margin %, Return Rate per brand
- **Map Visual** — Store performance by geographic location
- **Treemap** — Revenue breakdown by product brand
- **Gauge Chart** — Actual revenue vs monthly revenue target
- **Slicers** — Filter by Year and Month for dynamic analysis

---

## 6. 💡 Project Insights

- Profit Margin and Return Rate are tracked **per brand** to identify weak performers
- Month-over-month KPIs (Last Month Revenue, Profit, Returns) allow quick trend detection
- Geographic map reveals **top-performing store regions**
- Revenue gauge shows whether the team is **on track to hit monthly targets**

---

## 7. ✅ Final Conclusion

This dashboard gives Maven Market managers a **single view** of business health — from brand-level profitability to store-level geography — with time filters to drill into any period. It replaces manual reporting with an **always-updated, interactive** decision tool.

---

## 🛠️ Tools Used
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

---

*Dashboard built by [Wasim Raja](https://github.com/wasim-wr)*
