# Neural Network Charity Analysis

![](https://github.com/NAppazeller/Neural_Network_Charity_Analysis/blob/main/Image_1.PNG)
## Overview: 

The purpose of this project is to perform a risk analysis using deep learning neural networks. The overarching goal is to vet charitable organizations for donations and analyze the impact of each donation to ensure the funds are being used effectively.

## Results: 

#### Data Preprocessing
*What variable(s) are considered the target(s) for your model?*

  -The variable that was considered the target for our model was the "IS_SUCCESSFUL" attribute. It was used to determine if an organization effectively utilized a donation.

*What variable(s) are considered to be the features for your model?*

  -Variables that were considered features for our model included APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".
                  
*What variable(s) are neither targets nor features, and should be removed from the input data?*

  -Variables that were neither targets nor features and were removed from the input data inlcuded "EIN", "NAME", "ORGANIZATION", and "STATUS".
  
### Compiling, Training, and Evaluating the Model
*How many neurons, layers, and activation functions did you select for your neural network model, and why?*

![](https://github.com/NAppazeller/Neural_Network_Charity_Analysis/blob/main/Image_2.PNG)

*Were you able to achieve the target model performance?*

  -We were unable to achieve a target predictive accuracy higher than 75%.
  
*What steps did you take to try and increase model performance?*

  -Steps that were taken to increase model performance included removing additional attributes from the analysis, adding neurons and layers, and implementing various activated features.

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
