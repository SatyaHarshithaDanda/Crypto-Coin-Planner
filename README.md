# 💰 Crypto Coin Planner

The **Crypto Coin Planner** is a Python-based GUI application that helps users **track and analyze their cryptocurrency investments** in real-time using live price data from the CoinMarketCap API. It visually displays profit/loss statistics and current coin values, making it easy to monitor portfolio performance.

## 🎯 Objective

- Track real-time crypto prices from CoinMarketCap.
- Compute and visualize profit/loss per coin and total investment.
- Provide a user-friendly GUI to monitor your crypto portfolio.

## 🧰 Tools & Technologies Used

- **Python 3**
- **Tkinter** – For building the desktop GUI
- **Requests & JSON** – For making API calls and handling live crypto data
- **CoinMarketCap API** – For real-time cryptocurrency pricing data

## 🚀 Features

- Live fetch of top 300 cryptocurrencies from CoinMarketCap.
- Calculates:
  - 💵 Total paid vs. current value
  - 📈 Profit/loss per coin
  - 📊 Total profit/loss
- Dynamic color coding: green for gains, red for losses.
- Auto-refresh button to update data with current market prices.

## 📊 Portfolio Configuration

Customize the portfolio directly in the `crypto_coin.py` file:

```python
coins = [
    {"symbol": "BTC", "amt_no": 5, "price": 50000},
    {"symbol": "BNB", "amt_no": 12, "price": 500},
    {"symbol": "USDT", "amt_no": 18, "price": 500},
    {"symbol": "ADA", "amt_no": 500, "price": 3}
]
```

## ▶️ How to Run

1. Clone the repository or download the files.
2. Install the required libraries (if not already installed):
   ```bash
   pip install requests
   ```
3. Replace the `CMC_PRO_API_KEY` in `crypto_coin.py` with your own [CoinMarketCap API Key](https://pro.coinmarketcap.com/).
4. Run the application:
   ```bash
   python crypto_coin.py
   ```

## 📸 Screenshots

![Screenshot 2025-05-17 163338](https://github.com/user-attachments/assets/2ff193eb-4f20-455a-bbac-68f0821f1adb)

## 🛡️ Disclaimer

- This is a personal finance tool intended for educational or small-scale use.
- Ensure responsible usage of CoinMarketCap’s API based on your subscription limits.
