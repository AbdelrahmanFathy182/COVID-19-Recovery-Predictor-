# COVID-19 Outcome Predictor 🏥🤖

A machine learning system to predict patient recovery/mortality from COVID-19 symptoms and demographic data, based on WHO guidelines.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-brightgreen)

## 📌 Overview
- Predicts COVID-19 outcomes (recovered/deceased) using **5 ML classifiers**.
- Processes WHO-standardized data (14 variables including symptoms, age, location).
- Optimizes hyperparameters and evaluates models using **precision, recall, F1-score, and ROC-AUC**.

## 🛠️ Tech Stack
- **Languages**: Python 3
- **Libraries**: 
  - `pandas` (data cleaning)
  - `scikit-learn` (KNN, SVM, Logistic Regression, Naïve Bayes, Decision Trees)
  - `matplotlib/seaborn` (visualizations)
- **Tools**: Jupyter Notebook (or VS Code/PyCharm)

## 📂 Dataset
- **Source**: Preprocessed CSV (`data.csv`) containing:
  - 14 variables (e.g., `Country`, `Age`, `Symptoms`, `Visited_Wuhan`, `Result`).
  - Time-series data from Jan 2020 (cumulative cases).
- **Sample Data**:
  ```csv
  Country,Location,Age,Gender,Visited_Wuhan,From_Wuhan,...,Result
  China,Hubei,50-60,Male,1,1,...,0
