# StatisticalBacktestingFreqtrade

This notebook helps you define a proper timerange for training, validating and testing your strategy.

How to use:

1. Edit this line to your currency location:

	`token = pd.read_feather('user_data/data/binance/futures/BTC_USDT_USDT-1d-futures.feather')`

	(use read\_hdf or read\_json if you have your database in another format)

2. Optionally edit start\_date and end\_date to your desire timeframe for testing.

3. Then use one of the 2 methods to get timeranges for testing and validating your strategy.