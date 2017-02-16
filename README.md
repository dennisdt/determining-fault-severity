Fault severity in cell towers were predicted given multiple different log files. Categorical variables were converted to dummies and model was fit to a classification algorithm. Repo contains all log files and a Jupyter notebook with model.
# Determining Fault Severity

### Objective

Predicts the fault severity given multiple log files. 

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