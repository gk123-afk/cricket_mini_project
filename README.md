# cricket_mini_project
# 🔍More deatils about the project is mentioned in the ppt
# 🏏 Cricket Score Prediction Using Machine Learning

This repository presents a machine learning approach to predicting final cricket match scores using real-time and historical ball-by-ball data. The project was presented at the **3rd International Conference on Advancements in Smart, Secure and Intelligent Computing (ASSIC 2025)**, KIIT-DU.

## 📌 Project Overview

The aim is to develop a predictive model that can accurately forecast a team's final score in an IPL T20 match, using factors like player stats, recent overs, venue, and momentum shifts.

## 🎯 Objectives

- Predict final cricket scores using ball-by-ball match data.
- Perform data preprocessing and feature engineering to improve model accuracy.
- Compare models like **Random Forest, XGBoost, SVM**, and more.
- Understand how features like venue, momentum, and player performance influence predictions.

## 🧠 Methodology

- **Data Sources:** Kaggle & Cricinfo (ball-by-ball match data, team/player stats, venue info).
- **Preprocessing:** Missing value handling, scaling, encoding, and irrelevant data removal.
- **Feature Engineering:** 
  - Batsman strike rate, average
  - Bowler economy, average wickets
  - Recent over performance (last 5 overs)
  - Custom metrics for momentum

## 📈 Results

- **Train Score:** 99.05%
- **Test Score:** 99.73%


### 🔍 Model Comparison

✅ **Random Forest** outperformed all other models due to:
- Ability to handle non-linear patterns  
- Resistance to overfitting  
- Minimal hyperparameter tuning  
- Robustness to outliers and noise

## 🏟️ Special Features

- **Venue Encoding:** Incorporated pitch-specific behavior like high-scoring vs low-scoring grounds.
- **Momentum Modeling:** Accounted for score acceleration in the last few overs.

## 🚀 Future Work

- Integrate **LSTM or deep learning** models for temporal understanding.
- Include weather and ground dimensions.
- Build a **real-time web app** with dashboards.
- Extend to **match outcome predictions and player-level forecasting**.



⭐ Star the repo if you find it helpful!
