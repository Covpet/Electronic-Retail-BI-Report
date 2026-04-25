# Electronic-Retail-BI-Report
This Power BI dashboard delivers a comprehensive performance analysis of a global electronic retail business, transforming raw transactional data into actionable business intelligence across four analytical dimensions: executive performance, sales trends, store-level operations, and delivery efficiency.

# Global Retail Analytics — Power BI Dashboard

[![View Dashboard](https://img.shields.io/badge/Power%20BI-View%20Dashboard-yellow?logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiNmZkZGI3NWQtNzRhMy00OWRhLWI1ZmYtNmI4NWQwOTljYTE4IiwidCI6IjliNDEwMWFiLTIyMDYtNDEyMS1iMDEwLWFhNTczNmJmYzUwYSIsImMiOjF9)
[![Dataset](https://img.shields.io/badge/Kaggle-Dataset-blue?logo=kaggle)](https://www.kaggle.com/datasets/bhavikjikadara/global-electronics-retailers)

# Key Analytical Areas
## Executive Overview
Provides leadership with a high-level snapshot of revenue, profit margins, and overall business health. KPI cards surface critical metrics at a glance, enabling rapid assessment of whether the business is tracking against targets.

## Sales Trends
Examines how revenue and volume shift across time periods, identifying peak seasons, growth trajectories, and potential decline patterns. Time-intelligence DAX measures power period-over-period comparisons that reveal the true momentum behind the numbers.

## Store Analysis 
Breaks down performance at the individual store level, surfacing which locations drive the most value and which underperform relative to their market. This dimension supports strategic decisions around resource allocation, promotions, and store-level interventions.

## Delivery Analysis 
Investigates fulfilment efficiency by tracking delivery timelines and patterns. Identifying bottlenecks in delivery performance allows the business to reduce operational friction and improve customer satisfaction.

# Technical Highlights
* Built on the Sales and Stores tables of the Global Electronic Retailers dataset
* Custom DAX measures for aggregated KPIs, time intelligence, and conditional logic
* Interactive navigation via bookmarks and drill-through for seamless user experience
* Tooltip pages for contextual data exploration without cluttering the report canvas

# Business Value
The dashboard enables data-driven decision-making by connecting sales performance, store operations, and logistics into a unified view reducing the time executives and analysts spend hunting for answers across disconnected reports.


## 📄 Dashboard Pages

| Page | Description |
|------|-------------|
| **Stores Performance Dashboard** | High-level KPIs including total profit, orders, quantity sold, and country-level breakdown |
| **Sales Trend** | Year-over-year and day-of-week order patterns with online vs. in-store channel comparison |
| **Stores Analysis** | Store count, average size (sqm), and orders by country with scatter plot analysis |
| **Delivery Analysis** | Delivery volume, average delivery days, fastest delivery, and year-by-year fulfilment trends |
| **Product Information** | Top products by orders and quantity sold, broken down by country and channel |

---

## 📊 Dashboard Insight Summary

**Report Period:** February 9, 2020 – March 31, 2025 | **Peak Year:** 2023

---

### 💰 Profitability & Financial Performance

The business generated a total profit of **$33 million** across the reporting period, with an overall profit margin of **59%** — a strong indicator of healthy pricing and cost management. The United States emerged as the most profitable market, contributing **43%** of total profit, followed by international markets at **37%**, while the online channel accounted for **20%** of profit — suggesting significant untapped revenue potential in digital sales. A total quantity of **198,000 units** was sold across all channels and markets.

---

### 📈 Sales Trends & Order Volume

Order volumes tell a compelling growth story with a notable dip in 2021 (0.9K orders), likely reflecting post-pandemic disruption, followed by a sharp recovery to **8,900 orders in 2022** — the highest single-year volume recorded. The business reached its commercial peak in **2023**, which was designated the peak performance year. Orders stabilised at approximately 5,700 in 2024, with 2025 still in progress at 3,100 orders through March.

Day-of-week order patterns and the online vs. in-store yearly trend provide further granularity into customer purchasing behaviour across the business cycle.

---

### 🌍 Geographic Distribution

The **United States** dominates order volume with **11,200 orders** — nearly double that of all other countries combined — followed by the **Online channel** (5,600), **United Kingdom** (2,800), **Germany** (1,900), and **Canada** (1,800). Australia, Italy, Netherlands, and France round out the market presence with smaller but consistent order volumes.

In terms of physical footprint, the US also leads with **20 stores**, followed by Germany and France (8 and 7 respectively), the UK (7), Australia (5), Netherlands (4), Canada and Italy (3 each), and one online channel node — totalling **58 stores globally**, averaging **1,400 square metres** per location.

---

### 🏪 Channel Performance

In-store purchasing remains the dominant channel, accounting for **78.8% of orders (20,750)**, while the online channel represents **21.2% (5,580)**. This split points to a customer base that still strongly prefers the physical retail experience — however, the online channel's profitability share (20%) relative to its order share highlights an opportunity to scale digital operations with targeted investment.

---

### 🚚 Delivery & Fulfilment Efficiency

The average delivery time across the reporting period stands at **4.53 days**, with the fastest recorded delivery at just **1 day** — demonstrating operational capability for rapid fulfilment. Delivered orders peaked in **2022** at 4,500, aligning with the broader sales surge that year, before settling into a more consistent range in subsequent years. Continued optimisation of delivery performance could be a key lever for converting more customers to the online channel.

---

### 🖥️ Product Performance

Desktop PCs dominate the product catalogue, with **WWI** and **Adventure Works** brands leading in both volume and order frequency. The top-selling product overall was the **WWI Desktop PC2.33 X2330 Black** with 550 units sold, closely followed by the **WWI Desktop PC1.80 E1800 White** (538 units) and several **Adventure Works PC2.30 and PC1.60** variants. The United States led country-level product orders with **673 orders**, the Online channel contributed **344**, and the UK recorded **141** — reflecting the geographic dominance seen across all other metrics.

---

### 🔑 Key Takeaways

- The US market is the clear revenue and volume engine of the business
- 2022–2023 represents the business's strongest performance window
- In-store channels dominate, but the online channel holds strong profit-per-order potential
- Delivery efficiency is solid, with room to leverage speed as a competitive advantage
- Desktop PCs from WWI and Adventure Works are consistent volume drivers across all markets

---

## 🛠️ Tools & Techniques

- **Tool:** Microsoft Power BI Desktop
- **Data Modelling:** Sales and Stores tables with defined relationships
- **DAX Measures:** Custom KPIs, time intelligence, profit calculations, and conditional logic
- **Features Used:** Bookmarks, drill-through, tooltip pages, slicers, and interactive visuals

---

## 👤 Author

**Covenant**
- Built as part of a Power BI portfolio project
