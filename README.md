### Prediction of Product Sales
#### Analysis and preciction model for sales price of food items sold at various stores
##### Author: David Patton

Early exploration of the data set features and their correlations.

![image](https://user-images.githubusercontent.com/115942163/236379956-484eb294-b577-492b-abb9-4fbcee96db00.png)

 - Noticed a strong coorelation between Item MRP and Outlet Sales.

Examining the distribution of sales, looking for outliers in the data set.

![image](https://user-images.githubusercontent.com/115942163/236361625-657b10e1-3945-4b1b-b18b-c6a7ebec7474.png)


## Model

I expiremented with two models, a linear regression model and a decision tree. The decision tree ended up; being the best performing model. The tree was originally ran with a max depth of 20 but after further tuning the depth was adjusted to 5 for better poerformace. 

The decision tree model received a R-squared score of 0.60 on the training set and 0.59 on the test set. 

The low variance of the decision tree make it a better performing and reliable model.

## Recommendations:

My final recommendation is to use the decision tree regressor tuned to a max depth of 5 for optimal performance.
