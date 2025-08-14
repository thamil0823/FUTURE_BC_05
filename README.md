# FUTURE_BC_05

# ​ Crypto Portfolio Tracker

A simple React + Vite app that displays real-time prices of your cryptocurrency holdings. Built using the CoinGecko API for live data.

 ## Features

- Fetches current USD prices for selected coins (Bitcoin, Ethereum, Solana).
- Calculates and displays total portfolio value.
- Auto-refresh every minute for up-to-date data.
- Clean, minimal UI for quick insights.

##​ Tech Stack

- **Framework**: React 18
- **Bundler**: Vite
- **HTTP client**: Axios
- **Data source**: CoinGecko API

## ​​ Setup & Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/crypto-tracker.git
   cd crypto-tracker
# ​ Crypto Portfolio Tracker

A simple React + Vite app that displays real-time prices of your cryptocurrency holdings. Built using the CoinGecko API for live data.

## ​ Features

- Fetches current USD prices for selected coins (Bitcoin, Ethereum, Solana).
- Calculates and displays total portfolio value.
- Auto-refresh every minute for up-to-date data.
- Clean, minimal UI for quick insights.

## ​​ Tech Stack

- **Framework**: React 18
- **Bundler**: Vite
- **HTTP client**: Axios
- **Data source**: CoinGecko API

## ​​ Setup & Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/crypto-tracker.git
   cd crypto-tracker

2. Install dependencies:
   npm install

3. Start the dev server:
   npm run dev

4. open http://localhost:5173/ in your browser.

## Project Structure
crypto-tracker/
├── src/
│   ├── components/
│   │   ├── CoinList.jsx         <!-- Lists each coin and its value -->
│   │   └── PortfolioSummary.jsx <!-- Shows total portfolio value -->
│   └── App.jsx                  <!-- App container integrating components -->
├── index.html
└── vite.config.js
