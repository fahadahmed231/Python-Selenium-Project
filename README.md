# Amazon Web Scraper

This project is a web scraping tool built using Python and Selenium. It automates the process of collecting product information from Amazon India's search results pages for a specified query (e.g., "laptop").

## Features
- Scrapes product HTML content from Amazon's search results pages.
- Saves each product's HTML content to a separate file in a `data/` directory.

## How It Works
1. Initializes a Selenium WebDriver for Chrome.
2. Searches for a specified query on Amazon and iterates over the first 19 pages of results.
3. Extracts the HTML content of each product found on the page.
4. Saves the extracted HTML content into separate files for later analysis.

## Requirements
- Python 3.x
- Selenium (`pip install selenium`)
- Chrome WebDriver (`https://sites.google.com/a/chromium.org/chromedriver/downloads`)

## Usage
1. Modify the `query` variable in the script to search for different products.
2. Run the script using Python:
   ```bash
   python scraper.py
