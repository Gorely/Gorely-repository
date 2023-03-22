Outflow of mobile operator customers from «Not-a-Single-Break.com»

The telecom operator "Not-a-Single-Break.com" wants to learn how to predict the outflow of customers. 
If it turns out that the user plans to leave, he will be offered promotional codes and special conditions. 
The operator's team collected personal data about some customers, information about their tariffs and contracts.

The operator provides two main types of services:

Fixed telephone connection. It is possible to connect a telephone set to several lines at the same time.
Internet. The connection can be of two types: via a telephone line (DSL , from the English * digital subscriber line , "digital subscriber line") 
or fiber optic cable ( Fiber optic *).

Work purpose

- Build a model to help predict customer exit.
- ROC-AUC metric is used for evaluation and training. Additionally, we can check - F1 and Accuracy.
- Minimum threshold for a successful model - AUC-ROC >= 0.85
- Additional condition: When dividing into samples, the ratio of training to test = 3/1.

Project plan

- Open and examine the data.
- Analyze the data.
- Prepare the data for training the model.
- Train the models and conduct cross-validation, choose the best model
- Consider the result of its work on the metric on the test sample.
- General conclusion.

General conclusion

- Data is open and explored.
- The tables are merged by the values of the customerID column.
- An analysis of multicollinearity and business analysis of possible reasons for the departure of clients was carried out.
- The data is divided into training and test sets (3/1).
- The goals and signs of learning are highlighted (the goal is EndDate - the client left or not).
- Encoded data in the training sample, which are specified as object in the digital display of categorical variables.
- The data in the test sample is coded separately.
- Trained several models including tree models, forest and gradient boosting (CatBoost). Cross-validation has been carried out.
- It was determined that the CatBoost model was the best fit for our data.
- The best model (CatBoost) was tested on the test sample, the accuracy metric was calculated, its result is 0.807, which is more than with cross-validation.
- The AUC-ROC metric on the test sample is 0.852, which means that our classifier will be able to distinguish between positive and negative class values. 
- This is because the classifier can detect more true positives and true negatives than false negatives and false positives.
- I've analyzed the signs by which the model makes predictions, and it was found that the most important sign is the type of contract, 
the second after it is the amount of spending per month by the client, 
and the most "useless" for the model is whether the client has a spouse or not .
