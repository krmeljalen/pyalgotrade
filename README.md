# pyalgotrade
Modded pyalgotrade v0.20 that supports all crypto fiat pairs on Bitstamp.

### Installation

To use local version of pyalgotrade just copy it in the same folder as your python script runs. To make sure local one is used, you can even uninstall pyalgotrade that was installed through pip.

### Usage

All barfeeds now support 2 arguments:

`barFeed = barfeed.LiveTradeFeed("LTC", "EUR")`

If you call it with:

`barFeed = barfeed.LiveTradeFeed()`

It will use BTC/USD as non modded version, for backward compatibility.

###
