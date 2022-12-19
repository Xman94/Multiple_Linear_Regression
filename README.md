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
