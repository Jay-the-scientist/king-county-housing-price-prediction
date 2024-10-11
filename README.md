# King County Housing Price Prediction
This project analyzes housing data from King County to build models for predicting home sale prices. The goal is to aid in real estate investment decisions.

# The Task
As a data analyst at a real estate investment trust, I was tasked with determining factors that influence housing prices and developing predictive models. This will help assess markets and value of potential properties to purchase.

# The Data
The dataset contains over 21,000 home sale records for King County, WA between 2014-2015. Features include property details like bedrooms, bathrooms, square footage, building age, as well as location and sale date/price.

| Variable      | Description                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| id            | A notation for a house                                                                                      |
| date          | Date house was sold                                                                                         |
| price         | Price is prediction target                                                                                  |
| bedrooms      | Number of bedrooms                                                                                          |
| bathrooms     | Number of bathrooms                                                                                         |
| sqft_living   | Square footage of the home                                                                                  |
| sqft_lot      | Square footage of the lot                                                                                   |
| floors        | Total floors (levels) in house                                                                              |
| waterfront    | House which has a view to a waterfront                                                                      |
| view          | Has been viewed                                                                                             |
| condition     | How good the condition is overall                                                                           |
| grade         | overall grade given to the housing unit, based on King County grading system                                |
| sqft_above    | Square footage of house apart from basement                                                                 |
| sqft_basement | Square footage of the basement                                                                              |
| yr_built      | Built Year                                                                                                  |
| yr_renovated  | Year when house was renovated                                                                               |
| zipcode       | Zip code                                                                                                    |
| lat           | Latitude coordinate                                                                                         |
| long          | Longitude coordinate                                                                                        |
| sqft_living15 | Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area |
| sqft_lot15    | LotSize area in 2015(implies-- some renovations)       

# Methodology
Python libraries like Pandas, NumPy, Matplotlib and scikit-learn are used for data exploration, preprocessing, modeling and evaluation. Models will include linear regression, polynomial regression and ensemble methods.

# Modeling
LinearRegression, Polynomial transformations, Regularization (Ridge).

# Results
2nd degree polynomial Ridge model achieves highest R2 of 0.704 on test data. 
