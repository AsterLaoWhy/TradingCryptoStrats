# TradingCryptoStrats
![image](https://img.shields.io/badge/Lifecycle-Work%20in%20Progress-yellow)
 <br />
An attempt at using supervised, unsupervised learning, and LSTM NN to trade various crypto currencies.The goal is to be able to semi-passively trade crypto currency at a profit

<br />

# Data
Data was pulled from Kaggle for historical crypto currency data from April 2013 to June 2020. I also have an account able to pull current crypto data for more current backtesting.

# Steps taken

 - Look at the data from 2017-2020 due to time (allowing processes to not take a week) and behavior similarity (before 2017, the price was relatively stable)
 - Scale the data
 - Run Log regression, and gradient boosting classification then compare the results to an LSTM Neural Network
 - Do some feature reduction with UMAP and PCA to see if there is too much noise on the predictions
 - Realize this is a task that needs a ton of time and tweaking
 
 # Next steps
  - learn more about strategies regarding trading cryptocurrency/stocks to impliment
  - add stop loss and buy confidence weights
  - create better features
  - add more sophisticated buy and sell conditions 
