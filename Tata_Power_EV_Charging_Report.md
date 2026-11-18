# Tata Power EV Charging – Performance Report

**Source workbook:** `Tata_Power_Cleaned.xlsx` (Dashboards 1–4, supported by pivot sheets Sheet1–Sheet4)
**Scope:** 114,000 charging sessions · 8,000 customers · 65 stations · 390 plugs · 18 Bengaluru districts · Aug–Nov
**Currency:** the workbook does not label it; figures are read as Indian Rupees (₹). 1 Lakh = 100,000.

---

## 1. Executive Summary

| KPI | Value |
|---|---|
| Total sessions | 114,000 |
| Total energy delivered | 2,859,772 kWh (≈ 2.86 GWh) |
| Total revenue | ₹4,96,93,947 (≈ ₹4.97 crore) |
| Avg revenue per session | ₹435.91 |
| Avg energy per session | 25.09 kWh |
| Effective price | ≈ ₹17.38 per kWh |
| Sessions per customer | 14.25 |
| kWh per customer | 357.47 |
| Revenue per customer | ₹6,211.74 |
| Sessions per station | ≈ 1,754 |
| Sessions per plug | ≈ 292 |
| Avg kWh per station | ≈ 43,996 |
| Stations per district | ≈ 3.6 |

**Headline findings**

1. Demand grew strongly from Aug to Sep and then flattened into Oct. Nov is far lower, which most likely reflects a partial month.
2. Revenue tracks energy almost perfectly (flat ≈ ₹17.38/kWh), so growth in revenue comes from volume, not price or mix.
3. Usage is spread very evenly across stations and plugs. There is no strong hotspot or dead station.
4. Large-battery premium EVs are 13% of sessions but 29% of energy.
5. Investment returns vary far more than demand does. DC ultra-fast chargers pay back in about 10.4 years against 2.4 years for AC 7.4 kW.
6. Four districts show negative 5-year ROI: Anekal, Dasarahalli, Kengeri and Koramangala.

---

## 2. Dashboard 1 – Charging Demand & Revenue

*Charts: Overall Charging Demand Over Time · Revenue Aligned With Energy Consumption · Charging Demand vs Infrastructure Capacity by District · No. of Customers vs Energy Consumption by District*

### 2.1 Demand over time

| Month | Sessions | Revenue (₹) | kWh | ₹/kWh | ₹/session |
|---|---|---|---|---|---|
| Aug | 26,820 | 1,17,07,687 | 673,452 | 17.38 | 436.53 |
| Sep | 38,604 | 1,67,68,683 | 965,758 | 17.36 | 434.38 |
| Oct | 39,606 | 1,73,04,062 | 995,386 | 17.38 | 436.91 |
| Nov | 8,970 | 39,13,516 | 225,176 | 17.38 | 436.29 |
| **Total** | **114,000** | **4,96,93,947** | **2,859,772** | **17.38** | **435.91** |

- Aug to Sep: sessions up 43.9%, revenue up 43.2%.
- Sep to Oct: sessions up 2.6%, revenue up 3.2%. Growth has slowed sharply.
- Nov has about a quarter of Oct's sessions. Aug is also likely to be an incomplete month. Sep and Oct are the cleanest comparison.

### 2.2 District capacity vs demand

| District | Customers | Sessions | Plugs | Sessions/plug | kWh | Share of kWh |
|---|---|---|---|---|---|---|
| Indiranagar | 5,290 | 8,901 | 30 | 296.7 | 222,525 | 7.78% |
| Rajajinagar | 5,423 | 8,867 | 30 | 295.6 | 221,575 | 7.75% |
| Jayanagar | 5,287 | 8,664 | 30 | 288.8 | 217,880 | 7.62% |
| HSR Layout | 4,702 | 7,127 | 24 | 297.0 | 177,725 | 6.21% |
| Marathahalli | 4,680 | 7,024 | 24 | 292.7 | 177,539 | 6.21% |
| Electronic City | 4,675 | 7,127 | 24 | 297.0 | 176,105 | 6.16% |
| JP Nagar | 4,649 | 6,988 | 24 | 291.2 | 175,454 | 6.14% |
| Koramangala | 4,587 | 6,957 | 24 | 289.9 | 174,852 | 6.11% |
| Whitefield | 4,665 | 6,934 | 24 | 288.9 | 174,600 | 6.11% |
| Banashankari | 4,597 | 6,896 | 24 | 287.3 | 173,554 | 6.07% |
| Bommanahalli | 3,879 | 5,285 | 18 | 293.6 | 133,892 | 4.68% |
| Yelahanka | 3,880 | 5,325 | 18 | 295.8 | 133,320 | 4.66% |
| Kengeri | 3,859 | 5,290 | 18 | 293.9 | 132,419 | 4.63% |
| Hebbal | 3,813 | 5,210 | 18 | 289.4 | 130,521 | 4.56% |
| Rajarajeshwari Nagar | 3,821 | 5,184 | 18 | 288.0 | 129,872 | 4.54% |
| Dasarahalli | 3,824 | 5,214 | 18 | 289.7 | 129,512 | 4.53% |
| Byatarayanapura | 2,881 | 3,551 | 12 | 295.9 | 90,263 | 3.16% |
| Anekal | 2,817 | 3,456 | 12 | 288.0 | 88,165 | 3.08% |

