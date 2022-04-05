# Prediction-modeling-Real-Estate
 A step by step guide for doing my first machine learning modeling for real estate in California
 My individual contribution is to fill in the blanks for coding and developing the models. Also all my observations are put under Markdowns.
 
 ## About the dataset
 This dataset was based on data from the 1990 California census. They also added a categorical attribute and removed a few features for teaching purposes.
 This data has metrics such as the population, median income, median housing price, and so on for each block group in California. Block groups are the 
 smallest geographical unit for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).
 
 ## Conclusion
 After analyzing the corresponding models: linear regression, decision tree, random forest regressor and grid search, we conclude that the grid 
 search is the best model for predicting. We shall proceed to run the test set using the grid search. We can refine the model even further by 
 decreasing the weight of coefficience of the variables of the hypothesis.
 
 The best Estimator is median income where it had the highest score. This means that the most important factor when predicting the house price, 
 it is the income of the family living in this house. To take it further, we can say that the median income of the people trying to buy an appartment
 should be taken into consideration when targeting them for high priced apartments.
 
 
