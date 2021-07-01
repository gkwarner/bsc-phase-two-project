# Phase Two Project Repo
## Overveiw
Analysis of house price data and a predictive model to estimate the cost of a house based off multiple features.

## Busness Problem:
A Seattle real estate firm would like to create a tool that allows their clients to enter information about their home and receive a prediction for their home's sale price. They have hired you to produce a predictive model that can predict the sale price of a home as accurately as possible.

## Comparision 
The correlation between price and each feature was evaluated to examine the importance of each in the model.  This was done by graphing each relationship.  This was used to answer questions like, how mcuh does sqft_living affect the price of a home.  This can also show us any outliers in the feature.

## Data
From the house data we gatherd 12 features related to price containing 21597 rows of data.  We narrowed this down to 11 features and 14178 rows of data.  This was done by removing outliers and null values and checking correlations.

# Results

## Bedroom and Price Correlation

![Bedrooms_and_Price_Correlation](./images/Bedrooms_and_Price_Correlation.png)
#### The price increses as bedrooms increse.  This is true until after 8 bedrooms where the price lowers.

## Price and sqft_living Correlation

![Price_and_sqft_living_correlation](./images/Price_and_sqft_living_correlation.png)
#### Price increses as sqft_living increses
## Waterfront and Price Correlation

![Waterfront_and_Price_Correlation](./images/Waterfront_and_Price_Correlation.png)
#### Houses on a waterfront have higher prices then those not on a waterfront
## Floors and Price Correlation

![Floors_and_Price_Correlation](./images/Floors_and_Price_Correlation.png)
#### Price increses with the addition of floors however a 2 story house is more expensive then a three story house.
## Grade and Price Correlation

![Grade_and_Price_Correlation](./images/Grade_and_Price_Correlation.png)
#### As grade increses price also increses
### View and Price Correlation

![View_and_Price_Correlation](./images/View_and_Price_Correlation.png)
#### As the view improves the price increses
## Model Preformance

![Model_Preformance](./images/Model_Preformance.png)

## Conclusion

Our model preforms well in prices from 385000-535000 dollars but has high error with prices from 77999-322000 and 645000-7700000 dollars.  sqft_living, bedrooms, and grade are have high correlations with price.