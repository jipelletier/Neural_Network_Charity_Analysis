# Neural_Network_Charity_Analysis
## Project Overview & Purpose

Deep Neural networks are used for analyzing images and processing datasets. They are modeled after neurons in the brain to be effective with datasets that are complex.

This project used the features provided in the dataset to create binary classifier that predicts whether applicants will be succesful being funded by Alphabet Soup, a non profit organization. The neural network we create assists the non profit organization in analyzing the impacts of each donations and participants to efficiently use all donations.


## Results

## Data Reprocessing

### What variable is considered a target for your model?
- Is_Successful

### What variables are considered to be the features for your model?
- Application_Type
- Affiliation
- Classification
- Use_Case
- Organization
- Status
- Income_Amt
- Special_Consideration
- Ask_Amt

### What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN
- Name

## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The original model had 2 hidden layers and 1 outer layer but with optimization work, an additional hidden layer was added. The original had 80 neurons in the first hidden layer and 30 in the second hidden layer. To increase the model performance I increased them a bit. The activation functions I used in the hidden layers were relu and sigmoid because they are most effective given the type of data used

### Were you able to achieve the target model performance?
- I was unable to achieve target model performance despite trying 3 different models

### What steps did you take to try and increase model performance?
- To attempt to increase model performance, I removed columns, added a layer, and removed classification and application_type which resulted in a decrease of performance. I also increased the number of neurons and layers. Increasing the epochs seemed to improve the performance but didn't hit the 75% objective.

## Summary
Although I was unable to adjust the model to reach 75% accuracy, it was helpful to see how the adjustments contributed to the outcome. I would recommend using a linear regression model or a different machine learning model to possibly improve predictability. Given the type of data that we are analyzing, it could assist with reaching 75% accuracy.
