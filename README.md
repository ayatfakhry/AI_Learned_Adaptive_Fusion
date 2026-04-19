> 🚀 This project simulates real-world GNSS outages and evaluates advanced AI-based fusion strategies for reliable navigation.
> # 🚀 AI Adaptive GNSS/INS Fusion System

An advanced AI-driven system for improving positioning accuracy during GNSS outages using adaptive sensor fusion techniques.

---

## 📌 Project Overview

This project focuses on enhancing positioning performance by combining GNSS and INS data using multiple fusion strategies, including:

- Classical fixed fusion
- AI-based fusion
- Confidence-aware fusion
- Scenario-aware fusion
- Optimized fusion (grid search)
- Dynamic ML-based fusion (Random Forest)

The system is specifically designed to handle **GNSS outage scenarios**, where satellite signals become unreliable or unavailable.

---

## ⚙️ Key Features

✅ GNSS/INS data fusion  
✅ AI-based adaptive weighting  
✅ Confidence-aware fusion model  
✅ Scenario-based fusion strategies  
✅ Grid search optimization for best weights  
✅ Dynamic fusion using Machine Learning  
✅ Temporal feature engineering  
✅ Performance evaluation (RMSE, MAE, CDF)

---

## 🧠 Models Implemented

- AI V1 Fusion  
- Confidence-Aware Fusion (V2)  
- Smart Fusion (Scenario-Based)  
- Optimized Fusion (Best static weights)  
- Dynamic Fusion (Random Forest)  
- Temporal Dynamic Fusion (with past-state awareness)

---

## 📊 Performance Metrics

The system evaluates models using:

- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- Availability
- CDF (Cumulative Distribution Function)

---

## 🔍 Key Insight

> Despite introducing dynamic and temporal machine learning models, the optimized static fusion approach achieved the best performance.

This highlights that:

- Learning optimal fusion weights is a complex problem  
- Optimization-based methods can outperform ML in noisy environments  
- Temporal modeling improves stability but not necessarily accuracy  

---

## 📈 Results Summary

| Model | RMSE ↓ | MAE ↓ |
|------|------|------|
| GNSS Only | High | High |
| INS Only | Very High | Very High |
| AI Fusion | Improved | Improved |
| Smart Fusion | Better | Better |
| Optimized Fusion | 🔥 Best | 🔥 Best |
| Dynamic RF Fusion | Good | Good |
| Temporal Dynamic Fusion | Stable | Slightly Improved |

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📂 Project Structure
Developed an AI-driven GNSS/INS fusion system for robust positioning under GNSS outage conditions, implementing adaptive, optimized, and machine learning-based fusion strategies, achieving significant accuracy improvements and analyzing the limitations of data-driven fusion compared to optimization-based approaches.
