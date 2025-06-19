# Torrent Scraper for PS4 Games

## Overview
This Python script scrapes PS4 game torrents from a specific website, downloads the `.torrent` files, and saves them along with metadata to your local machine. The script is designed to run efficiently with parallel processing.

## Features
- Scrapes game pages for torrent links
- Extracts game metadata (year, genre, version, etc.)
- Downloads `.torrent` files to a local directory
- Logs collected files with metadata
- Multi-threaded for faster processing

## Requirements
- Python 3.x
- Required packages (install via `pip`):
  ```
  pip install requests beautifulsoup4 tqdm urllib3
  ```

## Usage
1. Clone or download the script.
2. Install the required dependencies.
3. Run the script:
   ```
   python torrent_scraper.py
   ```

## Configuration
- The script saves files to a `results` directory (automatically created).
- Collected files and metadata are logged in `collectedfiles.txt`.
- Adjust `MAX_WORKERS` in the script to control parallel threads.

## Notes
- The script includes a delay between requests to avoid overloading the server.
- SSL warnings are disabled for compatibility.

## Support & Donations
This project is maintained by a developer working from their phone! If you find this tool useful, consider supporting the effort to upgrade to a full PC setup.

**Crypto Donations:**
- **BTC:** `bc1qnrylqrxq3yzfnz89smp56lm5uu0ful8dsuzus9`
- **TRX:** `TKdJXyopnrTafFvFuDJ2BA8j6yHRpWutuk`
- **ETH/USDT:** `0x2525bC1f865229C6B897353f64fFeF471B0B6e1b`
- **SOL:** `7aE5Y7PvfUr52WnruiDATFpR99PWPo4q9U7vu3Hid3Yh`

**Connect:**
- Telegram Chat: [https://t.me/boredmonkeymanschat](https://t.me/boredmonkeymanschat)
- X (Twitter): [@bhanco2023](https://twitter.com/bhanco2023)

## Disclaimer
This script is for educational purposes only. Ensure you comply with all applicable laws and website terms of service when using this tool. The maintainer is not responsible for any misuse.
