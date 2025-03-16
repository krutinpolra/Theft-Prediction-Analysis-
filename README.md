# Theft-Prediction-Analysis

This project predicts the likelihood of a bicycle being stolen using historical data and machine learning algorithms. By analyzing key features such as location, security measures, and time of day, the model provides insights to help reduce the risk of bike theft.

## Overview

We developed a predictive model to determine the likelihood of a bicycle being stolen. The solution leverages classification algorithms trained on real-world data from Toronto Police Services. The model outputs whether a bicycle is likely to be stolen based on the provided features.

## Features

- **Location**: The geographic coordinates and area type where the bicycle is parked.
- **Time of Day**: The specific time when the bike was last parked or used.
- **Bike Specifications**: Attributes such as model, make, cost, and color.
- **Security Features**: Information on locks and other anti-theft devices.
- **Premises Type & Surrounding Area**: Type of premises (e.g., residential, commercial) and surrounding environmental factors.

## Key Technologies

- **Python**: Core programming language.
- **Pandas**: Data cleaning, preprocessing, and manipulation.
- **NumPy**: Efficient numerical operations.
- **Scikit-learn**: Implemented classification models like Logistic Regression and Random Forest.
- **Matplotlib & Seaborn**: Data visualization for exploratory data analysis.
- **Jupyter Notebook**: Development environment for prototyping and testing models.
- **Flask** (optional): For deploying a basic web-based user interface.

## Results

- Improved classification accuracy through feature engineering and model tuning.
- Insights into high-risk locations and time windows for bicycle thefts.
- Visualization of theft trends using bar plots, heatmaps, and other data visualizations.

## Dataset
The dataset comes from the Toronto Police Service's Open Data Portal and contains historical bicycle theft data including features such as location, time, and environmental factors.

**Source**: [Bicycle Thefts Data](https://data.torontopolice.on.ca/pages/bicycle-thefts)

---

Feel free to contribute by improving the model, enhancing visualizations, or integrating additional APIs for real-time prediction.
