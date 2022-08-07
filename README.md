# Challenge_14

---

## *This is a helpfull program that will analzy the market of a stock to create Sell/Buy strategies with Machine Learning. Feel free to explore my codebase!* 

---

> Modules

## Data Files 

[Data files](Starter_Code/Resources/emerging_markets_ohlcv.csv)

## EVALUATION REPORT

### We analized the moving averages of a stock, using a short and small SMA rolling windows:
###    *Short Window SMA: 4 days
###    *Long Window SMA: 100 days

![Trading Signals](Starter_Code/Resources/Plot_0.png)

---

### After splitting the data and training it we used the SVC classifier model to fit the data and make predictions based on the testing data. 
### We created a cummulative return plot to show both the Actual Returns vs the Strategy Returns. 

![Actual Returns vs Strategy Rreturns](Starter_Code/Resources/Plot_1.png)

### We can observe that the startegy returns provides a slightly better outcome than the actual returns. 