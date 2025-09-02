## 📊 VWRSI Pro — Dynamic Bands Module

VWRSI Pro replaces static RSI thresholds with volatility-adaptive bands:

### Formula
```pine
rsiMean = ta.sma(rsi, bandLength)
rsiDev = ta.stdev(rsi, bandLength)
dynHigh = rsiMean + bandMult * rsiDev
dynLow  = rsiMean - bandMult * rsiDev
```
These bands are not static—they reflect volume-adjusted momentum extremes. 

When RSI enters these zones with strong volume, it signals potential reversal or exhaustion.

<img width="1418" height="881" alt="Screenshot 2025-09-02 142613" src="https://github.com/user-attachments/assets/f1ab6328-9b2a-462c-a507-1b4165dfa19f" />

## ⚠️ Disclaimer
This indicator is provided for educational and informational purposes only. It does not constitute financial advice, investment recommendation, or a solicitation to buy or sell any financial instrument. Trading involves risk, and past performance does not guarantee future results. Users are solely responsible for their own trading decisions and should consult with a licensed financial advisor before acting on any information provided by this tool.
