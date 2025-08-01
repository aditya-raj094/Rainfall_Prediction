# 🌧️ Rainfall Prediction in India 

This project uses historical rainfall data across Indian states and districts to classify annual rainfall levels (High or Low) using a machine learning model. The goal is to explore rainfall patterns and predict categories based on monthly inputs.

---

## 📌 Overview

- ✅ **Model Used:** Random Forest Classifier  
- ✅ **Accuracy Achieved:** 94.74%  
- ✅ **Dataset Coverage:** 115 years (1901–2015)  
- ✅ **Tools:** Python, Pandas, Seaborn, Matplotlib, Scikit-learn  
- ✅ **Visualizations:** EDA, state/district rainfall trends, feature importance

---

## ⚙️ Technologies Used

- **Programming Language:** Python  
- **Data Manipulation:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (RandomForestClassifier)  
- **Notebook & App:** Jupyter Notebook

---

## 📂 Dataset

1. `district wise rainfall normal.csv`  
   Contains average monthly rainfall for each Indian district and state.

2. `rainfall in india 1901-2015.csv`  
   Contains historical monthly rainfall data from 1901 to 2015.

📌 *Sources: Indian Meteorological Department (via Kaggle)*

---

## 📊 Features

- **Exploratory Data Analysis (EDA):**
  - Correlation heatmaps
  - Monthly and annual rainfall distribution
  - Rainfall trends over the years
  - District-wise and state-wise comparisons

- **ML Model:**
  - Feature selection: Monthly rainfall (JAN–DEC)
  - Target variable: `RainCategory` (High / Low)
  - Model: Random Forest Classifier
  - Evaluation: Accuracy, confusion matrix, classification report

- **Visual Insights:**
  - Top 10 rainiest districts
  - Boxplots by state
  - Feature importance chart

