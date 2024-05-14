# DarkWebCrawler

DarkWebCrawler is a simple Python web crawler that searches for and extracts ***'.onion'*** links from a given parent URL. It makes HTTP requests with the requests library, parses HTML content with BeautifulSoup, and configures a SOCKS5 proxy with PySocks to connect to the Tor network.

## Features:

- Crawls web pages to find .onion links
- Uses a SOCKS5 proxy to access the Tor network
- Supports infinite recursion limit
- Allows users to display crawled .onion links
