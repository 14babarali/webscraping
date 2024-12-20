# AirAsia Passenger Reviews Scraper

A Python-based web scraper designed to extract passenger reviews from AirAsia Malaysia's page on airlineratings.com.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Requirements](#requirements)


## Project Overview

This project aims to collect and analyze passenger reviews for AirAsia Malaysia flights. It utilizes web scraping techniques to gather data from airlineratings.com, providing valuable insights into customer experiences and airline performance.

## Features

- Multi-page scraping capability
- Extraction of detailed review information
- Automatic handling of pagination
- Storage of scraped data in a structured Excel file
- User-friendly configuration options

## Requirements

- Python 3.8+
- Beautiful Soup 4
- Requests library
- Pandas


3. The script will scrape reviews and save them to `airasia_reviews_details.xlsx` in the current directory.

## Code Structure

The main file `airasia_scraper.py` contains the following components:

- Configuration section for setting base URL and headers
- Main scraping function with pagination handling
- Data extraction logic for each review
- Output formatting using pandas

## Data Extraction

The scraper extracts the following information from each review:

- Customer Name
- Flight Type
- Location/Date
- Overall Score
- Rating Categories
- Full Review Text

## Output Format

Scraped data is stored in an Excel file (`airasia_reviews_details.xlsx`) with columns corresponding to the extracted fields.

## Limitations

- The script may break if airlineratings.com changes its website structure.
- Rate limiting or IP blocking might occur with frequent scraping.
- Some reviews may be missing certain fields due to inconsistent data presentation on the source site.

## Future Improvements

1. Implement rate limiting to avoid being blocked by the target website.
2. Add error handling for network issues or unexpected page structures.
3. Incorporate natural language processing techniques for sentiment analysis of reviews.
4. Develop a user interface for easier configuration and result visualization.





