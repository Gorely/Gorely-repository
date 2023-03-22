Toxic tweets

- Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. 
- The store needs a tool that will look for toxic comments and submit them for moderation.
- Train the model to classify comments into positive and negative. At your disposal is a dataset with markup on the toxicity of edits.
- Build a model with a quality metric F1 of at least 0.75.

Conclusions

- The data was prepared, it was cleaned from unnecessary characters and lemmatization was carried out.
- A list of stop words is created, the data is divided into learning features and a target feature.
- TF-IDF vectorization of features for training was carried out.
- Trained the Logistic Regression model. F1 on the validation set - 0.778.
- The classification decision tree model was trained. F1 on the validation selection - 0.626
- Trained the CatBoostClassifier model. F1 on the validation set is 0.74, but the training time (compared to Regression) is very long.
- The Logistic Regression model was recognized as the best model.
- F1 of the best model on the test set is 0.771.
