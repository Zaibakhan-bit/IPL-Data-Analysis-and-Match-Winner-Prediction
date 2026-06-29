# 🏏 IPL Data Analysis and Match Winner Prediction
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Machine Learning](https://img.shields.io/badge/MachineLearning-ScikitLearn-green)


## 📌 Project Overview

This project analyzes Indian Premier League (IPL) match data using **Python, Machine Learning, and Power BI**. The objective is to discover meaningful insights from historical IPL data and build a machine learning model to predict match winners based on pre-match information.


## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on IPL data.
- Identify trends in team and player performances.
- Build machine learning models to predict match winners.
- Design an interactive Power BI dashboard for data visualization.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI


## 📂 Dataset

The dataset used in this project is publicly available on Kaggle:

**IPL Complete Dataset (2008–2020):**
https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020

Download the dataset and place the following files inside the `data/` folder before running the notebook:

* `matches.csv`
* `deliveries.csv`


## 📊 Exploratory Data Analysis

Some of the analyses performed include:

- Matches played per season
- Team-wise wins
- Toss decision analysis
- Top run scorers
- Top six hitters
- Top four hitters
- Top wicket takers
- Dismissal analysis
- Venue analysis

## 🤖 Machine Learning

Three classification models were trained and compared.

| Model | Accuracy |
|-------|----------|
| Logistic Regression | **55.50%** |
| Random Forest | 50.46% |
| Decision Tree | 44.50% |

**Best Model:** Logistic Regression

## 📈 Power BI Dashboard

The dashboard contains five interactive pages:

- 🏏 Overview
- 🏆 Team Analysis
- 💥 Batting Analysis
- 🎯 Bowling & Venue Analysis
- 🤖 Machine Learning Summary

## 📷 Dashboard Preview

Screenshots are available in the `dashboard_screenshots` folder.
## Dashboard Preview

### Overview
![Overview](dashboard_screenshots/IPL_DASHBOARD.jpeg)

### Team Analysis
![Team Analysis](dashboard_screenshots/TEAM_ANALYSIS.jpeg)

### Batting Analysis
![Batting Analysis](dashboard_screenshots/BATTING.jpeg)

### Bowling & Venue Analysis
![Bowling & Venue Analysis](dashboard_screenshots/BOWLINGVENUE.jpeg)

### Machine Learning Summary
![ML Summary](dashboard_screenshots/PREDICTION.jpeg)

## 🚀 Future Improvements

- Include player form
- Include weather conditions
- Include pitch information
- Include playing XI
- Experiment with XGBoost and LightGBM

## 📌 Conclusion

This project demonstrates the complete data analytics workflow—from data cleaning and visualization to machine learning and business intelligence dashboards—using real IPL data.

