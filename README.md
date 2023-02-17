# Cognizant AI Internship

## Situation:
I participated in an AI internship where I worked on a project that involved training a Random Forest Regressor model using cross-validation. The project required loading a CSV file containing data that was used to create target and predictor variables. The objective was to use these variables to train the model and generate performance metrics using mean absolute error.

## Task:
My task was to load the CSV file into a Pandas DataFrame and split the data into a target column and predictor variables. I then had to use these splits to train the Random Forest Regressor model with K folds of cross-validation. Performance metrics were output for each fold, and the average mean absolute error was computed across all folds.

## Action:
To load the CSV file into a Pandas DataFrame, I used the load_data() function which took a path string to the CSV file and returned the loaded data. I then used the create_target_and_predictors() function to split the data into predictor and target variables. The Random Forest Regressor model was trained using the train_algorithm_with_cross_validation() function, which used K folds of cross-validation to train the model, and the performance metrics were output for each fold.

I used the following libraries to accomplish the tasks:

- pandas (pd)
- scikit-learn (sklearn)

## Result:
As a result of the project, I was able to successfully train a Random Forest Regressor model using K folds of cross-validation. Performance metrics were generated for each fold, and the average mean absolute error across all folds was computed. The trained model and the computed metrics can be used to evaluate the accuracy of the model and to make predictions on new data.

# Conclusion:
Through this project, I gained experience in using Python and machine learning libraries like Pandas and scikit-learn to load and preprocess data, split data into target and predictor variables, train machine learning models using cross-validation, and evaluate the performance of the models. This project helped me to develop practical skills in data science and to better understand the process of building and evaluating machine learning models.
