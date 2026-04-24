# Time-Series-Forecasting-with-Foundation-Models
The project focuses on benchmarking different approaches using a robust backtesting framework, highlighting how newer LLM-based models compare against traditional methods.

# 🧠 ForecastForge: Time Series Forecasting with Foundation Models

## 📌 Overview

ForecastForge is a time series forecasting project that predicts daily blog traffic using both classical statistical models and modern AI foundation models.

The project focuses on benchmarking different approaches using a robust backtesting framework, highlighting how newer LLM-based models compare against traditional methods.

---

## 🎯 Problem Statement

Predicting website traffic is essential for:

- 📈 Content planning  
- 💰 Revenue optimization  
- ⚙️ Resource allocation  

This project forecasts **daily blog visits for the next 7 days**, incorporating historical patterns and external signals like publishing activity and holidays.

---

## 📊 Dataset

The dataset contains:

- `ds`: Date  
- `y`: Daily traffic (visits)  
- `published`: Whether a new blog was published  
- `is_holiday`: Holiday indicator  

---

## 🔍 Exploratory Analysis

The notebook explores:

- Weekly seasonality (weekday vs weekend trends)  
- Impact of content publishing on traffic spikes  
- Holiday-related traffic patterns  

---

## ⚙️ Approach

### ⏱️ Backtesting Strategy

Instead of a simple train-test split, the project uses:

- Forecast horizon: **7 days**
- Rolling windows: **20**

This simulates real-world forecasting scenarios and ensures reliable evaluation.

---

## 🤖 Models Compared

### 🟢 Baseline
- Seasonal Naive  

### 📈 Classical Model
- AutoARIMA  

### 🤖 AI / Foundation Models
- TimeGPT  
- Chronos  
- Moirai  
- TimesFM  
- Time-LLM  

The notebook compares how these models perform under the same conditions.

---

## 📏 Evaluation Metrics

- MAE (Mean Absolute Error)  
- SMAPE (Symmetric Mean Absolute Percentage Error)  

---

## 📊 Key Findings

- Foundation models capture complex patterns better than traditional models in many cases  
- External features (publishing, holidays) improve predictions  
- Baseline models remain competitive, emphasizing the importance of benchmarking  

---

## 📓 Notebook

The full implementation is available here:

👉 `forecastforge_time_series_forecasting.ipynb`

It includes:

- Data exploration  
- Model training  
- Backtesting  
- Evaluation and visualization  

---

## 💡 Key Learnings

- Importance of time-series-specific validation  
- Trade-offs between classical and modern models  
- Role of external signals in forecasting accuracy  

---

## 🚀 Future Work

Potential improvements:

- Convert notebook into a modular pipeline  
- Add deployment (API / dashboard)  
- Integrate anomaly detection  
- Automate retraining  

---

## 🧰 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)  
- Time Series Models (ARIMA)  
- AI Models (TimeGPT, Chronos, TimesFM, Time-LLM)  
- Jupyter Notebook  

---

## ⭐ Motivation

This project was built to explore how modern AI foundation models can enhance traditional time series forecasting workflows.

---

## 📬 Contact

Feel free to connect if you'd like to discuss this work or collaborate.