- Districts fall into four capacity bands: 30, 24, 18 and 12 plugs. Energy volume follows the band almost exactly.
- Sessions per plug range only from 287 to 297 (a spread of about 1.2%).
- The three 30-plug districts (Indiranagar, Rajajinagar, Jayanagar) deliver 23.2% of all energy.

### 2.3 Customers vs energy

- Distinct customers per district sum to 77,329, against 8,000 customers overall. The average customer therefore charged in about 9.7 districts. District customer counts overlap and must not be added together.
- Energy per customer in the district is highest in Indiranagar (42.1 kWh), Jayanagar (41.2) and Rajajinagar (40.9). It is lowest in Byatarayanapura and Anekal (31.3).

---

## 3. Dashboard 2 – Station Utilisation & Load

*Charts: Top 5 Districts Load Distribution · Top 10 Overutilised Stations · Top 10 Underutilised Stations · Available Charging Plugs vs Total Charging Sessions by District*

### 3.1 Top 5 districts by load

| District | Stations shown | Sessions | kWh |
|---|---|---|---|
| HSR Layout | 4 | 7,127 | 177,725 |
| Indiranagar | 5 | 8,901 | 222,525 |
| Jayanagar | 5 | 8,664 | 217,880 |
| Marathahalli | 4 | 7,024 | 177,539 |
| Rajajinagar | 5 | 8,867 | 221,575 |
| **Combined** | **23 stations** | **40,583** | **1,017,244** |

These five districts hold 35.6% of all sessions and energy.

### 3.2 Station extremes

| Rank | Most used (station ID: sessions) | Least used (station ID: sessions) |
|---|---|---|
| 1 | 24: 1,862 | 75: 1,635 |
| 2 | 26: 1,856 | 8: 1,664 |
| 3 | 51: 1,839 | 155: 1,677 |
| 4 | 36: 1,821 | 72: 1,680 |
| 5 | 32: 1,820 | 151: 1,683 |
| 6 | 147: 1,818 | 181: 1,695 |
| 7 | 196: 1,810 | 76: 1,697 |
| 8 | 7: 1,805 | 57: 1,703 |
| 9 | 63: 1,800 | 182: 1,703 |
| 10 | 25: 1,798 | 185: 1,704 |

- Average is ≈ 1,754 sessions per station.
- The busiest station is about 6% above average and the quietest about 7% below.
- The gap between busiest and quietest is about 14%. This is a mild imbalance, not a capacity crisis.

### 3.3 Plugs vs sessions

- Every station has 6 plugs (390 plugs / 65 stations).
- Plug count explains energy almost completely (correlation ≈ 0.999 between plugs and kWh by district).

---

## 4. Dashboard 3 – Customers, Income Tiers & EV Models

*Charts: Income-Tier Wise Revenue · Income-Tier Wise Energy · Top EV Models' Energy Consumption · EV Models With the Lowest Sessions*

### 4.1 Income tiers

| Tier | Revenue (₹) | Revenue share | kWh | Energy share | ₹/kWh |
|---|---|---|---|---|---|
| Mid-Range | 1,78,52,747 | 35.9% | 1,027,509 | 35.9% | 17.37 |
| Low-Mid | 1,63,96,044 | 33.0% | 943,603 | 33.0% | 17.38 |
| High | 1,54,45,156 | 31.1% | 888,659 | 31.1% | 17.38 |

- The three tiers are close in size. Mid-Range leads by about 5 points.
- Price per kWh is identical across tiers, so no tier-based pricing is visible.

### 4.2 EV models by energy

**Top 5 by energy:** Mahindra XUV400 EC Pro (157,676 kWh) · Hyundai Kona Electric (156,561) · Tata Punch EV (144,611) · Citroen eC3 (144,204) · Ampere Nexus (137,595).

