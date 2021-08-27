# NYTaxiPrice
A basic overview of feature selection and sklearn for taxi fare prediction in New York. XGBoost is used in conjunction with Optuna for hyperparameter tuning.

A lot more work can be done on this but it illustrates the basics of creating new features to improve our predictions and plotting our data to identify outliers. Further work can be done here to eliminate outliers, but out of 2 million observations removing these few remaining outliers is unlikely to have any noticeable change.

The original competition dataset has 54 million observations. Training using this would take a long time, so we use the first 2 million rows for this model. The train data provided in this repo is only 1 million rows due to file size constraints. If you are interested in the full data it can be found [here on Kaggle.](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data) I have also trained this model in my local environment with the entire dataset and saw minor improvements, so I would encourage any learners to try training the model with all the data if possible.