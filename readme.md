# How to use

* Create account at https://alpaca.markets/ (paper trading is fine)
* Edit the script and update the variables. There are comments.
* Save and Run the script with PowerShell (tested with pwsh 7.5).
* Monitor the output.

Its configured to only buy stock while market is open, other times it will occasionally update your position/account details.

Currently I have it so that it buys a stock no more than once a day, only if it drops by x% from the open.

You can specify the $ amount for each purchase (and the x% drop to buy at).

It will also perform sales on your positions if they're up by a definable % from your average entry price.

Currently my goal is simply for consistent daily easy buys when a stock drops, without having to monitor the market constantly, as well as profit taking when possible.

Suffice to say, if the stock doesn't drop the x% in a day, that stock won't have a buy for that day. Same for sales.
