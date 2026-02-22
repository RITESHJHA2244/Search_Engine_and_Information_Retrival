# Simple Web Scraper (Python)

## Project Description
This project is a simple Python web scraper.  
It takes a URL as input, fetches the webpage, and prints:

- Page Title
- Full Body Text
- All hyperlinks present on the page

The project uses `requests` to fetch the webpage and `BeautifulSoup` to parse the HTML.

---

## Technologies Used

- Python 3
- requests library
- BeautifulSoup (bs4)

---

## How It Works

1. The program takes a URL.
2. It sends an HTTP request to the website.
3. It checks the status code.
4. It parses the HTML content.
5. It extracts:
   - Title
   - Body text
   - All `<a>` tag links
6. It prints the results in the terminal.

---

## Installation

Install required libraries before running:

