# NYTaxiPrice
A basic overview of feature selection and sklearn for taxi fare prediction in New York.

A lot more work can be done on this but it illustrates the basics of creating new features to improve our predictions and plotting our data to identify outliers. Looking at pickup latitudes/longitudes and then looking at the generated plot of New York we can see some pickup locations are still outside New York. Further work can be done here to eliminate outliers, but out of a million observations removing these few remaining outliers is unlikely to have any noticeable change.

The original competition dataset has 54 million observations. Training using this would take a long time, so we use the first 1 million rows for this model. The data provided in this repo is only the first 1 million observations due to file size, however if you are interested in the full data it can be found [here on Kaggle.](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data)
