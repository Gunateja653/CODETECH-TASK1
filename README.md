# Boston-Housing-mL-model
The Boston Housing Dataset
NAME:Guna Teja sarvan Patnaik
ID:CT4ML4739
DOMAIN:MACHINE LEARNING
MENTOR:Muzammil Ahmed

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

* **CRIM:** Per capita crime rate by town
* **ZN:** Proportion of residential land zoned for lots over 25,000 sq.ft.
* **INDUS:** Proportion of non-retail business acres per town
* **CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* **NOX:** Nitric oxides concentration (parts per 10 million)
* **RM:** Average number of rooms per dwelling
* **AGE:** Proportion of owner-occupied units built prior to 1940
* **DIS:** - weighted distances to five Boston employment centres
* **RAD:** - index of accessibility to radial highways
* **TAX:** - full-value property-tax rate per $10,000
* **PTRATIO:** - pupil-teacher ratio by town
* **B:** - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
* **LSTAT:** - % lower status of the population
* **MEDV:** - Median value of owner-occupied homes in $1000's
# Boston Housing Price Prediction

This project aims to predict the median value of owner-occupied homes (MEDV) in the Boston area using various machine learning algorithms. The dataset used is the Boston Housing Dataset, a popular dataset for regression analysis.

## Steps

1. **Data Loading and Exploration:**
   - Load the Boston Housing Dataset from '/content/boston.csv'.
   - Perform exploratory data analysis (EDA) to understand the dataset's characteristics, including descriptive statistics and visualizations.

2. **Outlier Detection and Handling:**
   - Identify and handle outliers in the 'MEDV' column to improve model performance.

3. **Feature Selection:**
   - Utilize mutual information regression to select the most relevant features for predicting 'MEDV'.

4. **Model Selection and Evaluation:**
   - Experiment with different regression models, including Linear Regression, Random Forest Regressor, AdaBoost Regressor, Support Vector Regression (SVR), Decision Tree Regressor, and XGBoost Regressor.
   - Evaluate model performance using metrics such as Root Mean Squared Error (RMSE) and R-squared (R2) score.

5. **Prediction System:**
   - Develop a prediction system using the best-performing model (XGBoost Regressor in this case) to predict 'MEDV' based on user-provided input values for the selected features.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Usage

1. Install the required dependencies.
2. Run the provided code in a Google Colab environment or a Jupyter Notebook.
3. Follow the prompts to input values for the selected features and obtain the predicted 'MEDV'.

## Model Training:

XGBoost library is used to create and train a regression model.
Model parameters such as the objective function (reg:squarederror) and evaluation metric (rmse) are defined.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.
