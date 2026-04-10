> Project for *Distributed Data Analysis and Mining* — M.Sc. Data Science, A.Y. 2025/26

# US Accidents Analysis (2016–2023)

**Course:** Distributed Data Analysis and Mining  
**University:** Università di Pisa — Master's in Data Science & Business Informatics  
**Academic Year:** 2025/26  
**Authors:** Federica Braghin, Nicholas Vannucci, Giulia Mela, Ilenia Fortuna

## Overview

End-to-end data mining project on the US Accidents dataset (~7.7 million records, 49 U.S. states, 2016–2023), developed using PySpark in a distributed computing framework.

## Dataset

- **Source:** Kaggle — US Accidents (2016–2023)
- **Size:** ~7.7 million records, 46 features
- **Features:** temporal, geographical, meteorological, infrastructural

## Tasks Covered

- **Data Preparation:** outlier detection, missing value imputation, feature engineering (weather_grouped, duration_min, Sunrise_Sunset binarization)
- **Clustering:** KMeans vs Bisecting KMeans (k=3), PCA visualization, accident profile characterization
- **Classification:** Decision Tree, Random Forest, Logistic Regression for severity prediction; class imbalance handling (oversampling/undersampling)
- **Regression:** predicting accident duration with Decision Tree and Random Forest
- **XAI:** Gradient Boosted Trees + LIME for local explainability of severity predictions

## Key Results

- Best classifier: Decision Tree (Accuracy 0.83, F1 0.81)
- Best regression model: Decision Tree + categoricals (R² = 0.508)
- Best XAI model: Lightweight GBT (AUC 0.795) with LIME

## Technologies

Python · PySpark · Spark MLlib · HDFS · scikit-learn · LIME · Pandas · Matplotlib

## Presentation

Full methodology, results and analysis are documented in `report.pdf` and `US accidents_presentation.pdf`.
