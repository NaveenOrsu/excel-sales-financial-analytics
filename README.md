# Excel Sales & Financial Analytics

**Tools:** Excel · Power Query · Power Pivot · DAX · Pivot Tables · XLOOKUP · SUMIFS

**Source:** Codebasics guided project — AtliQ Hardware (500K+ rows, FY2019–FY2021)

**[Portfolio](https://codebasics.io/portfolio/NAVEEN-ORSU)** · **[LinkedIn](https://www.linkedin.com/in/naveenorsu/)**

---

## Problem

Build sales and financial reports in Excel that let the business track customer and market performance, and read a P&L by year and by month, without rebuilding the report each time.

## Data

- **500K+ transaction rows** across FY2019–FY2021
- **189 customers**, **23 markets**, **298 products**

## What I built

### Sales reports
- Customer performance report — net sales by customer, year on year
- Market performance report — net sales by market against target
- Product and division-level net sales breakdown

### Financial reports
- P&L statement **by fiscal year**
- P&L statement **by month**
- P&L by market

## Techniques used

- **Power Query** — loaded and shaped 500K+ rows, handled data types and joins at source rather than in formulas
- **Power Pivot** — built the data model and relationships so reports refresh instead of being rebuilt
- **DAX measures** — net sales and year-on-year comparisons
- **Pivot tables** for the reporting layer, with **XLOOKUP** and **SUMIFS** for lookup and conditional aggregation
- Conditional formatting to surface under-performing customers and markets

## Repository structure

```
excel/      sales_financial_reports.xlsx
images/     report screenshots
docs/       project summary (optional)
```

## Report screenshots

<!-- Upload PNGs to images/ then uncomment:
![Customer Performance](images/01_customer_performance.png)
![Market Performance](images/02_market_performance.png)
![P&L by Fiscal Year](images/03_pnl_fiscal_year.png)
![P&L by Month](images/04_pnl_month.png)
-->

---

> Guided project from the Codebasics Excel course. The data model, measures and report layout were built by me.
