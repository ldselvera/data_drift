## Data drift

Data drift (covariate shift) is a change in the statistical distribution of production data from the baseline data used to train or build the model. Data from real-time serving can drift from the baseline data due to:

*	Changes in the real world
* Training data not being a representation of the population
*	Data quality issues like outliers in the dataset

## Concept drift

Concept drift is a phenomenon where the statistical properties of the target variable you’re trying to predict changes over time. This means that the concept has changed but the model doesn’t know about the change. 

Concept drift happens when the original idea your model had about the target class changes. For example, you build a model to classify positive and negative sentiment of tweets around certain topics, and over time people’s sentiment about these topics changes. Tweets belonging to positive sentiment may evolve over time to be negative. 

In simple terms, the concept of sentiment analysis has drifted. Unfortunately, your model will keep predicting positive sentiments as negative sentiments.

## Data drift vs concept drift

As data is collected from multiple sources, data itself is changing. This change can be due to the dynamic nature of the data, or it can be caused by changes in the real world.

If the input distribution changes but the true labels don’t (the probability of the model’s input changes but the probability of the target class given the probability of the model input doesn’t change), then this kind of change is considered as data drift.

Meanwhile, if there’s a change in the labels or target classes of your model, that is the probability of the target class changes given the probability of the input data. This means we’re detecting the effect of concept drift. Both data drift and concept drift cause model decay and should both be addressed separately.
