---
title: Hospital Readmission Dashboard
---

# Hospital Readmission Dashboard

Reducing avoidable 30‑day readmissions is a high‑leverage way to cut costs and improve outcomes.  
This project builds an analytics workflow and executive dashboard that surfaces **where, why, and for whom** readmissions spike so leaders know exactly where to intervene.

---

## Problem
Identify the top drivers of 30‑day readmissions and quantify where targeted action (e.g., discharge planning, follow‑ups) can reduce rates and cost.

## Data
- **Source:** CMS Hospital Readmissions Reduction Program / Hospital Compare (public)
- **Grain:** Facility-, condition-, and period‑level KPIs (readmission rate, denominator, confidence)
- **Augments (optional):** Community demographics (ACS), bed counts, staffing levels

## Outcome *(placeholder until analysis is complete)*
- Baseline readmission rate: **—%** (national **—%**)  
- Estimated reduction opportunity with targeted focus: **— to —%** (~**$—** cost impact)

---

## What’s inside
- **SQL transformations:** CTEs, window functions for rates, YoY deltas, ranking
- **Feature engineering:** Condition groups, peer benchmarks, risk bands
- **Dashboard:** KPIs, trend lines, peer comparison, drill‑downs
- **Narrative:** “Top 5 levers” for operational action

## Results *(placeholder)*
- Top conditions by excess readmission: **—**  
- Facilities in 90th percentile risk band: **—**  
- Recommended focus units/regions: **—**

## Next steps
- Add patient‑level data (if available) for finer segmentation  
- Monitor post‑discharge follow‑up adherence

---

**Repo:** (link here)  
**Live dashboard:** (Tableau/Power BI link here)  
**Tech:** SQL, Pandas, Tableau/Power BI

[← Back to Portfolio Homepage](../index.md)
