***Data Preprocessing***

What variable(s) are the target(s) for your model?
* The target of this search is "IS SUCCESSFUL" from the dataset

What variable(s) are the features for your model?
* the features are all other variables other then "IS SUCESSFUL"

What variable(s) should be removed from the input data because they are neither targets nor features?
* I removed the variables EIN, and NAME since they are identifiers and not fluctuating data for the model. 

***Compiling, Training, and Evaluating the Model***

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* I utilized a tuner to test a wide range of layer types and nueron totals. Having an adaptive model is the best way to get as accurate of a result as possible.

Were you able to achieve the target model performance?
* no, the top result was not able to break the 75% goal

What steps did you take in your attempts to increase model performance?
* I made many changes ranging from changing the number of steps, increasing epoches, implementing a stop early function to increase the amount of tests in the same time. I even increased the diversity of activation without being able to reach the goal.

***Summary:***

Due to only being able to achieve a 73 with a robust and diverse model leads me to think the exploration should be done within the data itself. It could be possible some columns are creating misleading trends, affecting the results we came to.