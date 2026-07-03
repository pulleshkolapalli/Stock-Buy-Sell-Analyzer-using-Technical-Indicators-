# 🚀 Stock Buy/Sell Analyzer using Technical Indicators

A DSA-based stock analysis system by team **Signal Analysts** that generates Buy/Sell signals using technical indicators like Moving Average (MA) and Relative Strength Index (RSI), combined with optimized algorithms (Single Transaction O(n), Multiple Transactions O(n), and Dynamic Programming O(nk)) to compute maximum achievable profit from stock price data.

## 🔗 Live Demo

**[Launch the App →](https://stock-buy-sell-analyzer-pk.streamlit.app/)**

## ✨ Features

- 📊 Interactive Streamlit dashboard for visualizing stock trends
- 📈 Buy/Sell signal generation using Moving Average & RSI
- 🧮 Maximum profit computation using multiple algorithmic strategies:
  - Single Transaction — O(n)
  - Multiple Transactions — O(n)
  - Dynamic Programming (at most k transactions) — O(nk)
- 📉 Live price chart visualization with Plotly
- 🎨 Custom-styled UI with HTML/CSS for a polished look

## 🛠️ Tech Stack

- **Python** — core application logic
- **C++** — DSA algorithm implementations (profit-maximization logic)
- **Streamlit** — web app framework
- **Pandas / NumPy** — data handling and numerical computation
- **Plotly** — interactive charting
- **HTML / CSS** — custom UI styling

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `app.py` | Streamlit web app (UI, charts, signal display) |
| `main.cpp`, `stock_analyzer.cpp/.h` | C++ implementations of the trading algorithms |
| `stock_analyzer.exe` | Compiled Windows executable of the C++ analyzer |
| `requirements.txt` | Python dependencies |
| `runtime.txt` | Python version pin for deployment |

## 🚀 Getting Started (Run Locally)

1. Clone this repository:
```bash
   git clone https://github.com/pulleshkolapalli/Stock-Buy-Sell-Analyzer-using-Technical-Indicators-.git
```
2. Install dependencies:
```bash
   pip install -r requirements.txt
```
3. Run the app:
```bash
   streamlit run app.py
```

## 🙋‍♂️ Team

**Signal Analysts** — Kolapalli Hema Pulleshkolapalli and team
GitHub: [@pulleshkolapalli](https://github.com/pulleshkolapalli)

## 📄 License

This project is open source. Feel free to explore, fork, and build upon it.
