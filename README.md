# Apprentice Chef - Regression and Classification Analysis - Python
---------------------------------------------------------------------

Business Case : Predicting revenue and Predicting success of promotional offer for a Meal kit delivery company called Apprentice Chef.

This repository contains three jupyter notebook files:

1) Regression Analysis - A project on predicting revenue for a meal-kit delivery app called Apprentice Chef.

2) Classification Analysis - A project on predicting the success of a promotional offer for the same company.

3) Report to Management - A report to the company management providing insights and recommendations based 
on the regression analysis and the classification analysis.

Packages used:pandas, numpy, seaborn, matplotlib, statsmodels, sklearn

Regression Analysis recommendations
-------------------------------------------------
Revenue has a positive correlation with Average Preparation Video Time, Median Meal Rating and Total Meals Ordered.
It has a negative correlation with Average Clicks Per Visit. 
For every 1 unit increase in Median Meal Rating, Revenue increases by 8.3%. 
For every 1 unit increase in Master Classes Attended, Revenue increases by 4.1%.

Insights: -

1) Increase Median Meal Rating by addressing customer concerns expressed on platforms.

2) Make Master Classes more detailed and intricate so that customers feel a greater sense of achievement.

Classification Analysis recommendations
-------------------------------------------------
Cross-sell has a good positive correlation with Email Domain, Number of Names a customer has and Cancellations Before Noon.
We can predict when Cross-sell would be a success 95% of the time. 
We can predict when it would be failure 73% of the time.

Insights: -

1) Send Sales Promotion offers to professional email domains on workdays to boost sales among target market.

2) Coordinate logistics to deliver meal sets to working professionals when they get back home and reduce refund for Cancellations After Noon.

Model Scores
-------------
The revenue model’s highest testing R square was 0.681.
It had the Log of Revenue as dependent variable. 
It was built on selected statistically significant variables. The method used was OLS regression.

The cross-sell model’s highest AUC score was 0.844. 
The method used was Gradient Boosting based on hyperparameters. 
It was built using all variables in the dataset.
