# Amazon EG Samsung Scraper

This project is a Python-based web scraper that extracts Samsung product details from Amazon Egypt. It uses Selenium for web scraping and Pandas for data manipulation to structure and clean the data.

## Features
- Scrapes product information from Amazon Egypt.
- Extracts product details such as:
  - **Brand**
  - **Description**
  - **Options**
  - **Price**
  - **Shipping Information**
  - **Additional Info**
- Identifies sponsored products and includes this information in the output.
- Cleans and converts prices into a numerical format for analysis.
- Exports the final structured data to a CSV file.

## Prerequisites
- Python 3.x installed.
- Google Chrome and the corresponding [ChromeDriver](https://chromedriver.chromium.org/downloads) installed.
- The following Python libraries:
  - `selenium`
  - `pandas`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-eg-samsung-scraper.git
   cd amazon-eg-samsung-scraper
