# Tesla Stock Price Prediction Project

## Overview

This project implements a machine learning model to predict Tesla (TSLA) stock closing prices using historical market data. The project uses various regression models including Linear Regression, Decision Trees, and Random Forest, with optional implementations of Ridge and Lasso regression.

## Project Structure

```
tesla_stock_analysis/
├── notebooks/
│   ├── 1_Data_Exploration.ipynb
│   ├── 2_Feature_Engineering.ipynb
│   ├── 3_Model_Development.ipynb
│   ├── 4_Model_Evaluation.ipynb
│   └── 5_Results_and_Conclusions.ipynb
│   └── models/
│       ├── decision_tree_model.joblib
│       ├── linear_model.joblib
│       ├── random_forest_model.joblib
│       ├── ridge_model.joblib
│   └── resuls/
│       ├── model_performance.csv
├── data/
│   └── TSLA_data.csv
│   └── TSLA_processed.csv
├── README.md
└── requirements.txt
```

## Features

- Data exploration and visualization of TSLA stock trends
- Feature engineering for improved prediction accuracy
- Multiple regression models implementation
- Model performance evaluation using RMSE and R²
- Comprehensive visualization of predictions vs actual values

## Installation

1. Clone this repository
2. Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

Navigate through the notebooks in sequence:

1. Data Exploration: Initial analysis and visualization of stock data
2. Feature Engineering: Creation of new features and data preprocessing
3. Model Development: Implementation of various regression models
4. Model Evaluation: Performance analysis of different models
5. Results and Conclusions: Final analysis and visualization of results

## Requirements

See requirements.txt for detailed package dependencies.

## Author

AMZIL ASMAA

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
