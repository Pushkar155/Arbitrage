# Arbitrage Detector

A Python-based project to identify arbitrage opportunities between Binance and Solana decentralized exchanges (DEX). This tool fetches real-time token prices, calculates effective costs after fees, and highlights profitable trading opportunities.

---

## Features

- **Real-Time Price Fetching:** Get trading pair prices from Binance and Solana DEX.
- **Fee Calculation:** Accounts for maker fees, swap fees, and transaction costs.
- **Arbitrage Opportunities:** Identify viable arbitrage opportunities for tokens like DOGE and ETH.

---

## Folder Structure

- **`src/`**
  - `binance_api.py`: Functions for interacting with Binance API.
  - `solana_api.py`: Functions for fetching Solana DEX prices.
  - `fees.py`: Logic for calculating fees.
  - `arbitrage.py`: Logic for detecting arbitrage opportunities.
  - `main.py`: Main script to run the application.

- **`tests/`**
  - Unit tests for validating individual modules.

- **`config/`**
  - Store API keys, URLs, and sensitive data securely.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/arbitrage-detector.git
   cd arbitrage-detector
