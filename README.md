## What is data drift?

Data drift (covariate shift) is a change in the statistical distribution of production data from the baseline data used to train or build the model. Data from real-time serving can drift from the baseline data due to:

*	Changes in the real world
* Training data not being a representation of the population
*	Data quality issues like outliers in the dataset

For example, if you built a model with temperature data collected from a sensor in Celsius degrees, but the unit changed to Fahrenheit – it means there’s been a change in your input data, so the data has drifted.

## How to monitor data drift in production

The best approach to handling data drift is to continuously monitor your data with advanced MLOps tools instead of using traditional rule-based methods. Rule based methods, like calculating the data range or comparing data attributes to detect alien values, can be time-consuming and are susceptible to error. 

The best approach to handling data drift is to continuously monitor your data with advanced MLOps tools instead of using traditional rule-based methods. Rule based methods, like calculating the data range or comparing data attributes to detect alien values, can be time-consuming and are susceptible to error. 
