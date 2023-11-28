## Overview

The purpose of this analysis is to create a machine learning model to help determine which applicants have the best chance at success when funded by the nonprofit foundation Alphabet Soup. 

## Process

* First the dependencies and the CSV file are imported. 
* Next the data is prepared for the model by deleting columns, binning certain ranges in the 'APPLICATION TYPE' and 'CLASSIFICATION' columns, and using get_dummies.
* Data is then split into training and testing data. 
* The model is defined with two hidden layers with 30 neurons each. 
* The model is compiled and then fit and trained with 100 Epochs. 

## Outcome
* The model results in an accuracy of 72.83% and a loss of 0.5582