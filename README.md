# SC1015 Mini-Project
Welcome to our SC1015 Data Science Mini-Project! This project uses the [dataset name and link] dataset from Kaggle. Our presentation is linked [here]. For a complete walkthrough of the project, refer to the following jupyter notebooks:

1. [link to notebook 1]
2. [link to notebook 2]

## Contributors


## Introduction to the Problem

The question we are trying to answer with this project is: *how long will it take before at least 50% of the world's total energy consumption can be met by renewable energy sources?*

To answer this, we initially built a naive linear regression model that we later improved using polynomial regression. We also performed anomaly detection on the dataset to find the countries that consume the most energy overall (renewable + non-renewable).

## Models Used

1. Linear Regression - To predict the year when 50% of global energy consumption can be met by renewables.
2. Polynomial Regression - To improve the model derived in (1) above, because the relationship between the year and the production of renewable energy is non-linear.
3. Isolation Forest - To find what countries consume the most energy in total and to use this information to make recommendations and get data-driven insights into global energy trends.

## Summary and Conclusion

1. Global energy trends vary by continent, country, and year.
2. Among renewable energy sources, there are large variations in the contribution of each source to the total amount of renewable energy generated worldwide.
3. In general, global renewable energy generation has increased over the last two decades or so.
4. Simple regression predicts that renewables will become the largest source of energy within the next 40 years.
5. Linear regression does not yield a good model for non-linear relationships. (MSE>150,000)
6. Polynomial regression resulted in significant improvements in the MSE, and, therefore, provided a better model for the prediction.
7. The Bias-Variance tradeoff is key to improving ML models. Ideally, models should have a low bias and a low variance.
8. Isolation Forest predicts that seven countries consume an abnormally high amount of energy and thus contribute the most to global energy consumption. Our recommendation is to ramp up renewable energy generation in these countries to meet their needs to increase global renewable energy consumption.

## Learning Outcomes

1. Linear and Polynomial regression in scikit-learn.
2. The concept of bias-variance tradeoff.
3. Data visualization techniques in plotly and scikit-learn.
4. The difference between polynomial interpolation and regression.
5. Anomaly detection using the Isolation Forest algorithm.
6. Numpy, pandas, and seaborn.
7. Using github as a tool to collaborate.

## References

https://betterprogramming.pub/anomaly-detection-with-isolation-forest-e41f1f55cc6
