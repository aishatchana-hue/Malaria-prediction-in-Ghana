# Malaria-prediction-in-Ghana
https://colab.research.google.com/gist/aishatchana-hue/070d576c9425d2fc9dc3f3c23e4125eb/capstone-project-submit.ipynb
# 🦟 Predicting Malaria Incidence in Ghana - Capstone Project
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/aishatchana-hue/070d576c9425c2b3e9b1a2c3d4e5f6)
[![Model](https://img.shields.io/badge/Model-Random%20Forest-green)](https://scikit-learn.org)
[![Status](https://img.shields.io/badge/Status-Completed-success)](https://github.com/aishatchana-hue/Malaria-prediction-in-Ghana)
## 📋 Project Overview
Malaria remains a major public health challenge in Ghana, with transmission varying by ecological zone. This project predicts monthly malaria risk and incidence count using environmental and historical data to support early intervention.
**Problem:** No automated system for early warning by zone/month
**Goal:** Enable Ghana Health Service to prioritize interventions before peak seasons.
### 🌍 Study Area
- **Forest Zone:** High perennial transmission
- **Coastal Zone:** Moderate seasonal transmission  
- **Savannah Zone:** Highly seasonal, rainy season peaks
### 📊 Dataset
- **Source:** PLOS ONE - Malaria Incidence in Ghana 2008-2016
- **Features:** Year, Month, Ecological Zone, Rainfall, Temperature, Previous Cases
- **Target:** Risk Level (High/Medium/Low) + Incidence Count
- **Size:** 324 monthly records (3 zones x 108 months)

### ⚙️ Methodology
1. Data Collection -> PLOS CSV
2. Preprocessing -> Handle missing, encode zones
3. EDA -> Seasonal trends by zone
4. Model -> Random Forest Classifier & Regressor
5. Evaluation -> Accuracy, Confusion Matrix, Correlation
6. Deployment -> Risk prediction tool
### 📈 Results
- **Classification Accuracy:** 89%
- **Key Finding:** Rainfall is the strongest predictor in Savannah zone
- **Impact:** 2-month early warning possible for high-risk periods
### 🚀 How to Use
1. Open notebook in Colab (click badge above)
2. Run all cells
3. Input: Zone, Month, Rainfall to get Risk prediction
### 👩🏾‍💻 Author
**Aisha** - WOMEN TECHSTERS SPRINT|WTS/2026/184| DATA SCIENCE
Capstone Project 2026

