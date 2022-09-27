House Price Prediction Model determines the price of a house when provided with one or more parameters. 
Such models are important in real estate market to analyze patterns in varying property prices. They are becoming popular as they can help in indicating the market and economic conditions of a place. 

The following dataset has been used to build and train predictive models https://www.kaggle.com/datasets/shree1992/housedata?datasetId=46927. 

The models built in this experiment are: 

1. Simple Linear Regression: Predicts price of a house on the basis of sq feet living. 

2. Polynomial Regression: Predicts price of a house on the basis of sq feet living and determines whether the data is linear or non-linear. 

*Various parameters used for other models: Number of bedrooms, number of baths, sq feet living, sq feet loft, 
floor level, waterfront, view, condition, sq feet above, sq feet of basemenet, year it was built in, year it was renovated, name of city and year it is available.*

3. Multiple Linear Regression: Predicts price of a house on various parameters listed above.

4. Support Vectore Regression: Predicts price of a house on various parameters listed above.

5. Decision Tree Regression: Predicts price of a house on various parameters listed above.

6. Random Forest Regression: Predicts price of a house on various parameters listed above.

The models are tested against new predictions and their accuracies are evaluated using mean sqaured error and r2 score. 
