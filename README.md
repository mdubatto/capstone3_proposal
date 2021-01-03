# Capstone 3 Proposal


### Option 1:
[Walmart Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data)
* Forecast sales for each department in each store. The dataset includes extra fields such as CPI, Temp, Unemployment, etc.
* I was reading Skylar's book and I think I might be able to use an LSTM on the trend and concatenate that with another NN based on the other inputs before the final output layer. I'm not sure if that's how time series like this one is usually handled, but I think it might work.
### Option 2:
[Brazilian E-Commerce](https://www.kaggle.com/olistbr/brazilian-ecommerce?select=olist_order_reviews_dataset.csv)
* I'd want to forecast the monthly order volumes for each item using ARIMA and LSTM models.
* I was thinking I can create additional features based on the product ratings (if the number of reviews/month of an item is increasing and the average rating is also high it might impact the # of orders received).

### Option 3:
[Flight Cancellations](https://www.kaggle.com/usdot/flight-delays?select=flights.csv)
* Predict whether a flight will be cancelled