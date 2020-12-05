# MSBD5001Kaggle

Programming language used: Python

Packages used:
pandas,
numpy,
sklearn->train_test_split, RandomForestRegressor, mean_squared_error, GridSearchCV, ShuffleSplit,
requests,
BeautifulSoup

Steps to run the code:
1. Mount the google drive which I put both train and test datasets there
2. import both files as dataframe using pandas
3. use the function to separate into Year, Month, Day and Hour columns
4. Get public holiday from HK government website
5. Merge the hokiday to the training dataframe
6. Get weekday names
7. Split into train and validating datasets
8. Run random forest model
9. Use grid search and cross validation to tune hyper parameters
10. Run RF model again using best hyper parameters
11. Predict the results on test datasets using the trained RF model
12. Save the result into csv and export it
