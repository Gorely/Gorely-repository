Bank clients churning

Customers began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.
It is necessary to predict whether the client will leave the bank in the near future or not. You are provided with historical data on customer behavior and termination of agreements with the bank.
Build a model with an extremely large F1-measure. To pass the project successfully, you need to bring the metric to 0.59. Check the F1-measure on the test set yourself.
Additionally, measure the AUC-ROC, compare its value with the F1-measure.

Work plan

Import everything needed.
Open and study the data, prepare the data for work.
Highlight signs and targets.
Divide data into samples.
Scale features.
Train the decision tree model, check the error matrix, accuracy, recall and F1-measure.
Train a random forest model, find the best hyperparameters.
Train a regression model, compare with other models.
Make a conclusion about the balance of classes.
Fight the imbalance, if necessary.
Test the model on a test sample, calculate the AUC-ROC metric.
Compare our model with a simple "guesser".

General conclusion

I've trained decision tree, random forest, and logistic regression models and found that the random forest model was the best fit for our data.
I've brought the F1-measure higher than 0,59 so our model has pass the test.
The AUC-ROC metric on the test sample is high, which means that our classifier will be able to distinguish between positive and negative class values. This is because the classifier can detect more true positives and true negatives than false negatives and false positives.
In comparison with the simple classifier DummyClassifier, our model showed the best results in terms of the accuracy metric.
In addition, we analyzed the features by which the model makes predictions, and found that the most important feature is the client's age, the second after it is the number of bank products used, and the most "useless" feature for the model is residence in Spain.
