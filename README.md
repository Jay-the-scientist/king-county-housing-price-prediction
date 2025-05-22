# King County Housing Price Prediction
This project analyzes housing data from King County to build models for predicting home sale prices. The goal is to aid in real estate investment decisions. 

## Objective
As a data analyst at a real estate investment trust, I was tasked with determining factors that influence housing prices and developing predictive models. This will help assess markets and value of potential properties to purchase.

## Installation
Install the required Python libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## The Data
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

## Methodology
Data preprocessing involved removing outliers, converting date values, and engineering new features like age of the home. Exploratory analysis identified strong correlations, especially between square footage and price. Models such as Linear Regression and Decision Tree Regressor were trained and evaluated. Metrics like R² and RMSE were used to assess performance.

## Results
- Living space (sqft_living) had the strongest correlation with price.
- Newer houses and properties in premium locations commanded higher prices.

## Visualizations
