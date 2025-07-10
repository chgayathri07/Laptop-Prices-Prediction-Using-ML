# 💻 Laptop Price Prediction Using ML

A machine learning project that predicts laptop prices based on their specifications. Built using the CRISP-ML(Q) methodology, this project aims to help manufacturers and consumers better understand how different features impact laptop pricing.

---

## 🚀 Overview

SmartTech Co. collaborated with our data science team to build a predictive model that estimates laptop prices. With a wide variety of laptops in the market, this model helps both businesses and consumers make informed pricing and purchase decisions.

---

## 🎯 Objectives

* Predict laptop prices accurately from given specifications
* Understand the influence of components (RAM, brand, CPU, etc.)
* Build interactive visualizations for analysis
* Prepare the model for real-time deployment (optional)

---

## 🧠 CRISP-ML(Q) Methodology

### 1. Business Understanding

* Define key client objectives: pricing strategy, competitive analysis

### 2. Data Understanding

* Dataset includes: RAM, CPU, GPU, storage type, screen, brand, OS, and price
* Exploratory Data Analysis (EDA): Missing values, distributions, trends

### 3. Data Preparation

* Handled missing data and outliers
* Feature encoding (e.g., one-hot for brand, CPU type)
* Feature engineering (e.g., binary flags for storage types)

### 4. Modeling

* Algorithms used:

  * Linear Regression
  * Random Forest Regressor
  * Gradient Boosting Regressor
* Evaluation Metrics:

  * RMSE (Root Mean Squared Error)
  * MAE (Mean Absolute Error)
  * R2 Score

### 5. Evaluation

* Model comparisons using bar charts
* Error analysis (Actual vs Predicted)
* Chose best model based on accuracy and generalization

### 6. Deployment (Optional)

* Google Colab + Matplotlib/Seaborn dashboards for EDA
* * Streamlit app for real-time price predictions

---

## 📊 Visualizations

1. **Actual vs Predicted Prices** (scatter plot)
2. **Error Distribution** (histogram)

---

## 🛠 Tech Stack

* Python (Pandas, NumPy, Scikit-learn)
* Google Colab
* Seaborn, Matplotlib, Plotly

