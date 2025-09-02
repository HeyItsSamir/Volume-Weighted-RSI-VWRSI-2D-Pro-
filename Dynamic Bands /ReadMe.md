## 📊 VWRSI Pro — Dynamic Bands Module

VWRSI Pro replaces static RSI thresholds with volatility-adaptive bands:

### 🔧 Formula
```pine
rsiMean = ta.sma(rsi, bandLength)
rsiDev = ta.stdev(rsi, bandLength)
dynHigh = rsiMean + bandMult * rsiDev
dynLow  = rsiMean - bandMult * rsiDev
```
These bands are not static—they reflect volume-adjusted momentum extremes. 

When RSI enters these zones with strong volume, it signals potential reversal or exhaustion.
