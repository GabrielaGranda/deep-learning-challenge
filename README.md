# deep-learning-challenge

<h1>Overview</h1>

This project aims to build a deep learning model to predict the success of organizations funded by Alphabet Soup. By leveraging machine learning and neural networks, the model will analyze a dataset of over 34,000 organizations, using various features to determine the likelihood of success for future applicants. The goal is to provide Alphabet Soup with a reliable tool to identify the most promising candidates for funding based on historical data.

<h1>Results</h1>

<h2>• Data Preprocessing:</h2>

o	What variable(s) are the target(s) for your model?

The target for each model was the IS_SUCCESSFUL column. 

o	What variable(s) are the features for your model?

In the first model were: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
In the optimization options: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT

o	What variable(s) should be removed from the input data because they are neither targets nor features?

In the first model were: EIN, NAME
In the optimization options: EIN

<h2>•	Compiling, Training, and Evaluating the Model:</h2>

o	How many neurons, layers, and activation functions did you select for your neural network model, and why?

In the first model, I used 2 hidden layers, one with 80 neurons and the second with 30 utilizing the RELU activation. In the optimization 1 model, I used 2 hidden layers, one with 30 neurons and the second with 80 utilizing the RELU activation. In the optimization 2 model, I used 2 hidden layers, one with 15 neurons and the second with 8 utilizing the RELU activation. In the optimization 3 model, I used 2 hidden layers, one with 15 neurons and the second with 8 utilizing the RELU and TANH activation.

o	Were you able to achieve the target model performance?

Yes, the best result was with model 2 with an Accuracy of 0.759.

o	What steps did you take in your attempts to increase model performance?

In my analysis, I adjusted the neural network layers to observe changes in model behaviour and the impact of the random state. For the third model, I experimented with the Tanh activation function to assess its influence on performance. However, the results indicated no significant improvement or change in the model's behaviour compared to previous configurations.

<h1>Summary</h1>

The deep learning model achieved an accuracy of 75.99% with a loss of 0.4922, indicating moderate performance in predicting the success of organizations funded by Alphabet Soup. While the model shows some ability to classify the data, its performance could be further improved. A recommendation would be to explore alternative machine learning models, such as Random Forest or Gradient Boosting. These models tend to perform well with structured data and can handle feature importance and interaction more effectively. Implementing one of these models could lead to better accuracy and more robust predictions due to their ability to capture complex relationships in the dataset.
