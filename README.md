# Store_Item_Demand_Forecasting

The goal is to predict sales for 10 stores with 50 items each. In a first step statistical models are used. Second, a recurrent neural network is used.

Data: [Store Item Demand Forecasting](https://www.kaggle.com/c/demand-forecasting-kernels-only)


## Files
`01_Data_Exploration`

The data is explored. We see how many samples we have, how clean the data is etc. Next, we search for patterns in the data which could be helpful for the prediction as well as which influences our model choice for it.

`02_Statistical_Models`

After identifying relevant patterns, auto regressive models are used to predict the future sales (demand).

'03_'

Predictions with an LSTM. This is the final network configuration. Various network topologies and hyper parameters have been tried to come up with this configuration.

