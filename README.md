# Store_Item_Demand_Forecasting

The goal is to predict sales for 10 stores with 50 items each. In a first step statistical models ARIMA and SARIMA are used. Second, a LSTM is used. The statistical models are easier to set up and apply, while also delivering better results in this case. Better scores with the LSTM could be achieved with further hyper parameter tuning.


Data: [Store Item Demand Forecasting](https://www.kaggle.com/c/demand-forecasting-kernels-only)


## Files
`01_Data_Exploration`

The data is explored. We see how many samples we have, how clean the data is etc. Next, we search for patterns in the data which could be helpful for the prediction as well as which influences our model choice for it.

`02_Statistical_Models`

After identifying relevant patterns, auto regressive models are used to predict the future sales (demand).

`03_LSTM`

Predictions with a LSTM. This is the final model. Various network topologies and hyper parameters have been tried to come up with this configuration.

