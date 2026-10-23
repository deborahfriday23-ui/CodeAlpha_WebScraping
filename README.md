# World Population Data Scraper

## Project Overview
This project uses Python to scrape and prepare population data from Wikipedia. It demonstrates web scraping, HTML table extraction, and data cleaning to create a structured dataset for further analysis.

## Data Source
- **Website:** Wikipedia
- **Dataset:** [List of countries and dependencies by population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population)

## Tools and Libraries
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Colab

## Methodology
1. Sent an HTTP request to the Wikipedia page using Python's Requests library.
2. Parsed the webpage's HTML using BeautifulSoup.
3. Identified and extracted the relevant population table using Pandas.
4. Cleaned the dataset by removing a blank row and the Notes column.
5. Converted population figures to integer values and world-population percentages to numeric values.
6. Extracted the year from the original date text into a separate `Year` column.
7. Removed citation markers from the source descriptions.
8. Checked for missing values, duplicate locations, unwanted spaces, and invalid population values.

## Output
- `world_population_cleaned.csv` — the cleaned population dataset.
- `world_population_scraper.ipynb` — the Jupyter notebook containing the Python code.

## Project Purpose
This project was completed as part of the CodeAlpha Virtual Data Analytics Internship, Task 1: Web Scraping. It demonstrates the collection and preparation of publicly available web data for analysis.

## Attribution
Population data was obtained from Wikipedia. Please refer to the [original article](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population) for its sources, update history, and licensing information.