# mle-training
# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - Import all the requied modules
 - Setup path variables from which dataset can be read
 - Define the functions required to read the dataset as dataframe object
 - We prepare and clean the data. We check and impute for missing values.
 - Perform Feature Engineeing to create new features
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. 
 - Perform hyperparameter tunning
 - The final metric used to evaluate is mean squared error.

## Steps to be traced to execute the script
 - Setup a python virtual env with the required package dependencies
 - Execute the script using: python < scriptname.py >

