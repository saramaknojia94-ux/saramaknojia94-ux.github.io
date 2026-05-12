---
title: Medicare Claims Analytics Dashboard
---

# Medicare Claims Analytics Dashboard

**Problem:** Medicare spends billions annually but the patterns 
behind those payments sucha as which specialties cost the most, how much 
providers actually get paid vs what they bill, and which specialties 
serve the sickest patients, aren't visible without digging into 
the raw claims data.

**Data:** CMS Medicare Physician and Other Practitioners dataset (2023)- 10,000+ real provider records pulled via CMS public API.

**Outcome:** Identified that no specialty receives more than 40 cents 
on the dollar from Medicare. Registered Dietitians serve the most 
diabetic patients (75%) but receive only $5K avg payment vs Vascular 
Surgery's $532K.

## What's Inside

- Real CMS Medicare data pulled via public API; no clean toy dataset
- Specialty-level analysis of submitted charges vs actual Medicare payments
- Payment ratio analysis showing how much Medicare pays per dollar billed
- Chronic disease burden by specialty- diabetes, hypertension, depression
- Geographic variation in Medicare payments across states
- Interactive Tableau dashboard with KPI views and filters

**Repo:** [github.com/saramaknojia94-ux/insurance-analytics-dashboard](https://github.com/saramaknojia94-ux/insurance-analytics-dashboard)

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/sara.maknojia/viz/MedicareClaimsAnalytics-SaraMaknojia/MedicareDashboard)

**Tech:** Python, pandas, requests, Matplotlib, Tableau

[← Back to Portfolio Homepage](../index.md)
