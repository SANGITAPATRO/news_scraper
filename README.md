# News Headline Web Scraper 📰

## Objective
This script scrapes the latest news headlines from the BBC News website.

## Tools Used
- Python
- `requests` library
- `BeautifulSoup` (from `bs4`)

## How It Works
1. Sends a request to the BBC News website.
2. Parses the HTML content using BeautifulSoup.
3. Extracts text from `<h2>` and `<h3>` tags (commonly used for headlines).
4. Saves the collected headlines into a neatly formatted `headlines.txt` file.

## How to Run
```bash
python news_scraper.py
```

Make sure you have the required libraries installed:
```bash
pip install requests beautifulsoup4
```

## Output
The script creates a file `headlines.txt` with a timestamp and the list of scraped headlines.

---

⭐ Created with the intention of automating news data collection in a clean and readable way.
