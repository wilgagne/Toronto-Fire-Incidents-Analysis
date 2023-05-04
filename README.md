# Toronto-Fire-Incidents-Analysis
## Introduction:
This study aims to predict the time it takes to control residential fires using factors such as the extent and ignition source of a fire, the number of responding personnel, the presence of a fire alarm system, and the time to arrival of firefighters. Previous research has shown relationships between these factors and fire outcomes, but this study investigates their relationship with the time it takes to control a fire.

## Methods:
The research employs a classic data analysis approach using a dataset of fire incidents from the city of Toronto. The dataset is randomly split into training and test sets, and exploratory data analysis is performed to identify potential assumption violations. Linear regression is used to model the relationship between the predictors and response variable. Assumptions for linear regression are verified using residual plots, and appropriate transformations are applied if necessary.

## Results:
The findings suggest that a linear relationship exists between the time to control a fire and all of the predictors except the "Time to arrival" variable. Presence of a fire alarm system, the extent of the fire, the ignition source, and the number of responding personnel are useful in predicting the time it takes to control a fire. Normality and constant variance assumptions were partially violated, which may impact the accuracy of the model.

## Discussion:
The study demonstrates the potential to predict the time it takes to control a fire using relevant factors. However, the model's limitations include normality violation and small sample size in some categories, which may cause biased predictor coefficients. Future research may benefit from larger sample sizes to improve the model's accuracy and generalizability.
