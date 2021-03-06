<p align="center"><img src="https://i.imgur.com/e9mJv19.jpg"></p>
<p align="center">
<a href="https://github.com/Petersoj/AlpacaJavaBacktest"><img src="https://img.shields.io/github/license/Petersoj/AlpacaJavaBacktest.svg" alt="License"></a>
</p>

AlpacaJavaBacktest is a simple and fast Stock Trading Algorithm Backtesting Library for Java that uses <a href="https://polygon.io/">Polygon</a> for historic quotes, trades, aggregates, and other data points to give trading algorithm developers a more accurate understanding of what their algorithm might do in a live market. You should have a live trading account with <a href="https://alpaca.markets">Alpaca</a> in order to get a free API key for Polygon to use this backtesting library. This Library uses <a href="https://github.com/mainstringargs/alpaca-java">alpaca-java</a> exclusively as it contains a Polygon Java API and useful POJO classes. This library is community developed.

## To-Do
* Finish 1.0
  * Fetching and caching data via BacktestData
  * Running a backtest
  * UI for charts and algo trades, shows backtest info, aggregates/quotes/trades of a ticker, etc.
* Implement Time updates (e.g. every minute, hour, or day update) 
* Allow for parallel backtests
* Save/Load previous backtests to display on website
* Historical ETB and HTB ticker data
* More stats (like shown in the 'stats' output [here](http://pmorissette.github.io/bt/index.html#a-quick-example))
