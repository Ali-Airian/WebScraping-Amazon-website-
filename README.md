# WebScraping-Amazon-website-

**Amazon Product Scraper**
This Python script scrapes product information from Amazon search results for a specific search query and stores the data in a CSV file. It uses the BeautifulSoup library for web scraping and Pandas for data manipulation. The information extracted includes product title, price, rating, number of reviews, and availability status.

**Features**
Scrapes product information from Amazon search results.
Extracts product title, price, rating, number of reviews, and availability status.
Handles various cases of product availability and pricing.
Stores the extracted data in a CSV file named amazon_data.csv.
**Requirements**
Python 3.x
Required Python libraries: BeautifulSoup, requests, pandas, numpy
You can install the required libraries using the following command:
pip install beautifulsoup4 requests pandas numpy

**Usage**
Clone this repository to your local machine:

1. git clone https://github.com/yourusername(Own Machine Name)/amazon-product-scraper.git
Navigate to the project directory:

2. cd amazon-product-scraper
Open the scraper.py file and add your User-Agent to the HEADERS dictionary.
3. Run the script:
python scraper.py
After the script finishes running, you will find the extracted data in a file named amazon_data.csv.

**Note**
This script is designed for educational purposes and to showcase web scraping using Python. Make sure to review Amazon's terms of service before scraping their website.
The scraping process depends on the website's structure, which can change over time. If the script stops working, you might need to adjust the parsing logic accordingly.
**Disclaimer**
This project is not affiliated with or endorsed by Amazon. It is intended for educational purposes only.
