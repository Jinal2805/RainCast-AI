
# 🌧️ RainCast AI: Rainfall Pattern Prediction in Gujarat using LSTM

> A machine learning project using Long Short-Term Memory (LSTM) networks to analyze and forecast rainfall patterns in the Saurashtra and Kutch regions of Gujarat, India.

---

## 🚀 Project Overview

Agriculture in India relies heavily on monsoon rains, especially in Gujarat, where over 70% of the farmland is rain-fed. Due to increasing climate variability, traditional statistical models are proving inadequate in predicting rainfall accurately.

**RainCast AI** introduces an advanced LSTM-based time series forecasting model trained on over a century of rainfall data from the Indian Meteorological Department (1901–2015) to improve the accuracy of rainfall predictions.

---

## 🎯 Objectives

- Analyze long-term rainfall trends and variability in Gujarat.
- Compare traditional statistical forecasting models (ARIMA) with deep learning models (LSTM).
- Provide insights into changing rainfall patterns to support adaptive agriculture and water resource planning.

---

## 🧠 Methodology

### 📊 Dataset
- Source: Indian Meteorological Department (IMD)
- Region Focus: Saurashtra & Kutch (Gujarat)
- Duration: 1901–2015
- Features: Monthly rainfall data

### 🧪 Model Architecture
- **Model:** LSTM Neural Network
- **Layers:** 2 LSTM layers (50 units each), Dropout layers for regularization
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam
- **Training Technique:** Early Stopping to prevent overfitting
- **Data Scaling:** MinMaxScaler

### 📈 Metrics Comparison

| Metric        | ARIMA Model | LSTM Model |
|---------------|-------------|------------|
| RMSE          | 0.085       | 0.045      |
| MAE           | 0.23        | 0.17       |
| R² Score      | 0.15        | 0.65       |

---

## 🌦️ Key Findings

- **LSTM outperformed** ARIMA in capturing complex, non-linear rainfall patterns.
- Identified a **decline in total rainfall** and **increased variability** in the target regions.
- Findings suggest a **need to adjust crop calendars** and improve irrigation planning due to delayed and erratic monsoon behavior.

---

---

## 👩‍💻 Team Member

- **Tandel Kruti** 
---

## 📌 Future Scope

- Extend model to real-time rainfall forecasting using satellite feeds.
- Integrate weather API for live predictions.
- Build a web dashboard for farmers and policymakers.

---



## ⭐️ Acknowledgements

- Indian Meteorological Department (IMD) for the dataset  
- Inspiration from climate-resilient agriculture research




