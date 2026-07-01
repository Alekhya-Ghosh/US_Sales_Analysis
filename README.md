# Sales Overview Dashboard | Power BI

An interactive Power BI dashboard built to analyze sales, profit, and quantity performance across regions and states, with year-over-year (YoY) comparisons from 2021 to 2024.

## Overview

This dashboard provides a consolidated view of regional sales performance for business stakeholders, enabling quick identification of growth trends, underperforming regions, and profit anomalies without manual reporting.

## Features

- **Dynamic KPI Toggle** - Switch between Sales, Profit, and Quantity views using interactive buttons
- **Year Selector** : Filter the entire dashboard by year (2021–2024)
- **Regional Sales Cards** : Monthly sales trend (Jan–Dec) for Central, East, South, and West regions, each showing current sales vs. prior year (PY) sales
- **Geographic Sales Map** : Bubble map visualizing sales distribution by state, sized by sales volume
- **State-Level Breakdown** : Horizontal bar comparison of top-performing states
- **CY vs PY Metrics Table** : Region-wise comparison of Current Year and Previous Year Sales, Profit, and Quantity, with YoY % change indicators (▲/▼) for quick performance scanning

## Key Insights Surfaced

- Total sales of $733.95K across regions with a 20% YoY sales growth
- West and South regions show the strongest YoY sales growth (33% and 31% respectively)
- Central region shows a YoY profit decline of -62% despite flat sales, flagging a margin/cost issue worth investigating
- East and South regions show healthy YoY profit growth (65% and -50% respectively — mixed signal worth drill-down)

## Tools & Techniques

- **Power BI Desktop** : report building and data modeling
- **DAX** : calculated measures for YoY %, CY/PY comparisons, and dynamic KPI switching
- **Power Query (M)** : data transformation and cleaning
- **Bing Maps visual** : geographic sales distribution
- **Bookmarks & Buttons** : for interactive Sales/Profit/Quantity toggle navigation

## Dashboard Preview

![Sales Overview Dashboard](./assets/dashboard-preview.png)

## What This Project Demonstrates

- Translating raw regional sales data into a stakeholder-ready, decision-support dashboard
- Building dynamic, interactive BI reports (not static charts) using DAX and bookmarks
- Identifying and surfacing YoY performance trends and anomalies (e.g., profit decline despite flat sales) for business decision-making
- End-to-end BI workflow: data modeling → transformation → visualization → insight generation

## How to Use

1. Clone this repository
2. Open `Sales Overview.pbix` in Power BI Desktop
3. Use the Sales/Profit/Quantity toggle and year filters to explore the data interactively

---
**Author:** Alekhya Ghosh
[LinkedIn](https://www.linkedin.com/in/alekhya-ghosh-0a9963248/) | [GitHub](https://github.com/Alekhya-Ghosh) 
