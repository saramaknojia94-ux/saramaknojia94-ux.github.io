---
title: Patient No-Show Prediction
---

# Patient No-Show Prediction

**Problem:** 1 in 5 patients misses their appointment — wasted 
provider time, scheduling gaps, and downstream care delays. 
Can we predict who won't show up before it happens?

**Data:** 110,527 medical appointments from Brazilian clinics 
via Kaggle — includes demographics, wait time, SMS reminders, 
and appointment outcome.

**Outcome:** XGBoost model achieved 0.721 ROC-AUC and catches 
79% of no-shows before they happen. Wait time was the single 
strongest predictor (SHAP value 0.817).

## What's Inside

- Exploratory analysis uncovering no-show patterns by age, 
  wait time, and SMS status
- Feature engineering — wait days, day of week, age groups
- Logistic Regression baseline vs XGBoost comparison
- SHAP explainability showing WHY each patient is flagged

**Repo:** [github.com/saramaknojia94-ux/no-show-prediction](https://github.com/saramaknojia94-ux/no-show-prediction)

**Tech:** Python, Pandas, scikit-learn, XGBoost, SHAP, Matplotlib

[← Back to Portfolio Homepage](../index.md)
