# Used Cars Data Exploration

## Dataset

This document explores a dataset sourced from Kaggle(https://www.kaggle.com/datasets/shubham1kumar/usedcar-data?select=UserCarData.csv) containing prices and attributes for approximately 7906 ,and 18 features of used cars .


## Summary of Findings

The Car name Maruti had the highest count of used cars, upon checking the selling price for the cars, the distribution was rightly skewed, most of the selling prices of most cars were less than a million lakhs, when I applied log transformation on the selling price, the price distribution looks unimodal, with one peak between 600k and 1M.

Cars with bigger engine with automatic transmission fuel source was either Diesel or Petrol, and on a average were highly priced. But Manual transmission consisted of Diesel, Petrol and CNG cars were priced below 300k.
As for smaller engine power, Manual cars with fuel source; CNG ad LPG were priced below 300k, and Diesel and Petrol ranged from 300k-700k. And automatic, with a transmission of Diesel and Petrol ranging from 600k-1M averagely

Price had a surprisingly high amount of correlation with the year the cars were purchased, cars that were sold were mostly purchased in 2008 and upwards and sold at above 100,000 t0 10M. The state of California was seen to have the most count of used cars, New York sold more, followed by California. The count of cars a state had, didn't influence the amount of cars sold. A larger chunk of used cars with an engine power of 1000-1500 generated max power between 50-100 Max power.

From the above visualizations, I gathered that, First Car owners sold more than other owners, with the highest count in the Eastern Region, followed by Second Owners ranking higher also in the East.

Cars with automatic transmission had a wide spread of higher selling price than the manual cars.


From the point plot, it was interesting to find that there were used cars sold that ran on fuel source, LPG and CNG, which the count plot didn't show earlier. I noticed that, a car name could be one of either transmissions, and can vary in price.







KEY INSIGHTS FOR PRESENTATION

For the presentation, I focus on just the influence of the km driven, mileage, engine power, and the categorical variables on selling price.

I used pair plots to check the correlation between the numeric variables, Max power and engine power seems to be positively correlated with selling price of the cars, km-driven has a negative correlation with selling price. 
Other plots are either negatively correlated with the selling price or have no correlation at all.

I used box plots to check the relationship between numeric variables and the categorical variables.

I used point plots to check the selling price of used cars by their transmission as against their fuel source. Finally, I used scatter plots to check the correlation between the selling price of used cars against the km driven by their engine power.
 
