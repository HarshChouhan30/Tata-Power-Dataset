# Tata Power EV Charging – Key Insights & Recommendations

Companion to `Tata_Power_EV_Charging_Report.md`. Based on Dashboards 1–4 and the pivot tables (Sheet1–Sheet4) behind them.
Where a point is my interpretation rather than a number in the workbook, it is marked **(interpretation)**.

---

## Dashboard 1 – Demand & Revenue

**1. Growth has slowed after the Aug–Sep ramp.**
Sessions rose 43.9% from Aug to Sep, then only 2.6% from Sep to Oct (38,604 → 39,606). Nov (8,970) is probably a partial month.
*Action:* confirm the Nov cut-off date before reading it as a decline, and track weekly demand.

**2. Revenue is a pure volume story.**
Revenue per kWh is ₹17.36–17.38 in every month, and revenue per session is ₹434–437. Revenue growth therefore comes only from more sessions and more kWh.
*Action:* price, time-of-day tariffs or fast-charge premiums are untested levers.

**3. Capacity decides district volume.**
Sessions per plug sit between 287 and 297 in every district. Plug count and district kWh are almost perfectly correlated (≈ 0.999).
**(interpretation)** This is unusually uniform for real-world charging. It could mean demand is well matched to capacity, or that the data was generated or allocated per plug. Worth checking with the data owner before using it for siting decisions.

**4. Top 3 districts carry nearly a quarter of energy.**
Indiranagar, Rajajinagar and Jayanagar (30 plugs each) deliver 23.2% of kWh. The eight smallest districts (12 or 18 plugs each) together hold about 34% of energy.

**5. Customers roam widely.**
District-level distinct customers add to 77,329 against 8,000 real customers (≈ 9.7 districts each). Customer behaviour is network-wide, not tied to a home district.
*Action:* use network-level loyalty and app features rather than district-level ones.

---

## Dashboard 2 – Utilisation

**6. Station load is balanced.**
Stations range from 1,635 to 1,862 sessions (average ≈ 1,754). The busiest is about 6% above average and the quietest about 7% below. Because the spread is narrow, "over-" and "under-utilised" here are relative labels, not warnings.

**7. Watch the heavy stations.**
Stations 24, 26, 51, 36 and 32 each handled 1,820 or more sessions. Station 26 (HSR Layout) and station 51 (Indiranagar) are both in the top-5 load districts, which is where queueing would show up first.
*Action:* add uptime and wait-time tracking at these stations.

**8. Low-use stations are candidates for review, not closure.**
Stations 75, 8, 155 and 72 are about 4–7% below average. Station 151 (Jayanagar) and 181 (Marathahalli) also appear. Their district totals are still healthy.

**9. Top 5 load districts = 35.6% of the network.**
HSR Layout, Indiranagar, Jayanagar, Marathahalli and Rajajinagar hold 23 stations. Any outage planning, grid upgrades or maintenance windows should start there.

---

## Dashboard 3 – Customers & Vehicles

**10. Income tier does not change behaviour or price.**
Mid-Range gives the most revenue (35.9%), then Low-Mid (33.0%) and High (31.1%). Revenue share equals energy share in each tier, with a flat ₹17.38/kWh.
**(interpretation)** High-income customers are not paying a premium, which may be a missed opportunity for premium or reserved charging.

**11. Premium EVs are low frequency, high energy.**
Eight large-battery models (≥ 50 kWh) make 13.3% of sessions but 28.6% of energy, at about 54 kWh per visit. Models with the fewest sessions are MG ZS EV, BYD Atto 3, BMW iX1, Tata Nexon EV Max, Volvo XC40 and Audi e-tron 55.
*Action:* these customers benefit most from fast DC charging near dwell-friendly places such as malls and offices.

