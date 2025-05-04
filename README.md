# Regression Analysis on Movie Data

## Overview
This project explores regression analysis techniques applied to movie data. The goal was to investigate relationships between movie features and build predictive models using various regression approaches.

## Libraries Used
- **Data Handling**: 
  - `pandas` for data manipulation
  - `numpy` for numerical operations
- **Visualization**:
  - `seaborn` and `matplotlib.pyplot` for data visualization
- **Machine Learning**:
  - `sklearn.model_selection.train_test_split` for data splitting
  - `sklearn.linear_model.LinearRegression` for linear regression
  - `sklearn.metrics` for model evaluation (mean_squared_error, r2_score)
  - `sklearn.preprocessing` for feature engineering (OneHotEncoder, PolynomialFeatures)
  - `sklearn.compose.ColumnTransformer` for column-wise transformations
- **Data Source**:
  - `kagglehub` for accessing movie dataset

## Analysis Steps
1. **Data Loading**: Accessed movie dataset through Kaggle Hub
2. **Exploratory Data Analysis**: 
   - Examined feature distributions
   - Visualized relationships between variables
3. **Data Preprocessing**:
   - Handled categorical variables using one-hot encoding
   - Potentially created polynomial features for nonlinear relationships
4. **Model Building**:
   - Split data into training and test sets
   - Implemented linear regression model
   - Possibly explored polynomial regression
5. **Evaluation**:
   - Assessed model performance using MSE and R² metrics
   - Compared different feature engineering approaches


## How to Run
1. Install required libraries: `pip install pandas numpy seaborn matplotlib scikit-learn kagglehub`
2. Run the Jupyter notebook or Python script containing the analysis
