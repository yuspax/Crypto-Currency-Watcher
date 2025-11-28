# Crypto-Currency-Watcher
A simple Python script to monitor the real-time price of any cryptocurrency pair on Binance.

## Features

- Fetches the latest price every 10 seconds
- Supports any Binance trading pair (e.g., ETHUSDT, BTCUSDT)
- Easy to run locally or via Docker

## Installation

Local 
1. Install project from github
2. Run main.py
3. Enjoy!

Docker
1. Install project from github
2. Build the Docker image: 
    - docker build -t crypto-currency-watcher . 
3. Run the container 
    - docker run --rm crypto-currency-watcher 
4. Enjoy!
