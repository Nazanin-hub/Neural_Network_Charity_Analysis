# Neural_Network_Charity_Analysis
DeepLearning

## Project Overview

Helping Backs who is a datascientist in the nonprofit foundation Alphabet Soup to predict which organizations are worth donating to and which are too high risk. I designed a neural network, or deep learning model, using the python TensorFlow library to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Then, I compileed, trained, and evaluateed the binary classification model to calculate the model’s loss and accuracy.


## Resources

Data Source: charity_data.csv

Software: Python 3.8.3, Anaconda Navigator 1.9.12, Jupyter Notebook 6.0.3


## Results

### Data Preprocessing

  - IS_SUCCESSFUL column has been considered the target for the model.
  
  - All columns(APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT ) except IS_SUCCESSFUL column and 'EIN','NAME' columns have been considered the features for the model.
  
  - Identification columns,'EIN','NAME', should be removed from the input data.
  
### Compiling, Training, and Evaluating the Model

  - I Created a neural network model with two hidden layers. First hidden layer has 80 nourons with Relu activiation function. Second hidden layer has 30 nourons with Relu activation function and output layer activation function is Sigmoid.
  
  - 
  - 

## Summary
