# Farming the Future: Climate-Resilient Crop Prediction 🌱

An independent machine learning research project exploring how climate and environmental data can be used to predict crop suitability and forecast temperature trends for climate-resilient agriculture.

---

## Overview

Climate change has introduced increasing uncertainty in agricultural productivity, impacting crop yields, food security, and long-term sustainability.

This project applies machine learning techniques to analyze environmental and temperature data from major Indian cities to:

- Predict suitable crops based on environmental conditions
- Analyze the importance of climate and soil-related features
- Forecast long-term temperature trends
- Explore data-driven approaches to climate-resilient agriculture

---

## Research Focus

The project combines:

- Crop recommendation datasets
- Historical temperature records (1995–2020)
- Time-series forecasting
- Multi-class classification
- Environmental feature analysis

The study focuses on four major Indian cities:

- Delhi
- Mumbai
- Kolkata
- Chennai

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlforecast

---

## Machine Learning Models

### Crop Prediction
- Logistic Regression (multi-class classification)

### Temperature Forecasting
- Random Forest Regressor
- Extra Trees Regressor

---

## Key Features

- Data preprocessing and feature engineering
- Multi-class crop classification
- Feature importance analysis
- ROC curve evaluation
- Time-series forecasting
- Climate trend visualization
- Temperature suitability mapping for crops

---

## Key Findings

- Temperature, humidity, and soil nutrients were major predictors of crop suitability
- The Extra Trees Regressor showed strong performance in forecasting long-term temperature trends
- Different crops demonstrated distinct temperature preference ranges
- Climate-aware crop selection can support more sustainable agricultural planning

---

## Research Paper

The full research paper is included in this repository:

**Farming the Future: Machine Learning for Climate-Resilient Crop Prediction**

---

## Repository Structure

├── crops.py
├── temperature.py
├── Farming the Future.pdf
├── README.md

---

## How to Run

### 1. Install dependencies

pip install pandas numpy matplotlib seaborn scikit-learn mlforecast

### 2. Run the scripts

python crops.py
python temperature.py

### 3. Upload the required datasets when prompted

---

## Purpose

This project was developed as an independent research initiative focused on applying machine learning to real-world sustainability and agricultural challenges.
