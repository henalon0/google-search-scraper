# Google Search Scraper

A simple Python script for scraping Google search results using the BeautifulSoup library.

## Description

This script allows you to perform Google searches programmatically and retrieve search result URLs. It utilizes the `requests` library for making HTTP requests and `BeautifulSoup` for parsing the HTML content.

## Features

- Single result retrieval: Retrieve the first search result URL for a given query.
- Multiple results retrieval: Retrieve the top N search result URLs for a given query.

## Dependencies

- [Requests](https://docs.python-requests.org/en/latest/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Usage

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the script:

    ```bash
    python google_search.py
    ```

3. Enter your search query when prompted.

4. View the results.
