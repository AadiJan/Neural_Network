# **Neural_Network**

## **Overview of the Analysis:**
The intent of the project is to utilize Machine Learning and Neural Networks to predict whether applicants will be successful if funded by Alphabet Soup. This is by using the features in the dataset which helped create a binary classifier. 
The data was from Alphabet Soup's business team, a csv file containing more tham 34,000 organizations that have received funding from Aplhabet Soup over the years. Some of the columns that captures metadata about each organization such as EIN, NAME, APPLICATION_TYPE, ORGANIZATION and 8 other columns. 
The steps taken to predict are as follows,
*  Preprocessing Data for a Neural Network Model
*  Compile, Train, and Evaluate the Model
*  Optimize the Model

## **Results:**
*Data Preprocessing*
* What variable(s) are considered the target(s) for your model? 
    IS_SUCCESSFUL
* What variable(s) are considered to be the features for your model?
    All columns 
* What variable(s) are neither targets nor features, and should be removed from the input data?
    EIN and NAME. This column does not impact the results. 


*Compiling, Training, and Evaluating the Model*
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
   The model comprises two hidden layers and an input feature. The first hidden layer and 80 neurons and second has 50 neurons, with an activation function. Bothe the layers have "relu" as activation function and "sigmoid" as the output layer. 
![output](https://github.com/AadiJan/Neural_Network/blob/5fa9a677b57c548f2ffdaf7ee6555d3370c44ce1/Activation_fun_output.PNG) 

* Were you able to achieve the target model performance?
    The target was to achive 75%. However, the model was not able to meet the target.
    
 * What steps did you take to try and increase model performance?
       The number of epochs and number of neurons for each layer were modified to optimize the model. 
       
 ## **Summary:**
 The most accuracy the model was able to achive was 72.48% (accuracy = 0.7248979806900024). This does not meet the required target of 75%. However, with additional data added to the model, I belive the accuracy can be increased.
