# deep-learning-challenge
* For this challenge, we were tasking with using TensorFlow to analyze data from the nonprofit organization, Alphabet Soup. The goal of the TensorFlow model is to help the company determine the funding applicants have the highest chances of success. First, we processed the data using sklearn, dropped two columns, and organized the other columns. Then we scaled the training and testing features using the StandardScaler and transform function. The target was set to the 'Is Successful' column, to try and determine the success or failure of the funding applicants. 

* After that, we used Google Colab to evaluate the model and run TensorFlow. This included creating a neural network model, adding hidden layers and outer layers to the function, compiling and training the model, then evaluating the model for loss and accuracy.

* The original model had a 72% accuracy. So we were instructed to alter the model in an attemp to increase the accuracy to 75% or above. First I reduced the number of epochs from 200 to 100. The output was still at 72% accuracy. After that, I left the epochs at 100, but added a third hidden layer with the Sigmoid activation. Nonetheless, the accuracy maintained 72%. 
The jupyter file labeled 'deep learning' has the original model. The jupyter file labeled 'AlphabetSoup' has the modified accuracy attempts. 
