# Book Scraper

This project is a web scraper designed to collect detailed information about books from the website [Books to Scrape](https://books.toscrape.com/). The scraper uses `requests` to fetch web pages and `BeautifulSoup` to parse and extract the relevant data. The collected data is then stored in a CSV file for further analysis.

## Features

- Scrapes book information from multiple pages.
- Extracts details including title, rating, price, stock availability, book link, and image link.
- Fetches additional book details such as category, price excluding and including tax, tax amount, quantity, UPC, and reviews.
- Saves the collected data into a CSV file.

## Requirements

- Python 3.x
- `requests` library
- `BeautifulSoup` library
- `tqdm` library
- `pandas` library

## Installation

1. Clone the repository or download the script files.
2. Install the required libraries if you haven't already:

   ```bash
   pip install requests
   pip install beautifulsoup4
   pip install tqdm
   pip install pandas
