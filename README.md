Problem Statement:
Consider yourself to be Matt, who is a Deep Learning Engineer at a prestigious Wine firm. You are asked to look into Wine fraud that has occurred recently at your firm. Let's see if Neural Networks can help with this problem!
Requirements:
You'll need to have the latest version of SciKit Learn (>0.18) installed! It is easily installable either through pip or conda
Dataset Used:
We will use the wine data set from the UCI Machine Learning Repository. It has various chemical features of different wines, all grown in the same region in Italy, but the data is labeled by three different possible 0cultivars
 
Tasks to be Done:
a.	Check out the data
B.	Split your data into training and testing sets using SciKit Learn's train_test_split function from model_selection
a.	It is highly recommended to scale your data. You must apply the same scaling to the test set for meaningful results. Use the built-in StandardScaler for standardization.
b.	Train your model using Scikit Learn’s estimator objects
c.	Create an instance of the model by defining the hidden_layer_sizes
d.	Fit the training data to your model
C.	Use predict () method to get predictions
a.	Use SciKit-Learn's built in metrics to evaluate how well our model performed
b.	Extract the MLP weights and biases after training your model

