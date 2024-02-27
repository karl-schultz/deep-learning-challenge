# deep-learning-challenge
OVERVIEW: The purpose of our project is to use neural networks to create a machine learning model that can determine if
non-profit applicants will be succesful if funded by Alphabet Soup.

RESULTS: 
DATA PREPROCESSING: 1.) What variables are the target of our model? The "Is-Succesful" column is the target or dependent variable of our model.
2.) What variables are the features for your model? APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT. NAME is exempted from the initial model but is used in the optimized model. 
3.) What variables are neither and should be removed from the input data? EIN, SPECIAL_CONSIDERATIONS, STATUS. In the initial model NAME is also exempted but not in the optimized model.
COMPILING, TRAINING, AND EVALUATING THE MODEL: 1.) How many neurons, layers, and and activation functions did you select for your neural network model, and why? Five toal layers for our optimized model: An input layer, three hidden layers, and an ouptut layer.  Changing the 2nd and 3rd activation functions in the hidden layers to 'sigmoid' also helps boost the accuracy of the optimized model. 
2.) Were you able to achieve the target model performance? Yes, we were in our optimized model, if not our initial model.
3.) What steps did you take to try and increase model performance? We converted the NAME column into dummy variables to use in our model. We also added a third hidden layer and used "sigmoid" activation function for the 2nd and 3rd hidden layers.
