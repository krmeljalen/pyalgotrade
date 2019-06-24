# pyalgotrade
Modded pyalgotrade v0.20 that supports all crypto fiat pairs on Bitstamp.

### Installation

To use local version of pyalgotrade just copy it in the same folder as your python script runs. To make sure local one is used, you can even uninstall pyalgotrade that was installed through pip.

### Usage

All LiveFeed and LiveBroker now support 2 arguments. 

Example:

`barFeed = barfeed.LiveTradeFeed("LTC", "EUR")`

If you call it with:

`barFeed = barfeed.LiveTradeFeed()`

It will use BTC/USD as non modded version, for backward compatibility.

### Note

There might be some bugs around so try things with papertrader first, then go with live one.

### Credits

Me, Myself and I.

### License

Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) - [https://creativecommons.org/licenses/by-nc-nd/4.0/]
