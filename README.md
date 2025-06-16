# 🧠 MSDS 430 Final Project: APOE4, Cognition, and Alzheimer’s Disease Risk

This project was completed as part of the **MSDS 430: Predictive Modeling** course at Northwestern University. It focuses on the relationship between **APOE4 genetic status**, cognitive performance, and risk for cognitive decline in Alzheimer's Disease.

---

## 🎯 Project Goal

The primary aim is to explore how **genetic risk factors**, particularly **APOE4 carrier status**, relate to cognitive performance at baseline and over time.

Specifically, I sought to determine:

- Whether cognitive performance differs by APOE4 status
- If baseline diagnosis and APOE4 carrier status predict longitudinal decline
- How common APOE4+ status is in the sample (compared to the ~15–25% population prevalence, and 2–5% for homozygous carriers according to the Cleveland Clinic)

---

## 🧪 Methods Used

- Descriptive Statistics & Prevalence Estimation
- Pearson Correlation between Genetic Status and Cognition
- Grouped t-tests comparing cognitive scores across groups
- **Linear Mixed Effects Models** for longitudinal analysis
- Visualizations of decline trajectories over time

---

## 📘 Notebook Summary

### 📂 `Pasaye_Executive_Summary.ipynb`

This notebook includes:

- Data exploration and variable selection
- Model building using `lme4` for mixed effects
- Insights on longitudinal change by APOE4 status
- Executive summary of findings with plots

---

## 📁 Required Dataset (Internal Use Only)

> 🔒 The dataset is not public. It must be stored in a local `data/` folder at the project root.

**Required File**:
- `ADNI_dataset_final.csv`

---

## ▶️ How to Run

1. Place the CSV inside the `data/` directory.
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Pasaye_Executive_Summary.ipynb
