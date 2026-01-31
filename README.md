# ☀️ Solar Energy Production Forecasting System

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-green)
![Streamlit](https://img.shields.io/badge/Deployed%20With-Streamlit-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

The intermittency of renewable energy sources poses a major challenge to grid stability—especially within Germany’s **Energiewende** initiative.  
This project tackles that challenge by building a **high-fidelity solar power forecasting system** using historical sensor data and weather features.

The system demonstrates an **end-to-end Machine Learning pipeline**—from raw data preprocessing to a deployed interactive dashboard—highlighting practical skills in **Data Science, Machine Learning, and Full-Stack deployment**.

---

## 🚀 Key Features

- **High Predictive Accuracy**  
  - R² Score: **0.9864**  
  - Mean Absolute Error (MAE): **168.38 kW**

- **Cyclical Feature Engineering**  
  - Applied **Sine/Cosine encoding** to preserve the 24-hour temporal cycle and eliminate discontinuities.

- **Interactive Web Dashboard**  
  - Real-time solar power forecasting with *what-if* scenario analysis using **Streamlit**.

- **Robust Data Pipeline**  
  - Automated cleaning, transformation, and merging of generation and weather datasets.

---

## 🛠️ Technical Stack

| Category | Tools |
|--------|------|
| **Language** | Python 🐍 |
| **Libraries** | Pandas, NumPy, Scikit-Learn |
| **Visualization** | Matplotlib, Seaborn |
| **Model** | Random Forest Regression |
| **Deployment** | Streamlit |
| **Environment** | Google Colab |

---

## 🎯 Project Motivation

In the context of Germany’s **Energiewende**, accurate renewable energy forecasting is critical for:

- Grid load balancing  
- Energy trading optimization  
- Reduced reliance on fossil-fuel backup systems  

This project applies **Random Forest Regression** to model non-linear relationships between environmental variables and solar output, achieving high predictive performance.

---

## 📊 Performance Metrics

| Metric | Value |
|------|------|
| **R² Score** | **0.9864** |
| **Mean Absolute Error (MAE)** | **168.38 kW** |
| **Total Data Points** | **68,000+** |

---

## 🔬 Technical Highlights

- **Cyclical Encoding**  
  Implemented sine/cosine transformations to maintain temporal continuity across day-night boundaries.

- **Exploratory Data Analysis (EDA)**  
  Identified strong correlations between:
  - Solar Irradiation  
  - Ambient Temperature  
  - DC Power Output  

- **Full-Stack ML Deployment**  
  Integrated preprocessing, model inference, and visualization into a single Streamlit app.

---

## 💡 Key Discovery: The “Midnight Jump”

A major modeling challenge was the **discontinuous representation of time** (hour 23 → 0).  
By applying **trigonometric time mapping**, prediction errors during transition periods were significantly reduced—demonstrating the importance of feature engineering in time-series problems.

---

## 📈 Future Improvements

- Incorporate **LSTM / Temporal CNNs** for sequence learning  
- Add **real-time weather API integration**  
- Extend support for **multi-site solar farms**  
- Implement **model explainability (SHAP)** for interpretability

---

## 👩‍💻 Author

**Riya Jain**  
🎓 B.Tech – Computer Science & Engineering  
🏫 Government Engineering College, Ajmer  

---

⭐ *If you find this project interesting, feel free to star the repository!*  
