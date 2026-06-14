# Week 3 – Unsupervised Learning on Country Data

**Celebal Technologies Data Science Internship**

---

## Objective
Develop an end-to-end Customer Intelligence System using clustering (K-Means, DBSCAN) and PCA to segment countries based on socioeconomic indicators and generate actionable insights.

---

## Dataset
- **Name:** Country Socioeconomic Data (HELP International)
- **Source:** [Kaggle](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
- **Size:** 167 countries × 9 features

## Features
| Feature | Description |
|---|---|
| child_mort | Child mortality rate |
| exports | Exports as % of GDP |
| health | Health spending as % of GDP |
| imports | Imports as % of GDP |
| income | Net income per person |
| inflation | Annual inflation rate |
| life_expec | Life expectancy |
| total_fer | Fertility rate |
| gdpp | GDP per capita |

---

## Models Used
- **K-Means** – optimal k=3 selected via Elbow Method
- **DBSCAN** – density-based clustering (eps=1.5, min_samples=5)
- **PCA** – 2D visualization (PC1=46%, PC2=17.2%)

---

## Key Results
- Cluster 0 → Developed nations (high income, low mortality)
- Cluster 1 → Underdeveloped nations (high mortality, low income) — priority for aid
- Cluster 2 → Transitional/developing economies

---

## Files
- `week3_Manish.ipynb` – main notebook

---

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
