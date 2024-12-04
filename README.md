# WebScrapeX: Automated Google Search Result Extractor

This project is a Python-based web scraper that extracts and displays search result links from Google for a specified keyword. The script uses the `requests` library to make HTTP requests and `BeautifulSoup` from the `bs4` library to parse the HTML content. It retrieves a customizable number of search results and outputs them in a simple enumerated format.

## Features
- **Dynamic Search Query**: Converts user-input keywords into a Google search URL.
- **Customizable Number of Results**: Specify how many search results to fetch.
- **Browser Emulation**: Mimics a browser using custom user-agent headers to bypass detection.
- **Efficient Parsing**: Extracts only valid HTTP links from the search results.
- **Simple Output**: Displays the extracted links in an enumerated format.

## How It Works
1. Input a keyword to search on Google.
2. The script constructs a Google search URL and sends an HTTP GET request.
3. The HTML response is parsed using `BeautifulSoup`.
4. Links to search results are extracted and validated.
5. The results are printed as an enumerated list.

## Tech Stacks
- Python 
- `requests` library
- `beautifulsoup4` library

## Applications
- Research and data collection
- Content aggregation and analysis
- Automating search queries for SEO insights
