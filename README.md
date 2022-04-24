# SC1015 Mini-Project
Welcome to our SC1015 Data Science Mini-Project! This project uses the [Global Energy Consumption & Renewable Generation](https://www.kaggle.com/datasets/jamesvandenberg/renewable-power-generation) dataset from Kaggle. Our presentation [slides](https://docs.google.com/presentation/d/1BiESdyCDe18korISUYRaPje2cy7CG9sy6mEpWsvPSJQ/edit?usp=sharing) and [video](https://drive.google.com/file/d/157ETJFmPq6lHxcoHpRSCc8RqUW1dP3R1/view?usp=sharing). For a complete walkthrough of the project, refer to the following jupyter notebooks:

1. [Exploratory Data Analysis](https://github.com/aarushi-nema/SC1015-Project/blob/main/EDA.ipynb)
2. [Data Driven Insights](https://github.com/aarushi-nema/SC1015-Project/blob/main/Data%20Driven%20Insights.ipynb)
3. [Machine Learning and Anamoly Detection](https://github.com/aarushi-nema/SC1015-Project/blob/main/Machine%20Learning%20and%20Anomaly%20Detection.ipynb)

## Contributors

1. @Pratham117 - Machine Learning models (Linear and Polynomial regression), Isolation Forest for anomaly detection, Data Visualization in plotly and scikit for Polynomial regression and Isolation Forest.
2. @aarushi-nema - Exploratory data analysis, data cleaning, extraction.
3. @Bappe304 - Data Visualization in scikit-learn.

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
7. Variance is a measure of how well a model’s train set performance can be replicated on the test set.
8. Bias is the error (the difference between the actual and predicted value) in the model.
9. In general, as bias increases, the variance decreases and vice-versa. This is called the bias-variance tradeoff and is key to improving ML models. Ideally, models should have a low bias and a low variance.
10. Isolation Forest is an anomaly detection model that recursively splits each feature at a random point between the maximum and minimum values for that feature. It then runs a simple test on every point in the feature space to construct a tree. Values are classified as either outliers or inliers based on where they are placed in the tree.
11. Isolation Forest predicts that seven countries consume an abnormally high amount of energy and thus contribute the most to global energy consumption. Our recommendation is to ramp up renewable energy generation in these countries to meet their needs to increase global renewable energy consumption.

## Learning Outcomes

1. Linear and Polynomial regression in scikit-learn.
2. The concept of bias-variance tradeoff.
3. Data visualization techniques in plotly and scikit-learn.
4. The difference between polynomial interpolation and regression.
5. Anomaly detection using the Isolation Forest algorithm.
6. Numpy, pandas, and seaborn.
7. Using github as a tool to collaborate.

## References

https://betterprogramming.pub/anomaly-detection-with-isolation-forest-e41f1f55cc6 <br>
https://towardsdatascience.com/machine-learning-polynomial-regression-with-python-5328e4e8a386 <br>
https://towardsdatascience.com/polynomial-regression-with-scikit-learn-what-you-should-know-bed9d296f2 <br>
https://matplotlib.org/stable/plot_types/index <br>



