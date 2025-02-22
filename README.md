# Bike Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


## Table of Contents
* Problem Statement
* Technologies/Python Library Used
* Multiple Linear Model Building Steps
* Conclusion

## Problem Statement
BoomBikes want to understand the factors that affects the demand of shared bikes (in America). Thus company wants to :
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies/Python Library Used
- python - version 3.12.7
- numpy - version 2.2.1
- pandas - version 2.2.3
- matPlotLib - version 3.10.0
- seaborn - version 0.13.2
- sklearn - version 1.6.1
- statsmodels.api - version 0.14.4

## Multiple Linear Model Building Steps
As part of multiple linear regression model, we will be performing below steps:
1. Read, Understand and Visualize the data
2. Preparing the data for model (create dummy variable, train-test set, rescaling)
3. Training the model
4. Residual analysis
5. Predictions and evaluation on the test set
6. Automated Approach - Model Selection
7. Conclusion


## Conclusions
1. The independent variable selection in manual linear regression are similar.
2. The R2-Square score in manual =0.813 and automated=0.824, very close
3. Mean Square error is close to zero, which indicated BETTER MODEL FIT
4. Significant variable that can predict the demand for shared bikes are 'const', 'yr', 'workingday', 'temp', 'hum', 'windspeed', 'spring','winter', 'Mon', 'Mar', 'May', 'Nov', 'Sep'.
5. These variable can explain the bike demand with close to 0.813 acurracy.

## Contact
Created by [@chidambaram0705] - feel free to contact me!
