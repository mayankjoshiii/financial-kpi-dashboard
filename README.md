# Financial KPI Dashboard


**Tools:** Excel (Advanced) · Plotly.js · GitHub Pages  
**Dataset:** UK Retail Sales Data (ONS) / Kaggle Financial Dataset  
**Live Dashboard:** [🔗 View Live Interactive Dashboard](https://mayankjoshiii.github.io/financial-kpi-dashboard/)


---


## Problem Statement

Finance teams need real-time visibility into revenue performance, cost control, and margin trends. This project builds an end-to-end financial KPI dashboard — from raw data to boardroom-ready visualisations.


---


## What Was Built

### Interactive Plotly.js Dashboard (`index.html`)
- **Revenue vs Budget vs Forecast** — monthly trend lines for Jan–Apr 2024
- - **Revenue Mix by Category** — share of total revenue across product segments
- - **Regional Revenue Breakdown** — stacked bar chart by region and month
- - **Profit Margin by Segment** — gross margin % and EBITDA margin % per category
- - **Cost Waterfall (P&L Bridge)** — Revenue → COGS → Gross Profit → OpEx → EBITDA
- - **Budget Variance RAG Table** — Actual vs Budget with Red / Amber / Green status
- - **Revenue Heatmap** — Region × Month intensity matrix
- - **Operating Expenses by Region** — grouped bar chart (£ thousands)
             
- ### Data Preparation (Excel)
- - Revenue forecasting using moving averages
- - Budget vs Actual variance analysis with conditional formatting (RAG)
- - P&L summary by month and segment
- - Pivot tables for drill-down by region, product category, and time period
                     
- ---


## Key KPIs Tracked

| KPI | Value | Status |
|-----|-------|--------|
| Total Revenue (Actual) | £4.92M | 🟢 On Track |
| Revenue Budget | £4.97M | — |
| Gross Margin % | 41.9% | 🟡 Watch |
| EBITDA Margin % | 17.6% | 🟢 On Track |
| Cost-to-Revenue Ratio | 82.4% | 🟢 On Track |
| Revenue MoM Growth | +5.5% | 🟢 On Track |
| Budget Variance | −1.0% | 🟢 On Track |


---


## Repository Structure

```
financial-kpi-dashboard/
├── index.html               # Interactive Plotly.js dashboard (deployed via GitHub Pages)
├── retail_sales_sample.csv   # Source dataset — UK retail sales Jan–Apr 2024
├── requirements.txt          # Python dependencies
├── LICENSE                   # MIT License
└── README.md                 # This file
```


---


## How to Run Locally

1. Clone the repository:
2.    ```bash
git clone https://github.com/mayankjoshiii/financial-kpi-dashboard.git
```
2. Open `index.html` in any modern browser — no server required.
3. 3. To modify the data pipeline, install Python dependencies:
4.    ```bash
pip install -r requirements.txt
```


---


## Live Dashboard

👉 **[View the Interactive Dashboard](https://mayankjoshiii.github.io/financial-kpi-dashboard/)**


---


## Author

**Mayank Joshi** — Business Analyst & Data Analyst
MSc Business Analytics (Distinction) · Swansea University
[LinkedIn](https://linkedin.com/in/mayank-j-016147118) · [GitHub](https://github.com/mayankjoshiii)
