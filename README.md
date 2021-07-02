# Housing Costs in King County

The  second project focuses on statistics and linear regression to help  improve  skills at finding, isolating, and evaluating evidence to help reach informative conclusions. We were provided past data from King County about housing sales. With this in mind, I wanted to figure out to use this information to help potential home buyers figureout a direction to help them find a home. 

The price of a home in Western Washington has increased exponentially over the past 10 - 15 years. As a result, it is harder and harder to find an affordable house if somene doesn't have an annual income of around 80,000 dollars. 

By using libraries such as matplotlib, seaborn, and techiniques such as simple and multiple linear regressions, I hope to find the most accurate model to predict the best price for a house. 

### Data Used

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

### Methods 
I cleaned the data
Logged data in most models 
Removed outliers
One Hot Encoded categorical data 
Made several models 
Looked for features that were most correlated with price
Used the date to find out when are the best months to buy a house. 

### Results 
The data in my last model contained the features that a buyer will look at when trying to purchase a house. In my first models I did most methods but did not come out successful. In my ninth model I added the one hot encoded categorical data then my model started to train and test the data well. 
The final train error was 164055.86123491873
The final test error was  164525.45580753023

### Conclusion 
Based on the data, the categorical features were important when fitting this model. Zip Code, waterfront, and the view were features that changed the model and caused it to fit well. One hot encoding, logging, and removing outliers helped the most when trying to get the closest prediction. It would be good to buy a house in the summer months, with a good view, waterfront, and a good sized house. 


### Best Month to buy a house. 

![](bsc-phase-two-project/images/Sales_By_Month.jpg)


My first figure shows the most housing sales in different months of the year. According to the graph, monthe April, May, and July are the best times to purchase a house. 


### What's Next?

1. Using more of the data given to make the most accurate model that could be made. 
2. Try to lower the data in each individual price range in the model's output. 
