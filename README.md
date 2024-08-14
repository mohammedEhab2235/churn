# churn
A model to predict which customer to unsubscribe the network and who will not

importing all needed libraies (pandas, numby,sklearn,seaborn,matplotlib) to use it in cleaning data and preprocessing then visulaization and training and test the model 

cleaning data by removing all duplicates and null values

changing the (Exited) column to (Churn) to more obvious

drawing a plot to see the range of age of how many people unsubscribe in each age

and onther plot to see how balance effects people  

changing the coulmn (gender) from string to int so that the model can understands with encoder functions

spliting the (geography) column to other columns with (True) and (False)

spliting the features from result to take the input and output to model

training the model with (Random Forst) model

showing the (confusion matrix) to the how many model predicted right and how many wrong

and show the accuracy of the model

seeing the most efficting column on model is (Age)

trying another model (KNN) and (linear regression) and its not good with this data the accuracy is lower than (Random Forst)
