# Neural_Network_Charity_Analysis
# Overview of the analysis
## Purpose
The purpose of the study is to use the features in the provided dataset which is a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years, and help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Results: Using bulleted lists and images to support your answers, address the following questions.
#### What variable(s) are considered the target(s) for your model?
- The target variable is "is-successful".


#### What variable(s) are considered to be the features for your model?
- APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS, and	ASK_AMT.



#### What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME variables were neither targets nor feature therefore were dropped from the dataframe.


### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- For input layer I added the number of variables in our feature DataFrame which is 43.
- I added two hidden layers and for the first hidden layer the number of neurons are 80 and for second it is 30.
- I selected relu activation function for the hidden layers and sigmoid activation function for output layer.
- I used relu fuction to identify nonlinear characteristics from the input values.
- I selected sigmoid function to predict the probability that an applicants will be successfull.
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

