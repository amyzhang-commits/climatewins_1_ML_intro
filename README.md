# 🌦️🌎🌡️ClimateWins (part 1): Weather & Climate Change ML Analysis
---

## Overview

ClimateWins partnered with this project to explore the use of machine learning in classifying “pleasant” vs. “unpleasant” weather conditions across mainland Europe. Leveraging over 60 years of daily data from the ECA&D initiative (18 weather stations, 1960–2022), the scripts perform data cleaning, ethical/bias auditing, preprocessing, and multi-model training.

**Key Steps:**
- Structured data audit for bias and missingness
- Feature engineering for weather metrics
- Applied: Linear Regression, Decision Tree, K-Nearest Neighbors, Artificial Neural Networks

---

## Fast Highlights

- **Ethics First:** Bias review identified coverage gaps (some countries missed), incomplete features, and subjectivity in “pleasant” labels—each flagged in pre-model analysis.
- **Models Compared:** Decision Trees, KNN, and Multi-layer Perceptrons were evaluated. Decision Trees perfectly reproduced label rules; neural nets generalized well, especially as data complexity grew.
- **Key Finding:** When data is simple/deterministic, interpretable models (Decision Trees) suffice; as weather definitions and datasets evolve, MLPs become more robust.
- **Bias & Expansion:** Recommendations include better regional representation, clarified target variables, and richer, more resilient models to combat data drift over time.

---

## Practical Impact

- Early-stage, interpretable ML gives actionable insights on clean, structured data.
- Further accuracy and equity depend on moving toward richer, more diverse datasets—especially when expanding to underrepresented geographies and evolving climate norms.

---

## Tech & Skills

**Tools:** Python, pandas, scikit-learn, matplotlib  
**Focus:** Climate data analysis, bias mitigation, model transparency, ethical ML  
**Audience:** Data scientists, ML researchers, environmental advocates

---

*For full methods, datasets, and visuals, see detailed Jupyter notebooks in this repo.*
