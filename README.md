# Zudio — Store Performance Dashboard

An interactive, single-page analytics dashboard built from a Zudio-style retail sales dataset (100 stores, 8 states, ~7,900 orders across FY2024). Built with vanilla JavaScript and Chart.js — no build step, no backend, just open `index.html`.

**[Live demo →](file:///C:/Users/hp/Downloads/zudio-dashboard-repo/zudio-dashboard-repo/index.html)**

## What it does

- **5 live KPIs** — total sales profit, units sold, orders, average order value, active stores
- **Metric switcher** — swap the measure driving the charts between Sales Profit, Units Sold, and Orders (like changing a field well in Power BI)
- **Cross-filtering** — click any bar or doughnut slice to isolate it; every panel reacts together
- **Filters** — category, store type, state (multi-select), and a month range
- **Charts** — monthly trend, category mix, sales by state, clothing-type ranking, owned vs. rented split, top cities, top-10 store leaderboard

## Why I built this

[Add 2–3 sentences here: what you were practicing (data storytelling, JS charting, dashboard UX), what decisions you made, and what you'd add next.]

## Tech stack

- HTML / CSS / vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for all visualizations
- Data pre-processed and indexed with Python (pandas) for compact client-side loading

## Data

Synthetic/demo retail dataset styled after Zudio (Trent Ltd.) store operations. Not official Zudio data or a Zudio/Trent Ltd. publication.

## Run it locally

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/zudio-dashboard.git
cd zudio-dashboard
open index.html   # or just double-click it
```

---
Built by **Prakash Ekatpure** — [prakashekatpure45@gmail.com](mailto:prakashekatpure45@gmail.com) · +91 77220 24814
