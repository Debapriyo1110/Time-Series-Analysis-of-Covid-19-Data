# Time-Series Analysis of COVID-19 Data and Clustering Analysis

## Overview

This project explores the application of statistical and machine learning techniques on real-world datasets. It combines **time-series forecasting** on global COVID-19 case data with **unsupervised learning** on the MNIST handwritten digit dataset.

The main objective of this project is to analyse temporal patterns, forecast future observations, and identify hidden structures in high-dimensional data.

---

## Dataset Used

### 1. WHO COVID-19 Global Daily Dataset

* Daily global COVID-19 case records
* Used for exploratory data analysis and time-series forecasting

### 2. MNIST Handwritten Digit Dataset

* Image dataset of handwritten digits (0–9)
* Used for clustering analysis

---

## Project Workflow

### COVID-19 Time-Series Analysis

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Moving average analysis
* Growth rate analysis
* Seasonal decomposition
* Stationarity testing using ADF test
* ACF and PACF analysis
* Forecasting using:

  * ARIMA
  * SARIMA
  * Holt-Winters Exponential Smoothing
* Model comparison using AIC and BIC

### Clustering Analysis

* K-Means Clustering
* Hierarchical Clustering
* PCA for dimensionality reduction
* Cluster visualization
* Performance evaluation using Macro F1 Score

---

## Results

* Holt-Winters Exponential Smoothing achieved the best forecasting performance based on AIC and BIC values.
* SARIMA performed better than ARIMA by capturing seasonal effects.
* K-Means and Hierarchical Clustering successfully identified meaningful patterns in the MNIST dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* SciPy
* Google Colab

---

## Key Learnings

* Time-series modelling and forecasting
* Model selection and diagnostics
* Seasonal pattern analysis
* Unsupervised machine learning
* Dimensionality reduction using PCA
* Clustering performance evaluation

---

## Future Scope

* Prophet model for forecasting
* LSTM-based forecasting
* DBSCAN clustering
* Advanced anomaly detection

---

## Author

**Debapriyo Bhar**
B.Sc. Major in Statistics
Ramakrishna Mission Residential College (Autonomous)

Summer Internship Project
IDEAS Technology Innovation Hub (TIH), ISI Kolkata
