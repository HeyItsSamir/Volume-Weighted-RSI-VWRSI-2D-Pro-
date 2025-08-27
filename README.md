# Volume-Weighted RSI [VWRSI 2D Pro]

A modular RSI indicator that adapts to market context by weighting momentum with volume. Built for traders who demand clarity, control, and precision.

---

## 🔧 Features

- **Volume-Weighted RSI**: Filters out low-volume noise for cleaner signals.
- **Profile-Based Configuration**: Choose from Scalping, Intraday, Swing, Macro, or Custom.
- **RSI MA Overlay**: Optional smoothing with EMA/SMA/RMA/WMA.
- **Buy/Sell Signal Logic**: Toggleable signals with strict mode filtering.
- **Alert Conditions**: Built-in alerts for automation.

---

## ⚙️ Configuration Profiles

| Profile            | RSI Length | MA Length | Use Case            |
|--------------------|------------|-----------|---------------------|
| Scalping (≤30m)    | 21         | 28        | Fast, reactive setups |
| Intraday (1h–D)    | 14         | 14        | Balanced momentum tracking |
| Swing / Weekly     | 10         | 14        | Medium-term setups |
| Macro (Monthly+)   | 9          | 7         | Long-term positioning |
| Custom             | User-defined | User-defined | Full control |

<img width="312" height="320" alt="Configurations" src="https://github.com/user-attachments/assets/1b810888-5c4a-40d2-a0cc-6f7182ba6e42" />

---

## 📈 Signal Logic

| Signal Type | Condition | Strict Mode Filter |
|-------------|-----------|--------------------|
| **Buy**     | RSI crosses above RSI MA | RSI > 55 (vs > 50) |
| **Sell**    | RSI crosses below RSI MA | RSI < 45 (vs < 50) |

Signals are plotted as triangle shapes and can be toggled on/off.

<img width="911" height="866" alt="Signal Logic" src="https://github.com/user-attachments/assets/6f844595-59f7-43f9-b51b-0d8b48e84632" />

---

## 📊 Visual Setup

- RSI line color shifts:  
  - Above 50 → Bullish (Green)  
  - Below 50 → Bearish (Red)
- RSI MA: Customizable color and style
- Overbought/Oversold bands:  
  - 70–100 → Overbought  
  - 30–0 → Oversold  
  - 50 → Trend filter

---

## 🔔 Alerts

- **Buy Signal**: RSI crosses above MA and > 50  
- **Sell Signal**: RSI crosses below MA and < 50

---

## 🧠 Best Practices

- Use longer RSI lengths on lower timeframes to reduce noise.
- Match RSI and MA lengths for smoother overlays.
- EMA for fast signals, SMA for swing setups, RMA/WMA for macro views.
- Combine VWRSI with price action and volume for confirmation.

---

## ⚠️ Disclaimer
This indicator is provided for educational and informational purposes only. It does not constitute financial advice, investment recommendation, or a solicitation to buy or sell any financial instrument. Trading involves risk, and past performance does not guarantee future results. Users are solely responsible for their own trading decisions and should consult with a licensed financial advisor before acting on any information provided by this tool.
