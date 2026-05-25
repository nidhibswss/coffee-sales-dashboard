# 📊 Coffee Sales — Data Analysis

## Overview

This analysis is based on 1,000+ coffee sales orders recorded between **2019 and 2022**, covering customers across the **United States, Ireland, and the United Kingdom**. Sales are measured in **CAD** and broken down by coffee type, month, and year.

---

# 📅 Year-by-Year Analysis

## 2019 — Highest Product Diversity & Strong Overall Activity

- 2019 was the most active and well-distributed year in the dataset, with sales recorded across all four coffee types.

### Key Observations
- **Liberica** dominated yearly performance with two major revenue spikes:
  - May (~$170 CAD)
  - September (~$175 CAD)
- **Excelsa** reached its strongest performance in June (~$135 CAD), its highest point across all analyzed years.
- **Arabica** and **Robusta** maintained moderate but relatively consistent activity throughout the year.
- Sales activity was spread across most months, indicating broader operational consistency and stronger product diversity compared to later years.
- The balanced distribution of sales suggests that 2019 represented the business’s most diversified operational period, with demand spread across multiple product categories rather than concentrated in isolated spikes.

---

## 2020 — Reduced Activity with Significant Revenue Volatility

2020 showed noticeably lower overall activity compared to 2019, with fewer active sales months and reduced product popularity.

### Key Observations
- **Robusta** recorded the single highest monthly revenue value in the entire dataset:
  - April 2020 (~$195 CAD)
- Sales activity was concentrated primarily within: February–May, September–December
- Very limited activity occurred during the mid-year period (June–August).
- **Liberica** and **Excelsa** showed minimal contribution throughout the year.
- The mid-year gap (Jun–Aug) is a complete blackout — zero sales recorded for any coffee type across 3 consecutive months. This is unusual and could indicate a supply issue, data gap, or seasonal closure.


## 2021 — Most Operationally Stable Year

2021 demonstrated the most consistent monthly sales distribution, with activity recorded in all 12 months.

### Key Observations
- **Arabica** peaked in February (~$115 CAD) and maintained relatively steady activity throughout the year, indicating sudden popularity.
- **Liberica** experienced a strong Q4 increase, reaching its yearly peak in October (~$110 CAD).
- Only **Arabica** and **Liberica** recorded sales activity during the year.
- Despite reduced product variety, monthly revenue distribution remained stable with no major inactivity gaps.
- The consistent monthly activity suggests more customers may order the same coffee repeatedly, and improved operational stability compared to previous years, even with fewer actively sold coffee types.


### 2022
- **Incomplete data** — records end in **July 2022**.
- **Robusta** and **Liberica** were the only active types.
- **Liberica** peaked in **June (~$145)**, with Robusta peaking in **March (~$130)**.


---
## Coffee Type Performance

| Coffee Type | Best Year | Peak Month | Peak Sales (CAD) | Overall Activity |
|---|---|---|---|---|
| Arabica | 2021 | Feb 2021 | ~$115 | Moderate |
| Excelsa | 2019 | Jun 2019 | ~$135 | Low |
| Liberica | 2019 | Sep 2019 | ~$175 | High but sporadic |
| Robusta | 2020 | Apr 2020 | ~$195 | Low but high peaks |

---

## Key Findings

- **Liberica** generated the highest individual monthly peaks but had long periods of zero sales — suggesting large but infrequent bulk orders.
- **Robusta** recorded the single highest monthly revenue value (~$195, April 2020) despite being largely inactive in other years.
- **Excelsa** was the weakest and most inconsistent performer across all years.
- **2020** showed the lowest activity overall, with a notable mid-year gap (Jun–Aug) where no sales were recorded.
- **2021** was the healthiest year operationally — consistent monthly sales with no major gaps.
- The overall sales pattern is **spike-driven**, not growth-driven — indicating the business relies on occasional large orders rather than steady recurring revenue.

---

## Limitations
- 2022 data is incomplete — records only run through July, making any full-year comparison with 2019–2021 unreliable.
- Sales values are approximate — figures were read from dashboard line charts, not extracted directly from raw data, so exact numbers may vary slightly.
- No context for gaps — the mid-year blackout in 2020 (Jun–Aug) and other zero-sales months have no explanation in the data. Could be supply issues, data entry gaps, or seasonal closures.
- Missing values in raw data — some customers have no email or phone number recorded, which may affect the completeness of customer-level analysis.
