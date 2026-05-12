# Electronics Availability and Pricing Bot

Automated web scraper that monitors GPU availability and pricing across Best Buy and NVIDIA.com, built during the COVID-era GPU shortage when RTX cards were being scalped at 3-4x MSRP by automated bots.

## Overview

`RTX_Checker_BESTBUY_n_NVIDIA.ipynb` polls product pages at a configurable interval, parses stock status and current price, and alerts when an item transitions from out-of-stock to available. Demonstrates web scraping, scheduled polling, and real-time alerting logic.

## How to Run

```bash
pip install requests beautifulsoup4
jupyter notebook RTX_Checker_BESTBUY_n_NVIDIA.ipynb
```

Update the target product URLs in the notebook config cell to monitor different SKUs or retailers.

## Tech Stack
- Python 3
- `requests` — HTTP page fetching
- `beautifulsoup4` — HTML parsing and element targeting
- `time` — polling interval scheduling
