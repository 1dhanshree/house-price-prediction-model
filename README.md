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
```

2. Install required dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

Or using requirements.txt (if available):
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook House_Price_Prediction.ipynb
```

2. Run all cells sequentially to:
   - Load and explore the dataset
   - Perform data preprocessing
   - Train the XGBoost model
   - Evaluate model performance
   - Make predictions

Alternatively, you can open the notebook in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/1dhanshree/house-price-prediction-model/blob/main/House_Price_Prediction.ipynb)

## 📁 Project Structure

```
house-price-prediction-model/
│
├── House_Price_Prediction.ipynb    # Main Jupyter notebook
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies (if applicable)
```

## 🤖 Model Details

**Algorithm**: XGBoost Regressor

XGBoost (eXtreme Gradient Boosting) was chosen for this project because:
- High predictive accuracy
- Efficient handling of large datasets
- Built-in regularization to prevent overfitting
- Excellent performance on structured/tabular data

### Model Pipeline:
1. Data Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Train-Test Split
5. Model Training (XGBoost)
6. Model Evaluation
7. Predictions

## 📈 Results

*Results section to be updated with model performance metrics such as:*
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- California Housing Dataset from scikit-learn
- Dataset derived from the 1990 U.S. Census
- Reference: Pace, R. Kelley and Ronald Barry, Sparse Spatial Autoregressions, Statistics and Probability Letters, 33 (1997) 291-297

## 👤 Author

**Dhanshree**
- GitHub: [@1dhanshree](https://github.com/1dhanshree)

---

⭐ If you found this project helpful, please consider giving it a star!