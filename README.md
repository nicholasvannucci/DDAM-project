# US Accidents Analysis (2016–2023)
**Distributed Data Analysis and Mining | MSc in Data Science 
and Business Informatics @ UniPi | A.Y. 2025–2026**

## Overview
End-to-end data mining project on the US Accidents dataset 
(~7.7 million records, 49 U.S. states, 2016–2023), developed 
using PySpark in a distributed computing framework.

## Dataset
- Source: Kaggle — US Accidents (2016–2023)
- Size: ~7.7 million records, 46 features
- Features: temporal, geographical, meteorological, 
  infrastructural

## Tasks covered
- **Data Preparation**: outlier detection, missing value 
  imputation, feature engineering (weather_grouped, 
  duration_min, Sunrise_Sunset binarization)
- **Clustering**: KMeans vs Bisecting KMeans (k=3), 
  PCA visualization, accident profile characterization
- **Classification**: Decision Tree, Random Forest, 
  Logistic Regression for severity prediction; 
  class imbalance handling (oversampling/undersampling)
- **Regression**: predicting accident duration with 
  Decision Tree and Random Forest
- **XAI**: Gradient Boosted Trees + LIME for 
  local explainability of severity predictions

## Key Results
- Best classifier: Decision Tree (Accuracy 0.83, F1 0.81)
- Best regression model: Decision Tree + categoricals 
  (R² = 0.508)
- Best XAI model: Lightweight GBT (AUC 0.795) with LIME

## Technologies
Python · PySpark · Spark MLlib · HDFS · 
scikit-learn · LIME · Pandas · Matplotlib

## Repository structure
notebooks/
├── Preparation_part1.ipynb
├── Preparation_part2.ipynb
├── PLOT_iniziali.ipynb
├── Clustering_US.ipynb
├── Classification_US.ipynb
├── Regression_US.ipynb
└── XAI_US.ipynb
report.pdf

## Authors
- Nicholas Vannucci
- Federica Braghin
- Giulia Mela
- Ilenia Fortuna
```

---

### 💼 Descrizione per LinkedIn (sezione Progetti)

**Titolo:** `US Accidents Big Data Analysis — Distributed Data Mining Project`

**Descrizione:**
```
End-to-end distributed data mining project on the US Accidents 
dataset (~7.7M records) using PySpark. Covered the full pipeline: 
data cleaning and feature engineering, clustering (KMeans), 
severity classification (Decision Tree, Random Forest, Logistic 
Regression), regression for accident duration prediction, and 
explainability (GBT + LIME). Addressed real-world challenges 
including class imbalance, outlier correction, and distributed 
processing at scale.

Skills: Python · PySpark · Spark MLlib · Machine Learning · 
XAI · LIME · Big Data
