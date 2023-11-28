# Report - Deep Learning Assignment 

## Overview

The purpose of this analysis is to create a machine learning model to help determine which applicants have the best chance at success when funded by the nonprofit foundation Alphabet Soup. 

## Results

### Data Processing
* The “IS_SUCCESSFUL” column, showing which funding was successful, is the variable that will be set as the target for the model.
* All of the columns except for the “IS_SUCCESSFUL”, “EIN”, and “NAME” columns are the variables that will be set as features for the model. 
* The “EIN” and “NAME” columns are neither the target or features for the model, so they will be removed from the input data. 


### Compiling, Training, and Evaluating.
* I chose 2 layers with 30 neurons each formy neural network model, because I had 43 inputs, so I wanted less than that, but not too few. I chose "relu" and "tanh" because after playing around with different options those seemed like a good choice. 
* I was not able to achieve the 75% target model performance.
* In my first attempt at increaseing the model performance I added hidden layers and increased the number of Epochs, which only increased the accuracy slightly. In the second attempt I dropped the "STATUS", AND "SPECIAL_CONSIDERATIONS" columns, which had a similar accuracy to the original model, maybe a slight increase in accuracy. In my third and final attempt I decreased the bin sized of the "APPLICATION_TYPE" AND "CLASSIFICATION" columns and added a hidden layer, which slightly increased the accuracy from the original model but not enough to get to 75%.


## Summarize

My original deep learning model ended up with a 73.85% accuracy with a loss of 0.5353. 
