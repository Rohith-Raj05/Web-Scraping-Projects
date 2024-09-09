# Web-Scraping-Projects

Welcome to the Web Scraping Projects repository! This repo contains Python scripts designed to scrape data from various websites and save it in CSV format. The projects utilize BeautifulSoup and pandas for data extraction and organization.

## Projects

### Project 1: Scraping Data from "https://www.scrapethissite.com/pages/forms/"

**Objective:** Extract tabular data from the specified URL and save it to a CSV file.

**Features:**
- Sends a GET request to the URL
- Parses HTML content with BeautifulSoup
- Extracts table data into pandas DataFrame
- Saves DataFrame to `scraped_data.csv`

**Usage:**
1. Run the script to scrape data.
2. The results will be saved in `scraped_data.csv`.

### Project 2: Scraping Product Details from Amazon

**Objective:** Extract product details (title and number of ratings) from an Amazon product page and save them to a CSV file.

**Features:**
- Sends a GET request to the Amazon product page URL
- Parses HTML content with BeautifulSoup
- Extracts product title and ratings
- Saves data to `amazonWebScrapingDataset.csv`

**Usage:**
1. Update the script with the Amazon product URL.
2. Run the script to extract data.
3. Check `amazonWebScrapingDataset.csv` for the output.

**CSV File Format:**
- `ProductName`: Title of the product
- `Total_no_of_Raters`: Number of ratings
- `Date`: Date of data extraction

### Project 3: Scraping Data from Wikipedia - Largest Companies by Revenue

**Objective:** Extract data from multiple tables on the Wikipedia page about the largest companies in the United States by revenue and save it in CSV files.

**Features:**
- Sends a GET request to the Wikipedia page URL
- Parses HTML content with BeautifulSoup
- Extracts data from multiple tables
- Saves data to CSV files

**Usage:**
1. Run the script to extract data.
2. Multiple CSV files will be generated with the scraped data.

## Requirements

To run these projects, you need the following Python libraries:

- `beautifulsoup4`
- `requests`
- `pandas`

Install the required libraries using pip:

```bash
pip install beautifulsoup4 requests pandas
