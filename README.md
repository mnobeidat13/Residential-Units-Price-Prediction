# HousePrices
Visualization Map https://mnobeidat.netlify.app/ <br/>
Predicting and visualizing houses prices in Dubai <br/>
RandomForest(which turned to give the best result among other algorithms like linear regression and decision tree) regressor from sklearn was used to predict house prices depeneding on 4 variables: <br/>
Area, number of bedrooms, number of bathrooms and location.<br/>
A training aacuracy of 0.97 and testing accuracy of 0.87 was the best achieved even with hyperparemeter tuning and GradientBoosting.<br/>
Raw data which was collected from bayut.com using web scraper extension on chrome is saved in bayut3.csv.<br/>

final_map.html contains a map with plots of prices for each location of the 75 different locations in Dubai covered by the analysis.
