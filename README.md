# COVID-19-Forecasting-using-LSTM

LSTM or Long Short Term Memory is a type of Recurrent Neural Network that can enable you to account for long-term dependencies. It's more powerful and general than GRU. Recurrent Neural Network is a generalization of feedforward neural network that has an internal memory. RNN is recurrent in nature as it performs the same function for every input of data while the output of the current input depends on the past one computation. Long Short-Term Memory (LSTM) networks are a modified version of recurrent neural networks, which makes it easier to remember past data in memory. The vanishing gradient problem of RNN is resolved here. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration. It trains the model by using back-propagation. In an LSTM network, three gates are present: Input Gate, Forget Gate, Output Gate.

In this model, a 32 day window is used to forecast the values of total confirmed cases of COVID 19 in the next 7 days. The data used is upto 19 June 2020 and 7 days are used for validation while the rest are used for training. The results after running the model on the national Indian COVID 19 data and state data of Maharashtra, Gujarat and Delhi are represented as the mean absolute percentage error between the predicted and actual values for the 7 day prediction are listed as follows:

1. India National Data- 0.31280820303655565
2. Maharashtra State Data- 0.658542884147722
3. Gujarat State Data- 1.0116811274795616
4. Delhi State Data- 0.8153422630497
