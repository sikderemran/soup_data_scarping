# 💰 Yahoo Finance Crypto Scraper

A **lightweight Python script** that scrapes the top cryptocurrency data from [Yahoo Finance](https://finance.yahoo.com/crypto/) using **Requests** and **BeautifulSoup**.  
It fetches table data like Name, Price, Market Cap, and other fields every 10 minutes and prints them to the terminal with timestamps.

---

## ✨ Features

- 📊 Scrapes top 5 cryptocurrencies from Yahoo Finance
- ⏰ Logs real-time data with timestamps (IST)
- 🔁 Runs indefinitely and refreshes every 10 minutes
- 💎 Parses HTML data using BeautifulSoup
- 🧼 Clean dictionary-based output for each coin

---

## 🧩 Tech Stack

- Python 3.x  
- `requests` for making HTTP calls  
- `BeautifulSoup4` for HTML parsing  
- `datetime` and `time` for scheduling  

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed
- `pip` package manager

### Installation

1. Clone the repo:

```bash
git clone https://github.com/yourusername/yahoo-crypto-scraper.git
cd soup_data_scarping
pip install requests beautifulsoup4
python soup_data_scarping.py

