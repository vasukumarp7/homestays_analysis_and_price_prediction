# Homestays Analysis and Price Prediction

  In this homestay analysis and price prediction project, I did data preprocessing steps like filling null values, cleaning, one-hot encoding, and removing redundant data. Then I used data visualization techniques like a correlation heat map to understand the relation between variables, a box  to understand the data quartile range, and a bar plot to find which category was correlated with the price. Then I plotted the map using latitude and longitude variables to understand the price distribution across cities. I also calculated the sentiment score based on description features and calculated the Pearson correlation coefficient to find which amenities are highly correlated with the price variable. I one-hot encoded the categorical variables for machine learning analysis and removed the redundant data. I used seven regression models: linear regression, lasso, ridge, KNN regression, decision tree regression, random forest regression, and gradient boosting regression. Then I used grid search cross validation for less exhaustive models and random search cross validation for highly exhaustive models. I derived feature importance and SHAP values from tree-based models. I also used root mean squared error (RMSE) and R-squared to evaluate the model performance. The insights in this analysis Home characteristics and amenities have a high correlation with price over host information. Based on the model result, focusing on high-priced amenities and home characteristics will increase the profit. Also, remove the low-correlated amenities and house characteristics to save money.
