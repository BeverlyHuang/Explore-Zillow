# Housing Price Prediction: Time Series vs Machine Learning


### Goal
Real estate prices are always changing. Many models have been created to predict housing prices. This project will use Zillow dataset as an example to explore the performance of time series model and machine learning model on real estate price prediction.

### Conclusion
In order to compare time series and machine learning model in real estate price prediction, this project uses one region as an example to compare the prediction error of both models.

* In time series model, we use both moving average and Holt Winter method. The Moving Average model has 26493 mean squared error, and the Holt Winter model reduces mean squared error from 26493 to 7531.

* In machine learning model, we use linear regression to fit prices of two other regions in the same city to our target region. This gives us 21379 mean squared error.

Thus, when predicting time series data, using time series model (prediction based on trends)is better than machine learning model (prediction based on variables).
