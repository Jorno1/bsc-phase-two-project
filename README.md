# Housing Costs in King County

The  second project focuses on statistics and linear regression to help  improve  skills at finding, isolating, and evaluating evidence to help reach informative conclusions. We were provided past data from King County about housing sales. With this in mind, I wanted to figure out to use this information to help potential home buyers figureout a direction to help them find a home. 

The price of a home in Western Washington has increased exponentially over the past 10 - 15 years. As a result, it is harder and harder to find an affordable house if somene doesn't have an annual income of around 80,000 dollars. 

By using libraries such as matplotlib, seaborn, and techiniques such as simple and multiple linear regressions, I hope to find the most accurate model to predict the best price for a house. 

### Data and Technologies Used

This project uses the King County House Sales dataset from 2014 - 2015. 

The following language and libraries were used for this project:

* Python
* Matplotlib
* Seaborn
* Pandas
* Numpy
* Statsmodels
* Scipy

The provided data set gave us the following housing information:

* date
* price
* bedrooms
* bathrooms
* sqft_living
* sqft_lot
* floors
* waterfront
* view
* condition
* grade
* sqft_above
* sqft_basement
* yr_built
* yr_renovated
* zipcode
* lat
* long
* sqft_living15
* sqft_lot15

For this project, I will be looking at comparing our target variable (sales price) with living space (sqft_living), grade, and number of bathrooms, zipcode, view, and waterfront. There will also be mentions about the date the house was bought in  to find out which part of the year would be the best to find a house. 
### Questions to be answered:

- When is the best time to buy a home?
- Where is the best place in King County to buy a home?(Zipcode)
- How do various features such as number of bathrooms, grade of the house, amount of living space play impact the price? 


### Recommendations

![](bsc-phase-two-project/images/Sales_By_Month.png)


My first figure shows the most housing sales in different months of the year. According to the graph, monthe April, May, and July are the best times to purchase a house. 



This figure shows prices, age of the home, and locational data with bubble size representing price and colors representing when the house was built. It shows us location is correlated with your sales price. In general, buying a house north of the 47.5 latitude will be much more expensive than buying a house south of that latitude. Houses in the south of that latitude are substantially cheaper. 




### What's Next?

1. Using more of the data given to make the most accurate model that could be made. 
2. Try to lower the data in each individual price range in the model's output. 
