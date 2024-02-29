
**Output**

Intercept: -3662760.716731824
                    Coefficient
longitude          -43744.839786
latitude           -43638.568221
housing_median_age   1164.087506
total_rooms            -5.044436
total_bedrooms         79.519672
population            -45.879703
households             87.892252
median_income       39249.112784
Mean Squared Error: 5106013432.131462

MAE: 51689.81623391512
MSE: 5106013432.131462
RMSE: 71456.37432819736

**Description**
* These values represent the change in the predicted value of the dependent variable for a one-unit increase in the corresponding independent variable, holding all other independent variables constant.
1. Negative coefficients: longitude, latitude, total_rooms, population
These indicate that an increase in these variables leads to a decrease in the predicted value of the dependent variable.
2. Positive coefficients: housing_median_age, total_bedrooms, households, median_income
These indicate that an increase in these variables leads to an increase in the predicted value of the dependent variable.


![linearRegression](https://github.com/angelahuang3/MachineLearningProjects/assets/123219721/bc42e348-fa86-4387-8b7d-042d164bae09)

This data can be used for various purposes, such as:
1. Predicting median house prices: This is a common regression task where the model learns the relationship between the features and the median_house_value and uses it to predict the price of new houses.
2. Understanding factors affecting housing prices: By analyzing the coefficients of a fitted model, we can gain insights into which features are most important in influencing housing prices and how they affect the prices.
3. Developing decision support systems: Machine learning models trained on this data can be used to help real estate agents, investors, and policymakers make informed decisions about housing.
