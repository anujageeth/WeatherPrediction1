# 🌤️ Weather Prediction Using LSTM

This project implements a Long Short-Term Memory (LSTM) deep learning model to predict **daily mean temperature** based on a multivariate time-series weather dataset collected from 30 cities across **Sri Lanka (2010–2023)**.

---

## 📌 Project Overview

The goal of this project is to forecast the **mean temperature at 2 meters** using past weather data. The dataset includes various meteorological parameters such as precipitation, wind speed, daylight hours, sunrise/sunset times, and more.

The entire machine learning pipeline is implemented from scratch in Python using **TensorFlow/Keras** for model building and **pandas**, **NumPy**, **matplotlib**, and **seaborn** for data analysis and visualization.

---

## 🔧 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data processing and manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **Scikit-learn** – Preprocessing and evaluation metrics  
- **TensorFlow / Keras** – LSTM model implementation  

---

## 🧠 Features & Workflow

- 🔍 **Exploratory Data Analysis (EDA)**  
- 🧹 **Missing value handling** and **outlier detection**
- 🛠️ **Feature engineering** (including daylight hours and cyclical seasonal features)
- 📈 **Time-series sequencing** for LSTM input  
- 🧠 **2-layer LSTM model** with dropout for regularization  
- 📊 **Evaluation using MSE, RMSE, MAE, R²**  
- 📉 Visualizations for **training history** and **actual vs predicted results**

---

## 📊 Model Performance

| Dataset     | MAE (°C) | RMSE (°C) | R² Score |
|-------------|----------|-----------|----------|
| Training    | 0.2696   | 0.3512    | 0.9485   |
| Validation  | 0.3490   | 0.4549    | 0.9084   |
| Test        | 0.3838   | 0.5201    | 0.9661   |

---

## 📁 Dataset

The dataset was sourced from **Kaggle** and includes daily weather records across Sri Lanka from **January 2010 to January 2023**.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-prediction-lstm.git
   cd weather-prediction-lstm

1. Run the notebook in Jupyter or Google Colab:
- Weather_Prediction_LSTM.ipynb

## ✅ Future Improvements
- Include precipitation as a second prediction target
- Experiment with GRU or Transformer-based models
- Add hyperparameter tuning and cross-validation
