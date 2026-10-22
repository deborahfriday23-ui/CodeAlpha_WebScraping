# CodeAlpha Web Scraping Project

## Project Overview
This project was completed as part of the CodeAlpha Virtual Data Analytics Internship. It uses Python web scraping techniques to collect, clean, and analyse book information from [Books to Scrape](https://books.toscrape.com/), a website designed for scraping practice.

## Objectives
- Extract book titles, prices, star ratings, and availability.
- Collect data across all 50 catalogue pages.
- Clean and validate the scraped dataset.
- Perform basic exploratory data analysis.
- Export the cleaned data to a CSV file.

## Tools and Technologies
- Python
- Requests
- Beautiful Soup
- Pandas
- Google Colab

## Data Collection
The scraper collected 1,000 book records from 50 catalogue pages. Each record contains:
- **Title:** The book's title.
- **Price:** The listed price in pounds sterling (£).
- **Rating:** The displayed star-rating category.
- **Availability:** The displayed stock status.

## Data Cleaning and Validation
- Converted prices from text to numeric values.
- Checked for missing values.
- Checked for duplicate records and repeated titles.
- Exported the cleaned dataset to CSV.

The dataset had no missing values or fully duplicated rows. One book title appeared twice with different prices, so both records were retained.

## Key Findings
- **Total records collected:** 1,000
- **Average book price:** £35.07
- **Lowest listed price:** £10.00
- **Highest listed price:** £59.99
- **Most common rating:** One star, with 226 books
- **Least common rating:** Four stars, with 179 books
- **Availability:** All 1,000 records were listed as in stock

These findings describe the scraped catalogue data and its displayed availability at the time of collection.

## Project Files
- `CodeAlpha_WebScraping.ipynb` — notebook containing the scraping, cleaning, and analysis code.
- `books_scraped.csv` — cleaned dataset.

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if they are not already available:
   `pip install requests beautifulsoup4 pandas`
3. Run the notebook cells in order to collect and analyse the data.

## Data Source
[Books to Scrape](https://books.toscrape.com/)

This project was created for educational purposes as part of the CodeAlpha Virtual Data Analytics Internship.
