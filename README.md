# DALI Data Challenge:

In the first part, I created many data visualizations exploring the statistical distributions of sales, quantity, discount, and profit; the distribution of shipping time, converting entries to datetime; the relationship between location and how many items of each category people ordered; and the relative amounts of orders from each subcategory within each category. FInally, I plotted two maps of the orders: one map representing the locations of all orders placed, one representing the locations of those placed in the first month.

In part 2, I tried to use the ridge and lasso linear regression models from scikit learn to predict profit from Postal Code, Region, Category, Sales, Quantity, and Discount. The data had outliers with very high magnitude, so I tried normalizing it and taking the natural log. Nevertheless, I got very high error rates for both models.
