# Tata Power EV Charging Analysis – README

## What this is
A written report and insights pack built from the Excel workbook `Tata_Power_Cleaned.xlsx`. It summarises the four dashboards and uses the pivot-table sheets behind them for exact numbers.

## Files

| File | Purpose |
|---|---|
| `Tata_Power_EV_Charging_Report.md` | Full report: KPIs, tables and findings for Dashboards 1–4 |
| `Tata_Power_EV_Charging_Insights.md` | 20 numbered insights, recommendations and caveats |
| `README.md` | This guide |

Read the Report first for the numbers, then the Insights for what they mean.

## Workbook structure

| Dashboard | Pivot sheet | Theme | Charts |
|---|---|---|---|
| Dashboard 1 | Sheet1 | Demand, revenue and district capacity | Demand over time · Revenue vs energy · Demand vs capacity by district · Customers vs energy by district |
| Dashboard 2 | Sheet2 | Station utilisation and load | Top 5 districts load · Top 10 over-used stations · Top 10 under-used stations · Plugs vs sessions |
| Dashboard 3 | Sheet3 | Customers, income tiers, EV models | Revenue by tier · Energy by tier · Top EV models · Lowest-session EV models |
| Dashboard 4 | Sheet4 | Investment, payback, ROI | Top 10 ROI districts · Payback by charger · Cost breakdown · Demand vs 5-year ROI |

The dashboards contain charts and slicers only. All figures come from the pivot sheets, which were cross-checked against the chart data.

## Dataset at a glance
114,000 sessions · 8,000 customers · 65 stations · 390 plugs · 18 Bengaluru districts · Aug–Nov · 2.86 GWh · ₹4.97 crore revenue

## Assumptions and limits
- Currency is assumed to be ₹; the file does not label it.
- Aug and Nov are probably partial months. Sep and Oct are the cleanest comparison.
- Row-level data is not available as a sheet, so no analysis was done beyond the pivots.
- Derived figures (sessions per plug, ₹/kWh, shares, correlations, CAPEX totals) were calculated from the pivot values. Everything else is read directly.
- Interpretations are marked as such in the Insights file.
- Slicers could not be applied. The pivots are shown in the state they were saved in.

## Open in
Any text editor or Markdown viewer (VS Code, GitHub, Obsidian). Word versions can be produced on request.
