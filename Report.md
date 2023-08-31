# deep-learning-challenge
## Step 4: Write a Report on the Neural Network Model
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

# Purpose of this analysis.


What variable(s) are the target(s) for your model?
- The variable in which we are attempting to predict is the 'IS_SUCCESSFUL' column from the initial application data frame.

What variable(s) are the features for your model? 
- The feature variables were found within the datafram. The affiliated columns are as follows:
    - AFFILIATION
    - CLASSIFICATION
    - USE_CASE
    - ORGANIZATION
    - STATUS
    - INCOME_AMT
    - SPECIAL_CONSIDERATIONS 
    - ASK_AMT
    

What variable(s) should be removed from the input data because they are neither targets nor features? 
- The irrelevant variables were the 'EIN' and 'NAME' columns. Because of their inability to affect the model's accuracy, they were dropped from the dataframe.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 
- I used 9 hidden nodes in layer 1 and 18 hidden nodes in layer 2. I used relu for my activation after considering that it does not activate all the neurons at the same time.

Were you able to achieve the target model performance? 
- No, my accuracy sat at 63%.

What steps did you take in your attempts to increase model performance? 
- In order to strive for an increased model performance, I toyed with multiple layers, activation functions, and edited the epochs.

# Summary: 
 
All in all, the developed model was unsuccessful at achieving an accuracy percentage higher than 63%. This indicates that the model's performance could be improved through better clean up methods or through utilizing a different classification model to predict the success of applicants.
