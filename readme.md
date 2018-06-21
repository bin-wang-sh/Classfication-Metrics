#  Classfication Metrics for Udacity DS exercise
In this lesson you gained some insight into a number of techniques used to understand how well our model is performing. This notebook is aimed at giving you some practice with the metrics specifically related to classification problems. With that in mind, we will again be looking at the spam dataset from the earlier lessons.
First, run the cell below to prepare the data and instantiate a number of different models. Then do the following:  
Step 1: Now, fit each of the above models to the appropriate data. Answer the following question to assure that you fit the models correctly.  
Step 2: Now make predictions for each of your models on the data that will allow you to understand how well our model will extend to new data. Then correctly add the strings to the set in the following cell.  
Step 3: As an example of how this will work for the upcoming questions, run the cell below. Fill in the below function to calculate accuracy, and then compare your answer to the built in to assure you are correct.  
Step 4: Fill in the function to calculate precision, and then compare your answer to the built in to assure you are correct.  
Step 5: Fill in the function to calculate recall, and then compare your answer to the built in to assure you are correct.  
Step 6: Fill in the function to calculate f1-score, and then compare your answer to the built in to assure you are correct.  
Step 7: Now that you have calculated a number of different metrics, let's tie that to when we might use one versus another. Use the dictionary below to match a metric to each statement that identifies when you would want to use that metric.  
Step 8: Given what you know about the metrics now, use this information to correctly match the appropriate model to when it would be best to use each in the dictionary below.  
Step 9: Using the fbeta_score works similar to most of the other metrics in sklearn, but you also need to set beta as your weighting between precision and recall. Use the space below to show that you can use fbeta in sklearn to replicate your f1-score from above. If in the future you want to use a different weighting, this article does an amazing job of explaining how you might adjust beta for different situations.  
Step 10: Building ROC curves in python is a pretty involved process on your own. I wrote the function below to assist with the process and make it easier for you to do so in the future as well. Try it out using one of the other classifiers you created above to see how it compares to the random forest model below.
