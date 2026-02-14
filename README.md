# house-price-prediction-model
# House Price Prediction Model

A machine learning project that predicts house prices using the California Housing dataset and XGBoost regression algorithm.

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project implements a house price prediction model using machine learning techniques. The model is trained on the California Housing dataset and uses XGBoost Regressor to predict median house values based on various features such as location, house age, number of rooms, and demographic information.

## 📊 Dataset

The project uses the **California Housing Dataset** from scikit-learn, which contains:

- **Number of Instances**: 20,640
- **Number of Features**: 8 numeric, predictive attributes
- **Target Variable**: Median house value (in hundreds of thousands of dollars)

### Features:
- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average number of household members
- `Latitude`: Block group latitude
- `Longitude`: Block group longitude

**Data Source**: Derived from the 1990 U.S. census

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning library
- **XGBoost**: Gradient boosting framework

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/1dhanshree/house-price-prediction-model.git
cd house-price-prediction-model
