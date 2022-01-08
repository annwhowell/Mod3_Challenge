# Mod3_Challenge (Using Pandas for Bitcoin Arbitrage)

This is a python Pandas project that uses a Jupyter Lab notebook called crypto_arbitrage.ipynb to analyze Bitcoin prices across time (Jan-Mar 2018) from two different exchanges (Bitstamp and Coinbase) to identify possible opportunities for arbitrage. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* Pandas - to handle financial data analysis 

* Jupyter Lab - IDE program

* Path - from pathlib to handle relative paths to data files

* Matplotlib - for plotting graphs of data

* [csv] - import csv to allow for proper reading and writing to csv files

---

## Import Guide

Before running the application first import the following dependencies.

```python
  import pandas as pd
  from pathlib import Path
  %matplotlib inline  
    
```

---

## Usage

To use the crypto_arbitrage.ipynb application launch the notebook in Jupyter Lab

The program requires two data files - one for each exchange which are imported using date_time format parameters:
```
./Resources/bitstamp.csv
The bitstamp.csv file contains 129540 items from dates 1/1/2018 to 03/30/2018 in columns Open, High, Low, Close, BTC Volume, USD Volume, Weighted Price.

./Resources/coinbase.csv
The coinbase.csv file contains 129540 items from dates 1/1/2018 to 03/30/2018 in columns Open, High, Low, Close, BTC Volume, USD Volume, Weighted Price.

```


## Analysis dates
---
The application assesses differences between the to exchanges on three different dates:

Early: Jan 2, 2018
Middle: Jan 28, 2018
Late: March 30, 2018

---


## Analysis dates
---
Data is plotted using line graphs and box plots

## Contributors

Brought to you by Ann Howell with support from Rice FinTech Bootcamp.

---

## License

MIT