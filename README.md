# Rainfall Prediction Using Linear Regression

A machine learning project that predicts rainfall using Linear Regression. This project establishes relationships between weather variables (temperature, humidity, dew point) and precipitation to forecast rainfall amounts.

## 📋 Project Overview

Predicting rainfall is a vital aspect of weather forecasting, agriculture planning, and water resource management. This project uses Linear Regression algorithm to establish relationships between dependent variable (rainfall) and independent variables (temperature, humidity, dew point) to predict how many inches of rainfall we can expect.

## 🎯 Features

- Data collection from online dataset
- Comprehensive data preprocessing and cleaning
- Feature selection based on weather variables
- Linear Regression model training
- Model evaluation with multiple metrics (MSE, RMSE, R²)
- Visualization of predictions vs actual values
- Residual plot analysis
- Model persistence using pickle/joblib

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning algorithms and tools
- **joblib** - Model serialization

## 📊 Dataset

The project uses a rainfall dataset containing the following features:

- `tempmax` - Maximum temperature
- `tempmin` - Minimum temperature
- `humidity` - Humidity percentage
- `dew` - Dew point
- `precip` - Precipitation (target variable)

Dataset source: [Rainfall Dataset](https://raw.githubusercontent.com/itsluckysharma01/Datasets/refs/heads/main/Rainfall_dataset.csv)

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### Installation

1. Clone this repository
2. Install required dependencies
3. Open `RainFall_Prediction.ipynb` in Jupyter Notebook or VS Code
4. Run all cells sequentially

## 📈 Model Workflow

1. **Data Loading**: Load dataset from CSV file
2. **Data Preprocessing**: Handle missing values and clean data
3. **Feature Selection**: Select relevant features (tempmax, tempmin, humidity, dew)
4. **Train-Test Split**: Split data (80% training, 20% testing)
5. **Model Training**: Train Linear Regression model
6. **Prediction**: Generate predictions on test data
7. **Evaluation**: Calculate MSE, RMSE, and R² score
8. **Visualization**: Plot actual vs predicted values and residuals
9. **Model Saving**: Save trained model using joblib

## 📊 Model Evaluation Metrics

- **Mean Squared Error (MSE)**: Measures average squared difference between predicted and actual values
- **Root Mean Squared Error (RMSE)**: Square root of MSE, in same units as target variable
- **R-squared (R²)**: Indicates proportion of variance in dependent variable predictable from independent variables

## 📁 Project Structure

```
Rainfall_prediction_using_Linear_regression/
│
├── RainFall_Prediction.ipynb    # Main Jupyter notebook with complete implementation
├── README.md                      # Project documentation
└── rainfall_prediction_model.pkl # Saved trained model (generated after running)
```

## 💡 Usage

Run the Jupyter notebook cells sequentially:

1. Import necessary libraries
2. Load the dataset
3. Preprocess the data
4. Select features and target variable
5. Train the model
6. Evaluate performance
7. Visualize results
8. Save the model

## 📊 Visualizations

The project includes two key visualizations:

1. **Actual vs Predicted Rainfall**: Scatter plot showing model predictions against actual values
2. **Residual Plot**: Shows distribution of prediction errors

## 🔮 Future Improvements

- Add more weather features (wind speed, pressure, cloud cover)
- Try other regression algorithms (Ridge, Lasso, Random Forest)
- Implement cross-validation
- Add feature engineering
- Deploy model as a web application

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

Created as a machine learning practice project for rainfall prediction.

## 🙏 Acknowledgments

- Dataset provided by [itsluckysharma01](https://github.com/itsluckysharma01/Datasets)
- Built using scikit-learn library
