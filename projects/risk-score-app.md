---
title: Real-Time Risk Score App
---

# Real-Time Patient No-Show Risk Score App

**Problem:** A no-show prediction model is only useful if the right 
people can actually use it. Clinicians and schedulers don't open 
Jupyter notebooks.

**Data:** XGBoost model trained on 110,527 real medical appointments.

**Outcome:** Live Streamlit app deployed on Streamlit Cloud. 
Returns an instant risk score with clinical action recommendation. 
Accessible to anyone with a browser, no technical background needed.

## What's Inside

- Real-time risk scoring that updates instantly as inputs change
- Three risk tiers: Low, Moderate, High; each with a recommended action
- Clean UI built for non-technical clinical staff
- XGBoost model with 0.721 ROC-AUC and 79% no-show recall

**Repo:** [github.com/saramaknojia94-ux/risk-score-app](https://github.com/saramaknojia94-ux/risk-score-app)

**Live App:** [sara-noshow-risk.streamlit.app](https://sara-noshow-risk.streamlit.app)

**Tech:** Python, Streamlit, XGBoost, pandas, scikit-learn

[← Back to Portfolio Homepage](../index.md)