**Fewest sessions:** MG ZS EV Exclusive (1,625) · BYD Atto 3 (1,651) · BMW iX1 (1,733) · Tata Nexon EV Max (1,803) · Volvo XC40 Recharge (1,906) · Audi e-tron 55 (1,937).

| Segment | Models | Share of sessions | Share of energy | kWh/session |
|---|---|---|---|---|
| Large-battery (≥ 50 kWh) | 8 | 13.3% | 28.6% | 53.8 |
| Small-battery (≤ 26 kWh) | 9 | 50.0% | 34.1% | 17.1 |
| All Tata models listed (Nexon, Nexon Max, Punch, Tiago, Tigor, Tigor Base) | 6 | 27.3% | 25.6% | 23.5 |

- Premium models charge rarely but take about 54 kWh each time.
- Small-battery vehicles and two-wheeler equivalents are frequent, short visits (11–18 kWh).
- Average energy per session is typically around 80% of battery capacity (range 58% for Audi e-tron 55 to 98% for MG Comet, e2o Plus and Nexon EV Max).

---

## 5. Dashboard 4 – Investment, Payback & ROI

*Charts: Top 10 Districts With Highest ROI · Payback Period for Different Charging Setups · Cost Breakdown by Charging Setup · District-wise EV Demand vs 5-Year ROI*

### 5.1 Portfolio averages

| Metric | Value |
|---|---|
| Avg total CAPEX | ₹142.06 lakh |
| Avg annual revenue | ₹47.23 lakh |
| Avg annual EBITDA | ₹33.05 lakh |
| Avg payback | 4.61 years |
| Avg payback after subsidy | 4.34 years |
| Avg 5-year ROI | 41.4% |

### 5.2 Charger type economics

| Setup | Payback (yrs) | Civil | Electrical | Land lease | Equipment | Total CAPEX (₹ lakh) |
|---|---|---|---|---|---|---|
| AC Level-2 (7.4 kW) | 2.38 | 5.06 | 3.97 | 45.96 | 19.83 | 74.8 |
| AC Level-2 (22 kW) | 3.38 | 10.73 | 9.10 | 50.20 | 36.46 | 106.5 |
| DC Fast (50 kW) | 6.44 | 28.88 | 24.21 | 49.26 | 81.05 | 183.4 |
| DC Ultra-Fast (150 kW) | 10.39 | 63.63 | 57.17 | 84.53 | 169.71 | 375.0 |

CAPEX mix: land lease is 61% of an AC 7.4 kW site and 23% of an ultra-fast site. Equipment is 27% of AC 7.4 kW and 45% of ultra-fast.

### 5.3 District ROI and projected EV demand

| District | Projected EV demand | Avg 5-yr ROI |
|---|---|---|
| Bommanahalli | 1,200 | 144.7% |
| Marathahalli | 1,700 | 82.4% |
| Banashankari | 2,500 | 80.2% |
| Electronic City | 1,100 | 75.0% |
| HSR Layout | 3,100 | 65.6% |
| JP Nagar | 1,300 | 62.8% |
| Jayanagar | 3,600 | 59.1% |
| Yelahanka | 2,600 | 54.4% |
| Rajajinagar | 3,400 | 54.0% |
| Rajarajeshwari Nagar | 800 | 46.9% |
| Hebbal | 2,000 | 34.2% |
| Byatarayanapura | 600 | 14.2% |
| Whitefield | 2,000 | 9.5% |
| Indiranagar | 3,200 | 8.3% |
| Koramangala | 2,900 | −4.0% |
| Anekal | 700 | −7.3% |
| Kengeri | 1,500 | −12.8% |
| Dasarahalli | 1,000 | −21.8% |

- Projected demand and ROI are almost uncorrelated (r ≈ 0.09).
- High-demand districts such as Indiranagar (3,200) and Koramangala (2,900) have weak or negative ROI.
- Low-demand Bommanahalli (1,200) has the best ROI.

---

## 6. Data Notes & Limitations

- Dashboards hold charts only. All numbers here come from the pivot tables behind them.
- Dashboard 2 station charts use station IDs only; no station names or locations are in the pivots.
- Month columns are Aug–Nov with no year or day-level data, so seasonality cannot be assessed.
- The pivot tables are built on a data model of about 13 MB that the file does not expose as a sheet. Row-level data was not reviewed.
- The workbook does not show how ROI, payback or CAPEX were calculated, or whether they relate to existing or planned sites.
