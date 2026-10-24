# Amazon-Sales-Analysis-Dashboard
Interactive Tableau dashboard analyzing Amazon sales data: revenue trends, top products and categories, regional performance, and customer ratings.

<div align="center">

# Amazon Sales Analysis Dashboard

### An interactive Tableau dashboard for global sales, profit, and logistics performance

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-232F3E?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-FF9900?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Dashboard Preview](#dashboard-preview)
- [Business Objectives](#business-objectives)
- [Key Performance Indicators](#key-performance-indicators)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Dataset](#dataset)
- [Tools and Techniques](#tools-and-techniques)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)
- [Recommendations](#recommendations)
- [Future Enhancements](#future-enhancements)

---

## Overview

This project presents an end-to-end sales analysis of Amazon retail data, built as an interactive, multi-page Tableau dashboard. It consolidates revenue, profit, shipment performance, and unit sales into a single view, allowing stakeholders to move from a high-level summary down to region and country detail in a few clicks.

The homepage provides an executive summary through KPI cards, a region-wise profit ranking, and a country-level profit map, with navigation to deeper analysis pages.

---

## Dashboard Preview

<img width="800" height="545" alt="Amazon_sales_Dashboard_Preview" src="https://github.com/user-attachments/assets/790a7af7-691a-4851-b26c-43f9470c3326" />


> Region and country filters, click-to-filter charts, and map tooltips work across the dashboard.

---

## Business Objectives

1. Measure overall business performance through revenue, profit, and units sold.
2. Identify the highest and lowest performing regions and countries by profit.
3. Monitor logistics efficiency through average shipment days.
4. Enable self-service exploration with interactive filters and dashboard actions.
5. Support data-driven decisions on inventory, pricing, and regional strategy.

---

## Key Performance Indicators

| KPI | Value | Description |
|-----|-------|-------------|
| **Total Revenue** | $691.1M | Total sales value across all orders |
| **Total Profit** | $225.4M | Net profit generated |
| **Average Shipment Days** | 20.67 | Mean time from order to shipment |
| **Units Sold** | 3.1M | Total quantity of items sold |

---

## Dashboard Features

**Homepage**
- **KPI cards** summarizing revenue, profit, shipment days, and units sold
- **Region-wise Profit** bar chart, ranked from highest to lowest
- **Country-wise Profit** map with profit labels and detailed tooltips
- **Global filters** for Region and Country, plus a search control
- **Page navigation** via the "Next" button to move through the dashboard

**Interactivity**
- Click any region to filter the map and KPIs (dashboard actions)
- Hover tooltips with exact profit values and a Keep Only / Exclude option
- Multi-select filters for flexible comparisons
- Consistent branding and layout for an executive-ready look

---

## Key Insights

- **Sub-Saharan Africa** is the highest-profit region, followed by **Europe** and **Middle East and North Africa**.
- **India** and **North America** contribute the least profit among the listed regions, signalling room for growth or a review of cost structure.
- Profit is concentrated in a few regions, so regional performance varies widely.
- Average shipment time of roughly **21 days** is an opportunity area for logistics optimization.
- [Add insight on top countries, e.g. "Country X leads with $Y profit"]
- [Add insight on products, sales channels, or trends over time if covered in other pages]

---

## Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | [Kaggle / Company data / other] |
| **Records** | [number] rows |
| **Time Period** | [start date] to [end date] |
| **Key Fields** | Region, Country, Item Type, Order Date, Ship Date, Units Sold, Unit Price, Unit Cost, Total Revenue, Total Cost, Total Profit |

**Data preparation**
- Checked for missing values, duplicates, and inconsistent formatting
- Standardized region and country names for accurate map plotting
- Created a shipment days field from order date and ship date
- Validated totals against the source data

---

## Tools and Techniques

- **Tableau Desktop / Tableau Public** for dashboard design and publishing
- **Calculated fields** for Average Shipment Days and profit metrics
- **Filters and parameters** for interactive exploration
- **Dashboard actions** for cross-chart filtering
- **Maps (Mapbox)** for geographic profit visualization
- **Custom layout containers** and navigation buttons for a polished UI

---

## Repository Structure

```
Amazon-Sales-Analysis-Tableau-Dashboard/
│
├── Data/
│   └── Amazon_Sales_Data.csv
│
├── Dashboard/
│   └── Amazon_Sales_Dashboard.twbx
│
├── Images/
│   └── Amazon_Dashboard_Preview.gif
│
└── README.md
```

---

## How to Use

1. **Clone or download** this repository.
   ```bash
   git clone https://github.com/your-username/Amazon-Sales-Analysis-Tableau-Dashboard.git
   ```
2. Open `Amazon_Sales_Dashboard.twbx` in **Tableau Desktop** or **Tableau Public** (free).
3. Use the **Region** and **Country** filters at the top to narrow the view.
4. Click a bar in the Region-wise Profit chart to filter the map and KPIs.
5. Use the **Next** button to navigate to the other dashboard pages.


---

## Recommendations

- **Double down on top regions:** Prioritize inventory and marketing investment in the highest-profit regions.
- **Investigate low-profit regions:** Review pricing, costs, and demand in regions such as India and North America to unlock growth.
- **Reduce shipment time:** Target the 20+ day average through warehouse placement, carrier optimization, or regional fulfilment.
- **Monitor profit concentration:** Diversify across regions to reduce dependence on a few markets.

---

## Future Enhancements

- Add product category and sales channel analysis pages
- Include time-series trends and year-over-year comparisons
- Add profit margin and forecasting views
- Build a matching Power BI version for comparison
- Add customer segmentation analysis

---

<div align="center">

If you found this project useful, please consider giving it a star.

</div>
