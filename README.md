# Machine Learning with Regression in Python

This is the notebook used in the Apress published video.

## Business problem
1. We work for a fast-food restaurant that is looking to expand its business to new areas.
2. We have county-wide data including information on houses, incomes, population, crime, zoning information, and more for over 7,000 counties in which our business is currently operating, all stored in the csv file "existing.csv".
3. For each of these counties, we have averaged our sales revenue over the course of the past several months and we will use this data to train a regression model.
4. Using that trained regression model, we will predict what sales will be on a dataset of over 20,000 counties in which we do not have any facilities. This information is stored in "new.csv".
5. **The question our manager wants to answer is which county should we expand our business into next? Where can we expect the most sales revenue?**

## Data Dictionary
- crim: per capita crime rate by town
- zn: proportion of residential land zoned for lots over 25,000 sq.ft.
- indus: proportion of non-retail business acres per town.
- rm: average number of rooms per dwelling
- age: proportion of owner-occupied units built prior to 1940
- tax: full-value property-tax rate per 10,000 dollars
- ptratio: pupil/teacher ratio by town
- black: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- median_home_value: median value of owner-occupied homes
- sales: the average sales by month in the given county
- county_id: the unique identifier of the county in which the store is operating

* Note this data is entirely fictional and was simulated using the [Boston housing dataset](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html#:~:text=The%20Boston%20Housing%20Dataset,the%20area%20of%20Boston%20Mass.&text=It%20was%20obtained%20from%20the,the%20literature%20to%20benchmark%20algorithms.).

## Installation (Windows specific)
- Download [Anaconda](https://www.anaconda.com/products/individual)
- Install required libraries
  - Run the following commands in Anaconda Prompt:
    1. `cd path/to/this/directory`
    2. `pip install -r requirements.txt`