# 🏢 DataFest 2025 – Commercial Real Estate Leasing Analysis

This repository contains our project submission for **DataFest 2025**, a national analytics competition hosted by the **American Statistical Association (ASA)** and co-organized by **Western Illinois University**, with participation from teams representing **8+ universities across the U.S.**.

---

## 📊 Challenge Overview

Participants were given access to a proprietary real estate dataset provided by **SitusAMC** (data partner), containing commercial lease records across multiple years, industries, building types, and U.S. regions.

The goal: **extract meaningful insights** on leasing behavior across time (especially around COVID-19) and build predictive models for lease classification and rent estimation.

---

## 💼 Project Objectives

- Track leasing trends across Class A and Class O buildings
- Compare CBD vs suburban leasing volumes
- Quantify the rise of subleasing and lease renewals
- Classify lease type (New, Renewal, Other) using XGBoost
- Predict rental pricing using feature-driven models

---

## 🔍 Key Insights

- **Class A leases rebounded faster** post-COVID than Class O
- **CBD leasing showed sharper volatility** than suburban markets
- **Subleasing grew over 10x** after 2019, led by tech and finance sectors
- **XGBoost classifier** achieved strong performance (Precision ≈ 0.86 for new leases)
- **Top predictors** of rent: ZIP code, sublet flag, market, building area

---

## 🧠 Methods & Tools

- Python (Pandas, Seaborn, XGBoost, Scikit-learn)
- STL Decomposition for time series trend & seasonality
- Kruskal-Wallis and ANOVA for statistical testing
- Feature importance via gain metrics and visualizations

---
