# credit-risk-classification
# Module 20 Report

## Overview of the Analysis

For this analysis, we are attempting to quantify the credit risk for a list of individuals based on a variety of factors: total debt, debt-to-income ratio, and loan interest rate, etc. After splitting our data into training and testing data, we can fit a logistic regression model using our training data. These data points are then classified as "healthy loans" or "high-risk loans" and our model tells us the degree of accuracy with which we can trust our findings.


## Results

Our model does exceptionaly well when it comes to healthy loan predictions. With precision of 100% we can be very confident that our data will be accurate.

The model still fairs well, but less so when it comes to high-risk loans. Our model shows precision of 85%, which is still a strong performance. However, any precision percentage below the high-90's shows that our model risks having inaccurate high-risk loan data.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Our model has handled the data given fairly well, especially with healthy loan prediction, enough to provide a framework for ways to better fit future modified models. However with the accuracy below 90% in high-risk loan prediction we will likely need to resample and restructure our data and tweak our model until sound predictions can be made.
