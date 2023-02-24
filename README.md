# Stock-Market-Prediction-Using-LSTM 📈
Predicting Equity Prices for multiple asset classes. This type of model works for different types of Equities once data is fetched in the form required. 
Pricing equities has been a tough target for most people who try stock markets causing them enormous amount of pilling losses. Here we have used a complex Neural Network to predict equity prices based on previous historical data. 

# What is LSTM? 🤖
<p>LSTM stands for Long Short Term Memory. Long Short-Term Memory (LSTM) is a type of Recurrent Neural Network (RNN) that is specifically designed to handle sequential data, such as time series, speech, and text. LSTM networks are capable of learning long-term dependencies in sequential data, which makes them well suited for tasks such as language translation, speech recognition, and time series forecasting.
<br>
A traditional RNN has a single hidden state that is passed through time, which can make it difficult for the network to learn long-term dependencies. LSTMs address this problem by introducing a memory cell, which is a container that can hold information for an extended period of time. The memory cell is controlled by three gates: the input gate, the forget gate, and the output gate. These gates decide what information to add to, remove from, and output from the memory cell.</p>

# How does the code Flow? ⏳
<ul>
<li>Step 1- Importing Python Libraries </li>
<li>Step 2 - Dataset Reading </li>
<li>Step 3 - Pre Processing the data and getting the Overall Structure of the data to start with data modelling</li>
<li>Step 4 - Plotting the chart against the historical prices. </li>
<li>Step 5 - Plot the Closing prices in different charts - Trend || Seasonal || Resid </li>
<li>Step 6 - Splitting the data into the ratio of 70% Training Dataset and 30%Test Dataset</li>
<li>Step 7 - Windowing Dataset</li>
<li>Step 8 - <b>Implementing LSTM will start from here</b> || The above steps can be considered as Pre-Processing and Splitting of the Dataset</li>
<li>Step 9 - Import Keras and Tensorflow libraries for LSTM Network </li>
<li>Step 10 - Fitting data to the model and Selecting the number of ePochs required</li>
<li>Step 11 - Get a <pred> set of values and then evaluate the model and calculate Root Mean Square Error and R-Squared Score</li>
<li>Step 12 - Plot the stock price and Predicted values || The difference between the predicted value and stock prices is called the Root Mean Square Error (RMSE)</li>
<li>Step 13 - Predicting Future Price Update - For making it as realtime as possible, We have predicted 30 day trend</li>
<li>Step 14 - Plotting Past Prices and Predicted Values for the next 30 days </li>
</ul>

# Stocks and Equities test runs 🧪
<ul>
<li>Apple</li>
<li>HDFC Bank</li>
<li>India VIX</li>
<li>Nifty FMCG</li>
<li>Nifty IT</li>
<li>Nifty 100</li>
<li>Nifty 50</li>
<li>Nifty 500</li>
<li>Nifty Auto</li>
<li>Nifty Bank</li>
<li>Nifty Metal</li>
<li>Nifty Midcap</li>
<li>Nifty Pharma</li>
<li>Nifty Smallcap</li>
<li>Reliance Industries </li>
<li>Tata Global Products</li>
</ul>

# How to use it? 💻
<ul>
<li>Download "Index" Jupyter Notebook file of main</li>
<li>Fetch equity Database from exchange</li>
<li>Assign the database in the file [A comment has been mentioned for the same]</li>
<li>Run the file </li>
<li>Results are then fetched </li>
</ul>


# Development is still under Process    


#start with readme