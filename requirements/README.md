## Requirements

To receive all points, your Jupyter notebook file must have all of the following:

## Split the Data into Training and Testing Sets (30 points)

- There is a prediction about which model you expect to do better. (5 points)

- The labels set (y) is created from the “spam” column. (5 points)

- The features DataFrame (X) is created from the remaining columns. (5 points)

- The value_counts function is used to check the balance of the labels variable (y). (5 points)

- The data is correctly split into training and testing datasets by using train_test_split. (10 points)

## Scale the Features (20 points)

- An instance of StandardScaler is created. (5 points)

- The Standard Scaler instance is fit with the training data. (5 points)

- The training features DataFrame is scaled using the transform function. (5 points)

- The testing features DataFrame is scaled using the transform function. (5 points)

## Create a Logistic Regression Model (20 points)

- A logistic regression model is created with a random_state of 1. (5 points)

- The logistic regression model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

- Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

- The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

## Create a Random Forest Model (20 points)

- A random forest model is created with a random_state of 1. (5 points)

- The random forest model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

- Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

- The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

## Evaluate the Models (10 points)

- The following questions are answered accurately:

- Which model performed better? (5 points)

- How does that compare to your prediction? (5 points)
