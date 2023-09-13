
<div class='title' align="center">
    <h3>Project: Analysing House Prices in King County, Washington, USA</h3>
</div>

**Overview:**

You, as a skilled Data Analyst, have been entrusted with a pivotal project at a Real Estate Investment Trust (REIT). The task at hand is to meticulously assess the market prices of houses sold in King County, Washington, during the period between May 2014 and May 2015. To accomplish this, you will be utilizing a specific set of features such as square footage, number of bedrooms, number of floors, and more.

---

**Data Analysis Techniques:**

**Data Wrangling:** In this initial phase, you will be working with the raw data, preparing it for analysis. This involves tasks like handling missing values, removing duplicates, and transforming the data into a structured format suitable for further exploration.

**Exploratory Data Analysis (EDA):** Here, you'll delve deep into the dataset, uncovering patterns, correlations, and trends. Visualizations and statistical summaries will be pivotal tools to help you understand the relationships between different features and the target variable (house prices). 

**Linear Regression Model Development:** Armed with insights from the EDA, you will embark on the process of building a linear regression model. This model will be trained on the historical data to predict house prices based on the provided features. Linear regression is particularly useful for this task as it allows us to model the relationship between the variables.

**Model Evaluation:** Once the model is trained, it's crucial to assess its performance. This includes metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²) values. These metrics will give you a clear understanding of how well the model is predicting house prices.

**Model Refinement:** Based on the initial evaluation, you may identify areas for improvement. This could involve fine-tuning hyperparameters, considering feature engineering, or potentially exploring other machine learning models for comparison.

---

**Data Dictionary:**

| Variable      | Description                                                                                                 |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| id            | A notation for a house                                                                                      |
| date          | Date house was sold                                                                                         |
| price         | Price is prediction target                                                                                  |
| bedrooms      | Number of bedrooms                                                                                          |
| bathrooms     | Number of bathrooms                                                                                         |
| sqft_lot      | Square footage of the lot                                                                                   |
| sqft_living   | Square footage of the home                                                                                  |
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
| sqft_lot15    | LotSize area in 2015(implies-- some renovations)                                                            |
