# Transport-Demand-Prediction


![demand prediction](https://github.com/meyush0/Transport-Demand-Prediction/assets/112842527/b508872d-b956-4d68-9d29-a86af25b4a11)

## Project Objective
Nairobi-Transport-Demand-Prediction dataset provided to us is in unformatted manner, uneven data, and duplicate data and also some data columns in it is irrelevant. For doing the analysis on the data, the data needs to be in correct format and well organized formed.

As I read the data present in the file and gone through the details in each and every column. The data set was huge in which some of the data was not required for the analysis so the data was cleaned by dropping some unwanted columns and obtained the target variable "number of ticket", this is got from ride id. then created a new data frame, with the columns we required for the analysis including target variable.

I used feature engineering to get useful columns out of irrelevent column. Each and every column were compared to gain the insights about the data by doing the exploratory data analysis using python. and also saw the distribution of target variable. Cleaning the dataset, statistically analysing the data and visualizing the data by plotting the data into different graph and charts so that the trend and relationship between the various indicators can be understand easily, Modelling and Predicting the model using Machine learning algorithms.

To preform linear regression, we have to fulfil the assumption of it. so I used Variance inflation factor(VIF) and heatmap to compute multicollinearity in the dataset, I remove the features which have high multicollinearity and acquire the best features for regression. Perform train test split, feature scaling by zscore. I used different types of regression algorithm to train our model like, Linear Regression, Regularized linear regression (Ridge and Lasso), and used all the feature without checking multicollinearity to train our model like, Decision tree regressor, Random Forest regressor, and XGboost regresssor and Also I tuned the parameters of Regularized linear regression (Ridge and Lasso), Random Forest regressor and XGboost regressor and also found the important features for training the model.

Out of them XGboost with tuned hyperparameters gave the best result.

This resulting model can be used by Mobiticket and bus operators to anticipate customer demand for certain rides, to manage resources and vehicles more efficiently, to offer promotions and sell other services more effectively, such as microinsurance, or even improve customer service by being able to send alerts and other useful information to customers.

## Conclusion

As we have implemented six different models to predict the number of seats that Mobiticket can expect to sell for each ride. 
* Linear Regression, Regularized linear regression (Ridge and Lasso), Decision Tree, Random Forest Regressor and Xgboost Regressor. Xgboost regression model with hyperparameter tuning performed the best among them.
Our Model will help Mobiticket and Bus operators to anticipate the number of tickets they can expect to sell for each ride.
