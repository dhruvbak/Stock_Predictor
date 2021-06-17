# Stock_Predictor
#### HDFC Bank Stock prediction for March-April 2021 using RNN(LSTM)

The opening price of past 60 days is used to give output of 61st day opening price of stock and so on. This is used as training set and is fitted in Keras Sequential model of 5 layers (4 LSTM and 1 dense). The stock price of next 40 days is predicted using this model and is plotted along with actual opening values of stock.

LSTMs are type of RNN which avoids vanishing gradient problem with help of forget gate.

RNN is deep learning algorithm output from previous step are fed as input to the current step.
 
 
<br /> 
<br /> 
  
#### Links

RNN: https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/

LSTM: https://en.wikipedia.org/wiki/Long_short-term_memory 

Keras Sequential: https://keras.io/guides/sequential_model/ 

Dataset: https://www.kaggle.com/rohanrao/nifty50-stock-market-data?select=HDFCBANK.csv 


