# Smart Watch Price Prediction

## Overview
This project predicts the price of smart watches based on their specifications such as brand, display, connectivity, battery life, and features like GPS, NFC, and heart rate monitor.  
The model uses **machine learning** (Random Forest Regressor) to estimate the price of a new watch given its features.

## Features
- Predicts price for any smart watch using its specifications.
- Handles categorical features using **one-hot encoding**.
- Includes preprocessing for **missing or unseen categories**.
- Easy to extend with more watches or additional features.

## Dataset
- Source: Kaggle / Custom smart watch dataset  
- Columns included:
  - Brand
  - Model
  - Operating System
  - Connectivity
  - Display Type
  - Display Size (inches)
  - Water Resistance (meters)
  - Battery Life (days)
  - Heart Rate Monitor
  - GPS
  - NFC
  - Resolution Width (`Res_Width`)
  - Resolution Height (`Res_Height`)
  - Price (target variable)

## Technology Used
- Python
- Pandas, NumPy
- scikit-learn (Random Forest Regressor)
- Jupyter Notebook (for experimentation)

## How to Use
1. Clone the repository:
```bash
git clone <repo-link>
cd smart-watch-price-prediction
