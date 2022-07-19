# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data.

The following techniques have been used:

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To excute the script
1. First download data, execute **download_data.py** stored in **data_scripts** module.
2. Now split the data, execute **split_data.py** stored in **data_scripts** module.
3. Explore data using **explore_data.py** stored in **data_scripts** module.
4. Now create new features, execute **create_features.py** stored in **data_scripts** module.
5. To select best model train models over the data using **train.py** stored in **model_training_scripts** module.
6. Now predict using best models over the data using **score.py** stored in **model_scoring_scripts** module.

