# project2_kkcs: Crypto returns and predicted returns

## Purpose

To review three main crypto currencies (BTC / LTC / ETH) and see which one have higher actual returns and higher predicted returns

## Approach

* Use SMA to calculate portfolio returns for each crypto
* Use three different models (SMA SVM / DEMA SVM / DTC) to calculate predicted returns
* Use else - if to generate initaite buy/sell 
* Use airflow to create a loop function to have buy/sell fuction run automatically

## Results

* LTC have lower returns than BTC and ETH
* BTC has better returns and model accuracy than ETH and LTC
