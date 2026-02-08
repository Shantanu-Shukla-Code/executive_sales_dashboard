## 📌 Project Overview

This project presents an executive-level sales and profitability dashboard built in Power BI.
The goal is to evaluate overall business health, identify growth opportunities, assess regional and product performance, and highlight potential operational risks using historical sales data.
The dashboard is designed for decision-makers, focusing on clarity, comparability, and actionable insights rather than raw metrics alone.

---

## 🎯 Business Objectives

The dashboard answers the following key business questions:

* How is the business performing overall?
* Is the company growing, stagnating, or declining?
* Which regions should we invest in more or less?
* Which product categories should be scaled or deprioritized?
* Are there operational inefficiencies affecting performance?
* What are the key risks to future growth?

---

## 📊 Dashboard Structure

The dashboard consists of five well linked pages. The basic layout includes the header, page selection tab, information button and the year slicer. Along with these essentials, the report consists of multiple pages, each serving a specific analytical purpose.

### Overview

* Selected-year Revenue, Cost, and Profit
* Business Growth & Profitability metrics such as Growth Percent (Revenue Growth Same Period Last Year), Profit Percent(Selected-Year), Profit YoY% (Same Period Last Year)
* Total Profit by Region Visualiser and Monthly/Year on Year Performance Trends
* Completely interactive and responsive report corresponding to selected region or selected year to analyse overall contribution, performance and growth

### Regional Analysis

* Profit Heatmap to analyse profit divison by a region or a country
* Profit, Revenue & Profit Percent for each region and top five countries
* Bottom five countries as per their profit percent
* The region page is completely interactive with the ability to select year, country or region to study each region, its statistics and identify markets that need to be scaled as well as markets that needs further analysis before investment

### Product / Item Analysis

* Revenue, profit and profit percent contribution by item category
* Distribution of item categories across the two sales channel
* The report can be used to understand key items for revenue and profit as well as the items that drag the business down with the help of interactive environment utitlising the year slicer & item selection

### Orders Analysis

* Region based shipping time analysis comparing average vs maximum shipping times
* Average shipping time, profit & revenue per each sales channel
* Order priority analysis using the units sold and average shipping time
* The report is used to analyse efficiency of current order delivery operations as per different regions, sales channel, priorities over the years

### Key Insights

* Direct business questions with summarized answers
* Data-supported recommendations
* Key risks and strategic considerations

---

## 🛠️ Tools & Skills Used

### Power BI

* DAX

  * CALCULATE
  * VAR
  * SUM
  * SWITCH
  * SAMEPERIODLASTYEAR

### Data Modeling

* Star schema
* One-to-many relationships
* Data Transformation

### Dashboard Design

* Executive-focused KPI selection
* Visual hierarchy
* Color Storytelling
* Insight-driven storytelling

---

## ⚠️ Assumptions & Limitations

* The latest year contains partial data; all growth metrics are calculated using same-period-last-year logic to ensure fair comparison.
* Shipping data is used as a proxy for operational efficiency due to limited logistics data.
* Customer-level demand and marketing data were not available, limiting demand-side analysis.
* Recommendations are directional and intended to guide further investigation rather than serve as final strategic decisions.

---

## 📁 Repository Structure

```
📁 powerbi-sales-dashboard/
│
├── README.md
├── Sales_Dashboard.pbix
├── data/
│   └── sales data.csv
├── screenshots/
│   ├── Overview.jpg
│   ├── Region.jpg
│   ├── Items.jpg
│   ├── Orders.jpg
│   ├── Key Insights.jpg
│   ├── Items MENA selected.jpg
│   ├── Region Europe Selected.jpg
│   └── Region Help.jpg
```

---

## 📬 Contact

If you have feedback or would like to discuss this project, feel free to reach out.
