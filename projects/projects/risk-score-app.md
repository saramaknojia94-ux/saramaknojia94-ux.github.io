---
title: Real-Time Risk Score App
---

# Real‑Time Risk Score App

Frontline users need fast, interpretable predictions — not notebooks.  
This lightweight **Streamlit app** serves real‑time risk scores from the trained model (No‑Show Prediction project) with **clear explanations** so staff can act with confidence.

---

## Problem
Provide an easy way for schedulers/clinicians to score upcoming appointments and see **why** a case is high risk, enabling actions like SMS reminders or rescheduling.

## Data
- **Inputs:** Appointment attributes (lead time, weekday, age group, prior no‑shows, etc.)
- **Model:** Trained on the Medical Appointment No Shows dataset; exported as a serialized artifact

## Outcome *(placeholder until deployment)*
- In‑app scoring latency: **— ms**  
- Uplift simulation: **—%** fewer no‑shows with reminders to top‑risk decile

---

## What’s inside
- **Streamlit UI:** clean form inputs + results panel
- **Model serving:** scikit‑learn pipeline loaded from `.pkl`
- **Explainability:** SHAP values / feature attributions per prediction
- **(Optional)** PDF export of case summary and recommended actions
- **(Optional)** FastAPI endpoint for programmatic access

## How to run locally
```bash
pip install -r requirements.txt
streamlit run app.py
