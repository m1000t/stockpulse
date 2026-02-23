# 📈 StockPulse — AI Stock Trading Analyzer

> A sleek, AI-powered stock analysis tool that gives you **BUY / SELL / HOLD signals** with full technical breakdowns — built for beginner to intermediate traders.

![StockPulse](https://img.shields.io/badge/Powered%20By-Claude%20AI-00ff88?style=for-the-badge&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![HTML](https://img.shields.io/badge/Built%20With-HTML%2FJS-orange?style=for-the-badge)

---

## 🚀 Live Demo

👉 **[Launch StockPulse](https://yourusername.github.io/stockpulse)**

---

## 📸 What It Does

Type any stock ticker (NVDA, AAPL, TSLA, SPY...) and get a full AI-researched report in seconds:

| Feature | Description |
|---|---|
| 🟢 **BUY / SELL / HOLD Signal** | AI verdict with confidence score out of 10 |
| 📊 **12-Week Price Chart** | Visual price history with trend coloring |
| 📐 **Support & Resistance** | Key price levels with % distance from current price |
| 🔢 **RSI & MACD** | Real technical indicators explained in plain English |
| 📉 **Options Flow** | Implied volatility, IV rank, put/call ratio |
| 📰 **News Sentiment** | Latest headlines scored bullish / bearish / neutral |
| 🎯 **Analyst Targets** | Wall Street price targets and ratings |
| 📅 **Earnings Dates** | Upcoming earnings alerts so you don't get caught off guard |

---

## 🛠️ How It Works

```
User enters ticker
       ↓
Claude AI searches the web for live market data
       ↓
Fetches: price, RSI, MACD, SMA50/200, news, options data
       ↓
AI analyzes all data and generates BUY/SELL/HOLD signal
       ↓
Full report rendered with charts and beginner explanations
```

The app uses the **Anthropic Claude API** with built-in web search to pull real-time market data — no third-party data subscriptions needed.

---

## ⚡ Quick Start

### Option 1 — Just open it
Download `stock-analyzer.html` and open it in any browser. That's it.

### Option 2 — Host on GitHub Pages
1. Fork this repo
2. Go to **Settings → Pages → Branch: main → Save**
3. Visit `https://yourusername.github.io/stockpulse`

---

## 🧠 Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript — zero dependencies, zero build step
- **Charts:** [Chart.js](https://www.chartjs.org/)
- **AI & Data:** [Anthropic Claude API](https://anthropic.com) with web search tool
- **Fonts:** Google Fonts (Syne + Space Mono)

---

## 📊 Indicators Explained

### RSI (Relative Strength Index)
Measures if a stock is overbought or oversold on a scale of 0–100.
- **Above 70** = Overbought (potential sell signal)
- **Below 30** = Oversold (potential buy signal)
- **40–60** = Neutral zone

### MACD (Moving Average Convergence Divergence)
Shows momentum and trend direction.
- **MACD above signal line** = Bullish momentum
- **MACD below signal line** = Bearish momentum
- **Histogram growing** = Momentum accelerating

### SMA 50 / SMA 200 (Simple Moving Averages)
Average closing prices over 50 and 200 days.
- **Price above both MAs** = Strong uptrend
- **50 MA crosses above 200 MA** = "Golden Cross" — very bullish signal
- **50 MA crosses below 200 MA** = "Death Cross" — bearish signal

### Support & Resistance
- **Support** = Price level where buyers historically step in (floor)
- **Resistance** = Price level where sellers historically take profits (ceiling)

---

## ⚠️ Disclaimer

> **This tool is for educational purposes only and is NOT financial advice.**
> 
> Always do your own research before making any investment decisions. Options trading involves significant risk and is not suitable for all investors. Past performance does not guarantee future results.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Contributing

Pull requests welcome! Ideas for improvement:
- [ ] Portfolio tracker (analyze multiple tickers at once)
- [ ] Price alerts via email/SMS
- [ ] Historical signal backtesting
- [ ] Dark/light theme toggle
- [ ] Export report as PDF

---


