# Neural-Network-Charity

## Overview of the Analysis 

The purpose of the analysis is to use machine learning to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The original csv containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. First step of the analysis is Preprocessing Data for a Neural Network Model. And then we will Compile, Train, and Evaluate the Model. Finally we will optimize the model to see whether a higher accuracy could be achieved. 

## Results 

### Data Preprocessing 

* What variable(s) are considered the target(s) for your model?

  IS_SUCCESSFUL is a target for my model. Because the purposer of the analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

* What variable(s) are considered to be the features for your model?

  - APPLICATION_TYPE
  - AFFILIATION 
  - CLASSIFICATION
  - USE_CASE
  - ORGANIZATION
  - STATUS
  - INCOME_AMT,
  - SPECIAL_CONSIDERATIONS
  - ASK_AMT

* What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN
  - NAME

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

  ![image](https://user-images.githubusercontent.com/88631769/148705050-5284735d-2753-4a08-97aa-76bf616708c5.png)

 
* Were you able to achieve the target model performance?

  No, the highest accuracy I could achieve is 73%. 
  
* What steps did you take to try and increase model performance? 
  
  Adding more hidden layers and changing the activation function for the hidden layers. 
  
### Summary 

The deep learning neural network model did not reach the target of 75% accuracy after 3 attemps. The highest result we could get is 73%. To achieve a higher accuracy, more data needs to be acquired. In a binary classification, we could use a supervised machine learning model to combine numerous decision trees. 

