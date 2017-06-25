# OpenExpertAdvisor

Open source expert advisor for the Metatrader4 (MQL4) platform.

# Strategy

This strategy focus mainly on the swiss frank (best results are with EURCHF) and trades at the end of the New York session. The rules are simple; buy when oversold, sell when overbought.

The take profit and stop loss are determined from the symbol's volatility using the average true range (ATR) of the its price.

# Settings

![OpenExpertAdvisor](http://i.imgur.com/JVrYvIv.png)

# Performance

![OpenExpertAdvisor](http://i.imgur.com/6X8gWQb.png)

![OpenExpertAdvisor](http://i.imgur.com/qMW58jV.png)

![OpenExpertAdvisor](http://i.imgur.com/6JD2SyQ.png)

# Notes

This is more of a proof-of-concept than a real trading EA. While the results may seem alluring, the slippage, latency and broker commission would not allow this strategy to be profitable. Do not use this with a real trading account on a Forex broker, you will loose money.
