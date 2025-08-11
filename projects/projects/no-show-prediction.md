---
title: Patient No-Show Prediction
---

# Patient No-Show Prediction

Missed appointments create wasted resources, lost revenue, and delays in care.  
This project uses **predictive modeling** to identify which scheduled appointments are at the highest risk of no-show, allowing healthcare teams to take preventive actions like reminders or rescheduling.

---

## Problem
Healthcare providers lose time and money when patients miss scheduled appointments.  
The goal is to **predict high-risk appointments** in advance and act before the no-show happens.

## Data
- **Source:** Kaggle “Medical Appointment No Shows” dataset  
- **Size:** 100k+ appointment records with patient demographics, scheduling data, and attendance outcomes  
- **Key Features:** Age, gender, SMS reminders, scheduling delay, appointment day, neighbourhood

## Outcome *(placeholder until results are finalized)*
- Baseline no-show rate: **—%**  
- Model accuracy: **—%** ROC-AUC  
- Potential uplift: **—% fewer no-shows** if top decile receives interventions

---

## What’s Inside
- **EDA:** Patterns by day of week, lead time, age group, and SMS reminders
- **Feature engineering:** Transformations for date differences, categorical encoding, and risk grouping
- **Models:** Logistic Regression and XGBoost for classification
- **Explainability:** SHAP values to interpret model decisions
- **Simulation:** Cost/benefit analysis of targeted reminders

## Results *(placeholder)*
- High-risk group characteristics: **—**  
- Expected cost savings: **$— per year**  

---

## Next Steps
- Integrate with scheduling system for real-time scoring
- Deploy as part of the **Risk Score App** project

---

**Repo:** (link to GitHub repo)  
**Tech:** Python, Pandas, scikit-learn, SHAP

[← Back to Portfolio Homepage](../index.md)
