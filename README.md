# Farming the Future: Climate-Resilient Crop Prediction 🌱

This project explores how machine learning can be used to support climate-resilient agriculture by predicting suitable crops based on environmental conditions and forecasting temperature trends.

## 📌 Overview
Climate change has introduced significant uncertainty in agricultural productivity. This project uses machine learning techniques to analyze crop and temperature data to:
- Predict suitable crops based on environmental conditions
- Analyze feature importance (e.g., temperature, humidity, soil nutrients)
- Forecast temperature trends across major cities

## 📊 Datasets
- Crop Recommendation Dataset (Kaggle)
- Daily Temperature Data (1995–2020) for major Indian cities

## 🛠️ Technologies Used
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- mlforecast

## 🤖 Machine Learning Models
- Logistic Regression (crop prediction) :contentReference[oaicite:0]{index=0}
- Random Forest Regressor :contentReference[oaicite:1]{index=1}
- Extra Trees Regressor (temperature forecasting)

## 📈 Key Features
- Data preprocessing and feature engineering
- Multi-class classification for crop prediction
- Feature importance visualization
- ROC curve analysis
- Time series forecasting of temperature trends

## 📊 Results
- Temperature, soil nutrients, and humidity were identified as key predictors of crop suitability
- The Extra Trees model showed strong performance in forecasting temperature trends
- Visualizations revealed optimal temperature ranges for different crops

## 📄 Research Paper
A full research paper detailing methodology, analysis, and findings is included:

**Farming the Future: Machine Learning for Climate-Resilient Crop Prediction** :contentReference[oaicite:2]{index=2}

## 🚀 How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn mlforecast
   
2. Run:
   python crops.py
   python temperature.py

   
3. Upload datasets when prompted

## 💡 Purpose
This project demonstrates how machine learning can be applied to real-world problems, particularly in sustainability and agriculture, by transforming data into actionable insights.
