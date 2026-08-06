# Codveda Data Analytics Internship (2026)

This repository contains my completed tasks for the Codveda Technologies Data Analyst Internship.

---

## 🟢 Level 1: Basic level

* **Task 1: Data Preprocessing & Cleaning** (`level 1 data cleaning.ipynb`)
  * Handled missing values, formatted data, and prepared the Iris dataset for analysis (`level_1 data cleaned.csv`).
* **Task 3: Basic Data Visualization** (`level_1 data visualization.ipynb`)
  * Created customized bar plots, scatter plots, and line charts (`iris_bar.png`, `iris_line.png`, `iris_scatter.png`) using **Matplotlib** and **Seaborn**.

---

## 🟡 Level 2: Intermediate level

* **Task 2: Time Series Analysis** (`level_2 time series analysis(task 2).ipynb`)
  * Performed time-series visualization on stock prices (`2) Stock Prices Data Set.csv`).
  * Plotted 7-day and 30-day moving averages to track price trends.
  * Decomposed the series into **Trend**, **Seasonality**, and **Residuals** using `statsmodels`.

* **Task 3: Clustering Analysis (K-Means)** (`level_2 clustering analysis(task 3).ipynb`)
  * Standardized features using `StandardScaler` for fair distance metrics on the Iris dataset.
  * Applied the **Elbow Method** to identify $k = 3$ as the optimal number of clusters.
  * Plotted 2D cluster scatter plots complete with centroid markers (`X`).

  ---

🔴 Level 3: Advanced level

* Task 1: Predictive Modeling (`level_3 predictive modelling (task 1).ipynb`)
  * Merged and preprocessed telecom customer churn datasets (`churn-bigml-80.csv`, `churn-bigml-20.csv`).
  * Engineered features using One-Hot Encoding and scaled numerical features with `StandardScaler`.
  * Optimized model parameters using `GridSearchCV` and saved confusion matrix visualization (`churn_confusion_matrix.png`).

* Task 3: Sentiment Analysis (`level_3 sentiment analysis (task 3).ipynb`)
  * Preprocessed raw text from `3) Sentiment dataset.csv` using NLTK for regex cleaning, tokenization, stopword removal, and lemmatization.
  * Extracted text polarity scores and assigned sentiment classes using `TextBlob`.
  * Visualized class distribution (`sentiment_distribution.png`) and text frequency metrics with WordCloud (`sentiment_wordcloud.png`).

---

## 🛠️ Tools Used
* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-Learn
* Statsmodels
