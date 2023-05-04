# Toronto-Fire-Incidents-Analysis 🔥🧯

## Introduction:
This study aims to predict the time it takes to control residential fires using factors such as the extent and ignition source of a fire, the number of responding personnel, the presence of a fire alarm system, and the time to arrival of firefighters. Previous research has shown relationships between these factors and fire outcomes, but this study investigates their relationship with the time it takes to control a fire.

## Dataset:
Link: https://open.toronto.ca/dataset/fire-incidents/

his dataset encompasses fire incidents, as defined by the Ontario Fire Marshal (OFM), up until December 31, 2021. It offers more detailed information than the basic incidents dataset, specifically for fire incidents that the Toronto Fire Service (TFS) addresses. The dataset's format aligns with the reporting data that TFS submits to the OFM.

To protect privacy, personal information has been omitted, and exact addresses have been aggregated to the nearest major or minor intersection. Incidents with incomplete data might still be under investigation or may be classified as no-loss outdoor fires.

## Methods:
The research employs a classic data analysis approach using a dataset of fire incidents from the city of Toronto. The dataset is randomly split into training and test sets, and exploratory data analysis is performed to identify potential assumption violations. Linear regression is used to model the relationship between the predictors and response variable. Assumptions for linear regression are verified using residual plots, and appropriate transformations are applied if necessary.

## Results:
The findings suggest that a linear relationship exists between the time to control a fire and all of the predictors except the "Time to arrival" variable. Presence of a fire alarm system, the extent of the fire, the ignition source, and the number of responding personnel are useful in predicting the time it takes to control a fire. Normality and constant variance assumptions were partially violated, which may impact the accuracy of the model.

## Discussion:
The study demonstrates the potential to predict the time it takes to control a fire using relevant factors. However, the model's limitations include normality violation and small sample size in some categories, which may cause biased predictor coefficients. Future research may benefit from larger sample sizes to improve the model's accuracy and generalizability.

* See [Report](https://github.com/wilgagne/toronto-fire-incidents-analysis/blob/02127c4b8537d578792bea9a7a2e82272a41319c/Analysis_Report.pdf) for full analysis.
