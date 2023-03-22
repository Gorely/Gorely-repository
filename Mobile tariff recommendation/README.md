Mobile tariff recommendation

You have at your disposal data on the behavior of customers who have already switched to these tariffs 
(from the draft course "Statistical Data Analysis"). You need to build a model for the classification problem that will select the appropriate rate.

General conclusion

- We divided the data into three samples: 
67% of the data was left for model training,
16.5% sent for validation and
16.5% separated for model testing.
-According to the results of the search for the best prediction model for our data, it turned out to be the RandomForestClassifier model (random forest). 
On the validation set, it showed a prediction accuracy above Random Tree and Logistic Regression (0.81), which is also above the threshold value of 0.75. 
In the future, we will use a depth (depth) equal to 5 and a forest size (est) equal to 7.
-We compared our model with DummyClassifier's simple classification model and found that it performs better. 
A simple classification showed a result of 0.68 on the test sample, which is below the threshold value of 0.75.
-Based on the above, it is safe to say that the Random Forest model is the best for predicting the desired tariff for the user.
