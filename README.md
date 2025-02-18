# Pitching The Numbers
### Approach
#### Problem Statement
Currently, it is difficult to identify and/or predict when there will be an influx of monthly claims, high dollar claims, or delayed claims presented for process, resulting in higher than normal, expected, or budgeted cash outlay.

Using a claims data set, create an advanced statistical algorithm, ARIMA, Prophet, LSTM, etc. to forecast volume/cash outlay on a monthly basis, forecasting 3 to 6 months in advance.

#### Problem Clarification
We have received a few clarifying questions about the dataset provided to this competition and want to provide some modification to the initial problem statement:

The primary goal for this project is to predict which claims will be flagged as High-Dollar based off the data we have provided

Secondary goal: we want to know if you can predict the number of “delayed” claims per month – this designation is ultimately up to you to train and determine, but generally a delayed claim is one that falls into outlier categorization

You can ultimately incorporate multiple algorithms to solve these problems into some ensemble, and we will evaluate the models with our own methodology

ICD10 codes have been LabelEncoded to de-identify them, as “rare” or low prevalence diagnoses can unintentionally identify a patient (which would be a HIPAA violation), so you should only see encoded, nominal values

Null/NaN values in the High Dollar claim field should not be treated as zeroes – we held back 20% of those entries on our end for final model evaluation, and you should provide your predictions for those masked values as part of your final submission

Any other feature engineering specifications are up to your discretion to implement in your final model(s)

### Methodology
