***bitprice***

**A Bitcoin Price Tracking Service with Python**

Being such a volatile cryptocurrency, wouldn't it be nice for Bitcoin investors
to be able to track and be alerted of sudden price swings in their crypto portfolio?

Enter bitprice.

Using Coinmarketcap's API this Python app will use the data to trigger the alerts for you.

The two applets we will create via the great automation website IFTTT.

First we retrieve the CoinMarketCap latest bitcoin price to ensure everything is working in the *Python Console*.

For Example:

>>> import requests
>>> coin_api_url = 'https://api.coinmarketcap.com/v1/ticker/
>>> response = requests.get(coin_api_url)
