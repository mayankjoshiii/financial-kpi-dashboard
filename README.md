# Financial KPI Dashboard

**Tools:** Excel (Advanced) · Tableau Public · Power BI Desktop
**Dataset:** UK Retail Sales Data (ONS) / Kaggle Financial Dataset
**Live Dashboard:** [View on Tableau Public](#) *(link once published)*

---

## Problem Statement

Finance teams need real-time visibility into revenue performance, cost control, and margin trends. This project builds an end-to-end financial KPI dashboard — from raw data to boardroom-ready visualisations.

---

## What Was Built

### Excel Model (`/data/financial_model.xlsx`)
- **Revenue Forecast** using 3-month and 6-month moving averages
- **Budget vs Actual Variance Analysis** — % variance with conditional formatting (RAG)
- **P&L Summary** — Revenue, Gross Profit, EBITDA by month and segment
- **Pivot Tables** — Drill-down by region, product category, and time period

### Tableau / Power BI Dashboard
4 views with interactive filters (date range, region, product category):

| View | What It Shows |
|------|---------------|
| Revenue Trends | Monthly revenue vs forecast vs budget |
| Profit Margin by Segment | Gross margin % by product category |
| Cost Breakdown | Waterfall chart — COGS, OpEx, EBITDA |
| KPI Status Board | RAG traffic-light for 8 core KPIs |

---

## Key KPIs Tracked

| KPI | Target | Status |
|-----|--------|--------|
| Monthly Revenue | £2.5M | 🟢 On Track |
| Gross Margin % | >42% | 🟡 Watch |
| EBITDA Margin | >18% | 🟢 On Track |
| Revenue Growth MoM | >3% | 🔴 Below Target |
| Cost-to-Revenue Ratio | <58% | 🟢 On Track |
| Top Segment Revenue | >£800K | 🟢 On Track |
| Budget Variance | <5% | 🟡 Watch |
| Forecast Accuracy | >90% | 🟢 On Track |

---

## Repository Structure

```
financial-kpi-dashboard/
├── data/
│   ├── financial_model.xlsx        # Excel model with forecasts + variance analysis
│   └── retail_sales_sample.csv     # Raw data (50-row sample)
├── visualisations/
│   ├── tableau_dashboard.png       # Dashboard screenshot
│   ├── revenue_trends.png
│   └── kpi_rag_board.png
└── README.md
```

---

## How to Use

1. **Excel Model:** Open `data/financial_model.xlsx` — all formulas are unlocked and documented
2. **Tableau Dashboard:** Download `data/retail_sales_sample.csv` and connect in Tableau Public
3. **Power BI:** Import the CSV and use the provided `.pbix` template (coming soon)

---

## Business Insight

> Revenue growth has slowed to 1.8% MoM against a 3% target, driven by underperformance in the North West region (–12% vs budget). Gross margin held above 42% due to cost efficiencies in the Electronics segment. Recommendation: redirect £80K of the North West marketing budget to the South East, where conversion rates are 34% above average.
