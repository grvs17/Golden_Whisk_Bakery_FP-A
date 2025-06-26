# 🧁 Golden Whisk Bakery: Financial Performance Dashboard (2018–2024)

## 📍 Project Background

Golden Whisk Bakery, established in 2018, is a fictional artisanal pastry company that sells its goods both through its website and physical storefronts. As the business continues to expand, Golden Whisk’s leadership is seeking insights to strategically scale operations and ensure long-term viability amid rising artisanal bakery competition.

Although Golden Whisk has collected detailed operational and sales data across its lines of business, these datasets have not been fully leveraged to support strategic decision-making. This report analyzes and synthesizes Golden Whisk’s multi-year sales data to reveal how the company can navigate rising competition, scale sustainably, and strengthen its position through strategic, data-driven decisions.

Insights and recommendations are provided on the following key areas:

- **Sales Trend Analysis:** A historical review of monthly and seasonal revenue performance by product category  
- **Product-Level Performance:** Identification of top-selling and high-margin products across e-commerce and brick-and-mortar channels  
- **Revenue vs Profitability Gaps:** An evaluation of how well the company’s budget, forecast, and EBITDA aligned — and where they did not  


 📊 **Interactive Tableau Dashboard:** [View Full Dashboard](https://public.tableau.com/app/profile/giselle.veracruz/viz/GoldenWhiskBakery/Dashboard?publish=yes)  
📂 **SQL Queries for Data Cleaning and Prep:** *Link coming soon*  

---
## 📦 Data Structure Overview

The Golden Whisk dataset consists of two structured tables: `Brick_Mortar` and `E_Commerce`, capturing sales, cost, and margin data across 2018–2024. The combined dataset includes over 100,000 records, with each transaction categorized by date, channel, product, revenue, COGS, forecasted sales, and budget targets.

<img width="500" alt="Data Schema" src="https://raw.githubusercontent.com/grvs17/Golden_Whisk_Bakery_FP-A/main/images/Data%20Schema.png" />

Prior to analysis, a variety of checks were conducted for quality control and familiarization with the dataset. The SQL queries utilized to inspect and perform quality checks can be found [Link Coming Soon].


Key attributes include:

- **Timeframe:** January 2018 – December 2024  
- **Channels:** E-commerce and Brick & Mortar  
- **Metrics Tracked:** Revenue, COGS, EBITDA, Budget, Forecast  
- **Product Categories:** Cakes, Cookies, Pastries, Breads, Beverages, Seasonal Specials  

---

## 📈 Executive Summary

After steady growth in the early years, Golden Whisk Bakery’s revenue reached a record $1.2M in December 2024, fueled by strong holiday demand and the success of its seasonal specials line. Over the full period analyzed (2018–2024), the company generated $43.2M in total revenue, with Brick & Mortar stores driving 70% of overall sales.

<img width="1104" alt="Executive KPI Overview" src="https://raw.githubusercontent.com/grvs17/Golden_Whisk_Bakery_FP-A/main/images/Executive%20KPI%20Overview.png" />

Despite this growth, analysis revealed two persistent challenges:

- **Underperforming Forecasts:** Budget and forecast values lagged actual revenue for 21 consecutive months from mid-2020 to late 2022 — particularly in high-volume periods. 

- **Profitability Patterns:** Beverages and pastries are the bakery’s most profitable categories, consistently delivering strong margins with low production costs. Cakes remain solid contributors despite higher COGS. In contrast, breads and seasonal specials underperform on margin, signaling potential for pricing adjustments or production streamlining.

**These findings point to clear next steps:** focus on expanding high-margin categories like beverages and pastries while sustaining investment in cakes. For breads and seasonal specials, phase out low-margin items or optimize them by leveraging bundling strategies to increase profitability per transaction.

---

## 🔍 Insights Deep Dive

### Sales Trends

- For 2024, monthly revenue remained relatively stable, with notable peaks in March, July, and December—likely driven by strong seasonal special performance and product mix shifts during promotional periods.
- **Cakes have consistently been the brand’s strongest performer**, contributing ~40% of revenue over the past seven years—including in 2024. **Seasonal launches, special occasion campaigns, and targeted promotions** offer key opportunities to deepen loyalty and grow basket size.
- Despite their limited release, Seasonal Specials consistently generated meaningful revenue surges, making them a high-impact lever during key holiday windows.
- Forecasts closely mirrored actual revenue, with only a slight and consistent gap from budget targets. This level of accuracy suggests Golden Whisk’s planning process is mature — and may now support more ambitious revenue setting without sacrificing control.

<img width="750" alt="Monthly Revenue Trends - 2024" src="https://raw.githubusercontent.com/grvs17/Golden_Whisk_Bakery_FP-A/refs/heads/main/images/Monthly%20Revenue%20Trends%20-%202024.png" />

### Product-Level Performance

- The cake category dominated both top-line and bottom-line performance, with just three SKUs accounting for **28% of total sales** and **outperforming company-wide EBITDA benchmarks**.
- **Pastries and beverages** delivered the highest EBITDA margins (51.7%+), with several pastries — like Pain au Chocolat, Cinnamon Roll, and Apple Turnover — also ranking among the top 30 revenue drivers. These products strike a rare balance between volume and profitability, making them prime candidates for focused growth initiatives.

<img width="613" alt="Top Sellers by Channel" src="https://raw.githubusercontent.com/grvs17/Golden_Whisk_Bakery_FP-A/refs/heads/main/images/Top%20Sellers%20by%20Channel.png" />

### Revenue vs Profitability Gaps

- **High-revenue products aren’t always the most profitable:** Top sellers like cakes and seasonal specials drive sales but come with high costs—some yielding up to 30% lower margins than more modestly selling items.
- **Mid-tier products like Macaron and Latte quietly outperformed:** Despite modest sales, they delivered superior profit margins thanks to low costs—underscoring the need to optimize for margin, not just volume.
- **Bread consistently drives volume, not profit:** Its steady margins and popularity make it ideal as a traffic driver—supporting cross-sell opportunities with higher-margin items that lift overall basket profitability.

<img width="750" alt="Profit Drivers - 2024" src="https://raw.githubusercontent.com/grvs17/Golden_Whisk_Bakery_FP-A/refs/heads/main/images/Profit%20Drivers%20-%202024.png" />

---

📑 **Supplementary Visual Analyses:** [Focused Deep Dives – Forecasting & Profitability - Coming Soon](Insert-Link-to-Focused-Deep-Dives.md)

---

## 🎯 Recommendations

Based on the findings above, the following strategic recommendations are proposed:

- **Prioritize Margin Leaders:** Expand production and promotion of pastries and beverages—consistently top EBITDA performers with scalable potential.
- **Trim Low-Earning Products:** Reevaluate breads and seasonal specials to retire or improve items that sell well but earn too little profit.
- **Set More Ambitious Forecasts:** Reliable forecasting performance suggests Golden Whisk is ready to set more ambitious targets during high-opportunity periods.
- **Leverage Cross-Selling:** Use bread as a volume driver to boost profitability through bundled high-margin add-ons like beverages and pastries.
- **Broaden Seasonal Offerings Year-Round:** Build on the popularity of seasonal items by introducing limited-edition launches tied to underutilized holidays and moments—like Valentine’s Day, Hanukkah, or Kwanzaa—to drive revenue beyond current peak months.


---

## 📌 Caveats and Assumptions

- The dataset used was synthetically generated using Python to reflect realistic bakery economics and seasonal patterns.
- Financial metrics such as EBITDA and COGS were modeled with standard industry assumptions and do not reflect real company records.
- Forecast/budget gaps were intentionally embedded to demonstrate variance analysis methods.
- All dashboards and insights are for demonstration purposes only and should not be interpreted as commercial forecasts.

---

_Authored by Giselle Rosario Veracruz • Portfolio Project • 2025_
📫 [LinkedIn](www.linkedin.com/in/giselle-veracruz) • 💻 [More Projects](https://github.com/grvs17)
