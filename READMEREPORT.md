For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

1. **Overview** of the analysis: Explain the purpose of this analysis.
    The purpose of the analysis is to create a model to predict if an applicant will be successful based on the data from previous years. 

2. **Results**: Using bulleted lists and images to support your answers, address the following questions:

* Data Preprocessing
  * What variable(s) are the target(s) for your model?
  * What variable(s) are the features for your model?
  * What variable(s) should be removed from the input data because they are neither targets nor features?

    -The target variable: Is successful (was the money used effectively)
    -The feature variables: Application type, affiliation, classification, use case for funding, organization type, active status, income classification (income_amt), special considerations, and funding amount requested (ask_amt)
    -Removed variables: EIN, Name 

* Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
     -There were 44 input features, 80 neruons in the first layer, 30 neurons in the second layer, 2 hidden layers, and 2 different types of activation functions that resulted in the best accuracy score. 
  * Were you able to achieve the target model performance?
    I was not able to achieve the target model performance with my highest accuracy score being 72.59
  * What steps did you take in your attempts to increase model performance?
    I tried to increase performance by adding more neurons and hidden layers but this did not help. 



3. **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
    Based on the results on the deep learning model, adding more than two hidden layers and removing/adding the number of epochs did not have an affect of the performance. A different model could be improved by changing the activation functions. I only tried sigmoid and relu. And perhaps, increasing the number of neurons or hidden layers might help it a fraction of the percentage. 