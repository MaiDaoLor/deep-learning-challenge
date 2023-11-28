# Report on the Neural Network Model for Alphabet Soup Charity 

The purpose of this analysis is to sleect applicants for funding with the best chance of success in their ventures. In this report we wil be reviewing the [AlphabetSoupCharity_1.ipynb](C:\Users\16123\OneDrive\Desktop\deep_learning_challenge\deep-learning-challenge\Starter_code\AlphabetSoupCharity_1.ipynb) (first model) and [AlphabetSoupCharity_Optimzation.ipynb](C:\Users\16123\OneDrive\Desktop\deep_learning_challenge\deep-learning-challenge\Starter_code\AlphabetSoupCharity_Optimzation.ipynb) (second model). 

## Data Preprocessing
1. What variable(s) are the target(s) for your model?
    - The target for both model is the 'IS_SUCCESSFUL' column which is "y". 
2. What variable(s) are the features for your model?
    - For the first model, the features are all the columns except for the 'IS_SUCCESSFUL', 'EIN', and 'NAME column which is for "X".
    - For the second, the features are all the columns except for the 'IS_SUCCESSFUL', 'EIN', 'NAME', and 'SPECIAL_CONSIDERATION' column which is for "X".
3. What variable(s) should be removed from the input data because they are neither targets nor features?
    - The 'EIN' and 'NAME' column was dropped from application_df.
    - The 'EIN', 'NAME', and 'SPECIAL_CONSIDERATIONS' in application_df was dropped.

## Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?     
    - For the first model I use 80 for the the first hidden layers and 30 neurons for the second layers.
    - The second model, I attempted with 16, 10, and 8 neurons and 3 hidden nodes layers. 
    - The reason for these selection was mostly out of curiosity. 
2. Were you able to achieve the target model performance?
    - I was unable to achieve the targe model performance for both. The first attempt accuracy was at 0.5197667479515076. For the second model I made 4 attempts and the final accuracy score is 0.7258309125900269. I was unable to achieve a target predictive accuacy higher than 75%. 
3. What steps did you take in your attempts to increase model performance?
    - I added a third hidden layer, with different neurons and and activation functions. 