**12. Small vehicles drive visit counts.**
Nine small-battery models (≤ 26 kWh) make half of all sessions but 34% of energy, at about 17 kWh per visit. Two-wheeler equivalents (Ather, Ola, Ampere, Hero, Greaves) account for 31.5% of sessions and 19.9% of energy.
*Action:* AC chargers suit this group, and they drive queue pressure through short, frequent visits.

**13. Tata's own models are a quarter of energy.**
The six Tata models listed hold 27.3% of sessions and 25.6% of energy. Best sellers by energy: Punch EV (144,611 kWh) and Nexon EV (135,949).

**14. Mahindra XUV400 and Hyundai Kona lead energy overall.**
Both are mid-size (about 39 kWh) and take about 30 kWh per session, higher than most Tata models.

---

## Dashboard 4 – Investment & ROI

**15. Charger type matters more than anything else.**
Payback is 2.4 years (AC 7.4 kW), 3.4 (AC 22 kW), 6.4 (DC 50 kW) and 10.4 (DC 150 kW). The average is 4.6 years.
**(interpretation)** Ultra-fast chargers are a long-horizon, brand or network-coverage investment, not a short-term financial one. A mix weighted to AC with selective DC hubs looks more defensible on these numbers.

**16. Land lease is a major cost driver for AC sites.**
It is 61% of an AC 7.4 kW site's CAPEX (₹46 of ₹75 lakh) and 47% for AC 22 kW. For DC 150 kW, equipment dominates (45%).
*Action:* land deals have more influence on AC returns than hardware choices.

**17. Demand does not predict ROI.**
The correlation between projected EV demand and 5-year ROI is about 0.09. Indiranagar (3,200 projected) returns 8.3%, Koramangala (2,900) −4.0%, while Bommanahalli (1,200) returns 144.7%.
**(interpretation)** District cost structure (land, charger mix) probably matters more than demand, but the workbook does not break ROI down by district, so this cannot be confirmed from it.

**18. Four districts show negative 5-year ROI.**
Anekal (−7.3%), Dasarahalli (−21.8%), Kengeri (−12.8%) and Koramangala (−4.0%). Byatarayanapura (14.2%), Whitefield (9.5%) and Indiranagar (8.3%) are barely positive.
*Action:* review charger mix and lease terms before further CAPEX in these districts.

**19. Best-return districts.**
Bommanahalli, Marathahalli, Banashankari, Electronic City, HSR Layout and JP Nagar are all above 60%. HSR Layout combines high ROI (65.6%) with high demand (3,100 projected) and high load.

**20. Subsidy helps modestly.**
Average payback improves from 4.61 to 4.34 years after subsidy (about 0.27 years).

---

## Priority Recommendations

| # | Recommendation | Why | Source |
|---|---|---|---|
| 1 | Prioritise HSR Layout, Marathahalli, Banashankari and Electronic City for expansion | High ROI plus solid volume | Dash 1, 4 |
| 2 | Pause or re-plan CAPEX in Anekal, Dasarahalli, Kengeri and Koramangala | Negative 5-year ROI | Dash 4 |
| 3 | Test tiered or time-based pricing | Price per kWh is flat across months and tiers | Dash 1, 3 |
| 4 | Keep AC as the base and add DC selectively for premium EVs | Payback 2.4–3.4 yrs (AC) vs 6.4–10.4 yrs (DC) | Dash 4 |
| 5 | Monitor stations 24, 26, 51, 36, 32 for congestion | Highest session counts | Dash 2 |
| 6 | Confirm Aug and Nov month boundaries | Both look like partial months | Dash 1 |
| 7 | Validate whether session data reflects real usage | Sessions per plug are almost uniform | Dash 1, 2 |
| 8 | Use network-level engagement for customers | Customers use about 10 districts each | Dash 1 |

---

## Caveats

- Revenue and CAPEX figures are read as ₹ (not labelled in the file).
- Monthly figures cover Aug–Nov only, with no year.
- ROI and payback inputs are not shown, so district-level explanations are interpretation.
- Station IDs have no names or locations in the pivots.
