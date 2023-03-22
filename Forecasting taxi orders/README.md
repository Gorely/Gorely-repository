Forecasting taxi orders

The Clear Taxi company has collected historical data on taxi orders at airports. 
To attract more drivers during the peak period, you need to predict the number of taxi orders for the next hour. Build a model for such a prediction.

The value of the RMSE metric on the test set should not exceed 48.

We need:
- Load the data and resample it one hour at a time.
- Analyze the data.
- Train different models with different hyperparameters. Make a test sample of 10% of the original data.
- Check the data on the test sample and draw conclusions.

General conclusion

- The data is open and studied.
- Data analyzed and resampled.
- Created additional features for training models.
- Various models were trained and analyzed on the validation set.
- The CatBoostRegressor model was recognized as the best model.
- The best model was tested on the test sample and the RMSE metric was 46.44.
