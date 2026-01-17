# 🔥 Forest Fire Burned Area Prediction using Neural Networks (Keras)

## 📌 Project Overview
Forest fires cause severe environmental and economic damage.  
This project aims to **predict the burned area of forest fires** using meteorological and environmental data by applying a **Neural Network regression model built with Keras**.

The model captures **non-linear relationships** between weather conditions and fire behavior.

---

## 🎯 Problem Statement
Predict the **burned area of forest fires (in hectares)** using historical weather, fuel moisture indices, and environmental variables.

---

## 📊 Dataset Information
- **Total records:** 517
- **Target variable:** `area` (burned area in hectares)
- **Dataset type:** Multivariate regression

### Key Features:
- Spatial coordinates (X, Y)
- Fire weather indices: FFMC, DMC, DC, ISI
- Weather conditions: temperature, humidity (RH), wind, rain
- Temporal data: month, day (encoded)

---

## 🧹 Data Preprocessing
- Encoded categorical variables (`month`, `day`)
- Removed `size_category` to avoid data leakage
- Applied **StandardScaler** for feature scaling
- Target variable skewness handled during modeling

---

## 🧠 Model Used
- **Neural Network (Regression)**
- Built using **TensorFlow / Keras**
- Architecture:
  - Input layer
  - Two hidden layers with ReLU activation
  - Output layer with linear activation

---

## ⚙️ Model Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

> Due to the highly skewed nature of forest fire data, prediction remains challenging but informative.

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

