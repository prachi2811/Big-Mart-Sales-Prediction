# Big-Mart-Sales-Prediction
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.
Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.
The aim is to build a predictive model and find out the sales of each product at a particular store.
So the idea is to find out the properties of a product, and store which impacts the sales of a product. Let’s think about some of the analysis that can be done and come up with certain hypothesis.
One of the key challenges in any data set is missing values, so missing values are imputed using column transformation teachnique where any numerical column missing value are imputed with the median whereas any categorical column missing values are imputed with the mode or the most frequently occuring value.
All the categorical columns are converted into numerical columns using one-hot encoding method.
After building models around the dataset and basic eda the results are presented in the files attached.
XGB gives the best variance and bias error tradeoff.
