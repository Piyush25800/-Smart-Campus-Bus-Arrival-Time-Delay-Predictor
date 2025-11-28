# 🚌 Smart Campus Bus Arrival Time Predictor

A machine learning project that predicts **bus arrival delay (in minutes)** for campus buses using factors like distance, time of day, traffic, weather, and previous delays.

This can help students estimate whether the campus bus will be **on time, early, or late**, and plan accordingly.

---

## 🎯 Project Overview

The model is trained on a **synthetic but realistic dataset** that simulates different routes, traffic conditions and weather.  
A **Random Forest Regressor** is used to predict the expected delay from the scheduled arrival time.

**Input features:**

- Route ID  
- Distance from stop to campus (km)  
- Hour of the day  
- Day of the week  
- Peak hour flag  
- Weather condition (sunny / cloudy / rain)  
- Traffic level (low / medium / high)  
- Previous stop delay (minutes)

**Output:**

- Predicted arrival delay (in minutes)  
- Human-readable message:
  - *“Expected to be about 7.8 minutes late.”*  
  - *“Expected to be roughly on time.”*  
  - *“Expected to be about 3.2 minutes early.”*

---

## 🧠 Tech Stack

- Python  
- NumPy, Pandas  
- Scikit-learn (RandomForestRegressor, train/test split, pipeline)  
- Joblib (model saving/loading)

---
