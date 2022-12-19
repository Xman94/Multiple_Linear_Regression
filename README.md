# Multiple Linear Regression
This script demonstrates how to implement multiple linear regression using the scikit-learn library in Python.

## Dependencies
The following libraries are required to run this script:

- numpy
- matplotlib
- pandas
- sklearn
- Input Data
The script reads in a dataset stored in a .csv file called '50_Startups.csv'. The file should contain the following columns:

- Columns of independent variables (predictors)
- Column of the dependent variable (response)
- Preprocessing
The script performs one-hot encoding on the categorical variable in the input data using the OneHotEncoder class from sklearn.preprocessing.

## Model Training and Evaluation
The script then splits the data into a training and test set using the train_test_split function from sklearn.model_selection. The multiple linear regression model is trained on the training set using the LinearRegression class from sklearn.linear_model. The model is then used to make predictions on the test set, and the predictions are compared to the actual values of the dependent variable in the test set.

## Output
The script prints out a comparison of the predicted values and the actual values of the dependent variable in the test set. The predicted and actual values are printed side-by-side for easy comparison.

# Polynomial Regression
This script demonstrates how to implement polynomial regression using the scikit-learn library in Python.

## Dependencies
The following libraries are required to run this script:

- numpy
- matplotlib
- pandas
- sklearn
- Input Data
- The script reads in a dataset stored in a .csv file called 'Position_Salaries.csv'. The file should contain the following columns:

- Column of independent variable (predictor)
- Column of the dependent variable (response)

## Model Training and Evaluation
The script first trains a linear regression model on the input data using the LinearRegression class from sklearn.linear_model. It then trains a polynomial regression model on the same data by first transforming the independent variable using the PolynomialFeatures class from sklearn.preprocessing, and then fitting a linear regression model on the resulting polynomial features.

## Visualization
The script generates three plots to visualize the linear and polynomial regression models. The first plot shows the linear regression model, the second plot shows the polynomial regression model, and the third plot shows a higher-resolution version of the polynomial regression model for a smoother curve.

Output
The script also prints out the predictions made by the linear and polynomial regression models for a new independent variable value of 6.5.
