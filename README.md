## Summary

### Overview:
Project aims to demonstrate use of LSTM Encoder-Decoder model for time series forecasting. One can use any dataset but for the purpose of this project, I have tried to predict spot freight prices / rates timely and accurately with LSTM Encoder-Decoder deep learning technique.

*Freight prices / rates trades details are openly available from deals. Freight prices / rates are timely updated from high volume of trade.
Fixture trade deals are often kept private to avoid revealing market movements. Traders and freighters often hide demand and supply levels.* 

### Data Source:
The target variable in the data is denoted by "Target-Australia/China c5" index. The focus is not on the meaning/significance of the target variable rather the technique that can be generalized to any time series.
There are several other variables in the data that were free source and were collected from Bloomberg and Reuters. As students of Singapore Managament University, we had access to run the systems and extract this data. 

### Future Work:
Spot Freight Price Index is like stock market index, it is very volatile and sentiment driven. Hence, future work may include improving feature selection, collecting text data, eg. news, announcement to predict spot market using NLP-based features too. Also, utilizing the other features that were present in the data might prove useful.

### Reference:
https://machinelearningmastery.com/how-to-develop-lstm-models-for-time-series-forecasting/
