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

  - I Created a neural network model with two hidden layers and one output layer. First hidden layer has 80 nourons with Relu activiation function. Second hidden layer has 30 nourons with Relu activation function and output layer activation function is Sigmoid.
  
  
  ![model](https://user-images.githubusercontent.com/71282697/107843722-34909a00-6d82-11eb-9287-d857cb10a650.png)

  ![accuracy of the model](https://user-images.githubusercontent.com/71282697/107843741-525dff00-6d82-11eb-895b-4a67af56b225.png)

  
  - The target model performance was 75% while the accuracy of the model was 72% .So, I was not able to get the target model performance.
I dropped the 'SPECIAL_CONSIDERATIONS' column, Created more bins for rare occurrences in 'APPLICATION_TYPE' and 'CLASSIFICATION' columns, added more hidden layers, added more naurones to each layer, changed the activiation function for each layer,and increased the number of epochs. but, none of these steps could help to increase the model performance and get the more accuracy.
  
  
  ![optimizing the model](https://user-images.githubusercontent.com/71282697/107843759-7b7e8f80-6d82-11eb-9997-a251fb0e009f.png)
  
  ![accuracy of the optimized model](https://user-images.githubusercontent.com/71282697/107843768-98b35e00-6d82-11eb-9944-c5c4a0a36d20.png)

  


## Summary

After optimizing the model, the accuracy of the model is still 72% and I didn't get the higher accuracy. I think we can optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy.  
