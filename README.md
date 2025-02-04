📌 Overview
This project is a Python-based web scraper that extracts user reviews and business details from Yelp, given a list of Yelp business URLs. It automates the process of collecting customer feedback, ratings, and business information, then structures the extracted data into a CSV file for easy analysis.

🔍 Key Features
✅ Extracts Customer Reviews – Retrieves the latest reviews from each Yelp business page.
✅ Scrapes Business Information – Collects price range, rating, categories, address, and opening hours.
✅ Handles Errors Gracefully – Implements retry logic and error handling to avoid crashes.
✅ User-Agent Rotation – Mimics real browsers to reduce the risk of being blocked.
✅ Rate-Limiting – Ensures responsible scraping with controlled request intervals.
✅ CSV Input & Output – Reads a list of Yelp URLs and saves structured results in an output CSV file.

🚀 How It Works
Place a list of Yelp business URLs in an input CSV file.
Run the script to scrape reviews and business details.
Retrieve the structured data in an output CSV file for further analysis.
🛠️ Technologies Used
Python
BeautifulSoup (for HTML parsing)
Requests (for making HTTP requests)
CSV module (for reading and writing data)
