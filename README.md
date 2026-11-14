# Excel Sales & Financial Analytics

**Tools:** Excel · Power Query · Power Pivot · DAX · Pivot Tables · XLOOKUP · SUMIFS

**Source:** Codebasics guided project — AtliQ Hardware (500K+ rows, FY2019–FY2021)

**[Portfolio](https://codebasics.io/portfolio/NAVEEN-ORSU)** · **[LinkedIn](https://www.linkedin.com/in/naveenorsu/)**

---

## Problem

Build sales and financial reports in Excel that let the business track customer and market performance, and read a P&L by year, by month and by market — without rebuilding the report every time new data arrives.

## Data

- **500K+ transaction rows** across FY2019–FY2021
- **189 customers**, **23 markets**, **298 products**
- Fiscal year runs September to August

## Reports in this repository

Exported as PDF so they can be read without opening Excel.

| Report | What it shows |
| --- | --- |
| [01 — Customer Performance](reports/01_customer_performance.pdf) | Net sales by customer, FY2020 vs FY2021, filterable by region, market and division |
| [02 — Market Performance vs Target](reports/02_market_performance_vs_target.pdf) | Net sales by country against target, with the gap in % |
| [03 — P&L by Fiscal Year](reports/03_pnl_by_fiscal_year.pdf) | Full P&L for FY2019–FY2021 with a 21 vs 20 variance column |
| [04 — P&L by Market](reports/04_pnl_by_market.pdf) | FY2021 P&L split by market, filterable by region and sub-zone |
| [05 — P&L by Month](reports/05_pnl_by_month.pdf) | P&L by fiscal quarter and month within a selected year |

## How the reports were built

- **Power Query** — loaded and shaped 500K+ rows, fixed data types and merged the sales, product and customer tables at source instead of with worksheet formulas
- **Power Pivot** — built the data model and relationships so the reports refresh instead of being rebuilt
- **DAX measures** — net sales, gross margin and year-on-year comparisons
- **Pivot tables** as the reporting layer, with **XLOOKUP** and **SUMIFS** for lookups and conditional totals
- Conditional formatting to surface under-performing customers and markets at a glance

## What the reports show

- Net sales grew from **₹87.5M (FY2019)** to **₹196.7M (FY2020)** to **₹598.9M (FY2021)** — a **204.5%** rise in FY2021 over FY2020
- Customer and market reports rank performance against target, so the accounts and countries falling short are visible without filtering by hand

---

> Guided project from the Codebasics Excel course. The data model, measures and report layout were built by me.
