# EV Energy Demand Forecasting using Machine Learning

## 📌 Project Overview

This project analyzes Electric Vehicle (EV) charging infrastructure data to understand and predict energy consumption patterns at municipal charging sites. Unlike traditional categorical studies, this research employs Supervised Machine Learning Regression—specifically Random Forest and Neural Network architectures—to forecast the exact Energy Provided (kWh) for each charging session. By modeling the relationship between charging duration, geographical location, and temporal variables, this study provides actionable insights for grid stability management and urban infrastructure planning in transitioning energy markets like Uganda.

## 🎯 Objectives

* Data Description
* Data Exploration and Visualization
* Data cleaning and Preparation
* Modelling and Evaluation
* Summary

## 📊 Dataset

The dataset contains information about EV charging stations including:

* Charger counts (Level 1, Level 2, DC Fast)
* Location 
* Facility information

## Requiremnts
* pandas
* scikit-learn
* gradio
* joblib

## ⚙️ Methods

* Data Cleaning and Preparation
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Models:

  * Random Forest (Classical Model)
  * Neural Network (MLP Classifier)

## 📈 Results

* Identified high-demand energy zones
* Random Forest achieved strong performance
* Neural network required tuning but provided comparable results

## 🧠 Key Insights

* Locations with more chargers have higher energy demand
* Fast chargers significantly increase consumption
* Demand is geographically clustered

## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/HeatherNankunda/electric-vehicle-energy-demand-forecasting.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   notebooks/ev_analysis.ipynb

## 📌 Author

Heather Nankunda
