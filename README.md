# Neural_Network_Charity_Analysis
Analysis of charities using deep neural networks

## Overview of the analysis: 
The purpose of this analysis is to create a neural network model that will analyze if applicants will be successful based on the information given by the dataset. The data was preprocessed before being used in the model.

## Results: 
Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The targets for this model were: Is Successful, which stated whether or not the loan was successful
What variable(s) are considered to be the features for your model?
- The features for this model were: Application Type, Affiliation, Use Case, Classification, Organization, Income Amount, and Ask Amount. EIN and Name were removed as they are unique to each applicant.
What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and Name were neither targets nor features and were removed from the input data.
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used two hidden layers with eight and six neurons, respectively. With each successive model, I tried different activation functions, including tanh, ReLu, and sigmoid. In previous model sets I have found tanh and sigmoid work well together.
Were you able to achieve the target model performance?
I did not achieve target model performance. I was just shy of 75% accuracy at 73% accuracy
What steps did you take to try and increase model performance?
I tried to increase model performance by changing the activation functions.

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

Overall, the model did not seem to increase in accuracy with more epochs. The first epochs had a model accuracy of 68% and it only seemed to increase to about 73%. Perhaps this is the limitation of the model. It might be worth persuing another type of classification such as random forests.
