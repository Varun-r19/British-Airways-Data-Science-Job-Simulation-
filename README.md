# British Airways Review Scraper

This project scrapes customer reviews for British Airways from the AirlineQuality website and performs basic data processing on the collected reviews.

## Features

- Web scraping of British Airways reviews from [AirlineQuality.com](https://www.airlinequality.com/airline-reviews/british-airways)
- Pagination handling to collect reviews from multiple pages
- Basic data cleaning and preprocessing of reviews
- Storage of reviews in a pandas DataFrame for further analysis

## Requirements

- Python 3.x
- Required Python packages:
  - requests
  - beautifulsoup4
  - pandas
 
## Usage

Run the Jupyter notebook `British_airways.ipynb` to execute the scraper and data processing steps.

## Code Structure

- `British_airways.ipynb`: Main Jupyter notebook containing the scraping and processing code
- `README.md`: This file, containing project information and instructions

## Future Improvements

- Complete the `clean()` function to properly clean the review text
- Implement more advanced text processing and analysis techniques
- Add data visualization of the scraped reviews
- Implement error handling and logging

## Installation

1. Clone this repository:
2. Run `pip install -r requirements.txt` to get the the required packages
