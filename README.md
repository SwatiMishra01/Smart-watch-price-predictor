# Smart Watch Price Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.25-green?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-1.6.2-blue?logo=pandas)

## Overview
Predicts the price of smart watches based on specifications like brand, display, connectivity, battery life, GPS, NFC, and heart rate monitor.  
Uses **Random Forest Regressor** for price estimation.

## Features
- Predicts price for any smart watch using its specifications.
- Handles categorical features with **one-hot encoding**.
- Automatically manages missing or unseen categories.
- Easy to extend with new watches or features.

## Dataset
- Source: Kaggle / Custom dataset
- Columns:
  - Brand, Model, Operating System, Connectivity
  - Display Type, Display Size (inches), Water Resistance (meters)
  - Battery Life (days), Heart Rate Monitor, GPS, NFC
  - Resolution Width & Height
  - Price (target variable)

## Technology Used
- Python
- Pandas, NumPy
- scikit-learn
- Jupyter Notebook

## Usage

1. Clone the repository:
```bash
git clone <repo-link>
cd smart-watch-price-prediction
```
2.Install dependencies
```bash
pip install -r requirements.txt
```

