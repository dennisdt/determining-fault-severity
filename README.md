# Determining Fault Severity

### Objective

Predicts the fault severity given multiple log files. Convert categorical variables to dummies and classify fault severity using the given features. 

### Code

The code is provided in the `Fault Severity Predictions.ipynb` notebook file. The data is read from the `event_type.csv`, `log_feature.csv`, `resource_type.csv`, and `severity_type.csv` dataset files. 

### Data

The dataset consists of the following fields:
* event_type: Categorical
* log_feature: Categorical
* volume: Numerical
* resource_type: Categorical
* severity_type: Categorical
* location: Categorical
* fault_severity: Ordinal
