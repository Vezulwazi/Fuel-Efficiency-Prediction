# Fuel Efficiency Prediction (Auto MPG)

A beginner-level regression project that predicts a car’s fuel efficiency (MPG, miles per gallon) using engine and vehicle characteristics.

---

## Problem Statement

Given a car’s attributes:

- Cylinders
- Engine Displacement
- Horsepower
- Weight
- Acceleration
- Model Year
- Origin

predict its fuel efficiency in **miles per gallon (MPG)**.

---

## Dataset

**Source:** UCI Auto MPG Dataset

- Total Samples: **398 cars**
- Model Years: **1970–1982**
- Features: **7 input features + 1 target variable**

### Feature Description

| Feature | Type | Description |
|----------|------|-------------|
| cylinders | Integer | Number of engine cylinders |
| displacement | Float | Engine displacement (cu in) |
| horsepower | Float | Engine horsepower (6 missing values imputed) |
| weight | Float | Vehicle weight (lbs) |
| acceleration | Float | 0–60 mph time (seconds) |
| model_year | Integer | Model year (70–82) |
| origin | Categorical | 1 = USA, 2 = Europe, 3 = Japan |
| car_name | String | Vehicle name (dropped during preprocessing) |
| mpg | Float | Fuel efficiency (target variable) |

---

## Project Structure

```text id="q8xv1a"
Fuel Efficiency Prediction/
│
├── 01_eda.ipynb              # Exploratory Data Analysis
├── 02_data_cleaning.ipynb    # Data cleaning & feature engineering
├── 03_model_building.ipynb   # Model training & evaluation
├── utils.py                  # Helper functions
├── requirements.txt         # Dependencies
├── README.md                # Documentation
│
└── data/
    ├── auto_mpg.csv
    └── auto_mpg_cleaned.csv
