# Web Scraping Tool

## Overview

This project is a web scraping tool developed using Python that automates the process of extracting data from websites. The tool scrapes sub-URLs, image URLs, and text content from a given main URL. It then stores the scraped data into an SQLite database for easy management and querying. Additionally, the tool can download images from the scraped pages and organize them into folders based on the domain.

### Features:
- Extract sub-URLs, image URLs, and text content from websites.
- Save the scraped data in an SQLite database.
- Download and organize images based on the domain name.
- Handle network errors, HTML parsing issues, and database errors gracefully.

## Motivation

This tool was developed to address the challenges of manual data collection from websites. By automating the scraping process, the tool improves productivity and reduces human error. The project aims to process large volumes of images and web pages efficiently while ensuring reliability and robustness against common scraping issues.

## Technologies Used
- Python 3.x
- BeautifulSoup 4 (for HTML parsing)
- Requests (for HTTP requests)
- SQLite3 (for database management)
- Regular expressions (for text cleaning)
- Hashlib (for generating unique filenames for images)

## Installation

To set up the web scraping tool on your local machine, follow these steps:

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/web-scraping-tool.git
    cd web-scraping-tool
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the script** to start scraping by providing the main URL:
    ```bash
    python main.py
    ```

2. The script will prompt you for:
    - **Main URL**: The starting URL to scrape.
    - **Directory**: The location to store the downloaded images.

3. The script will then:
    - Scrape the main URL and all sub-URLs.
    - Extract image URLs, text content, and store them in the SQLite database.
    - Optionally download images and organize them by domain name.

## File Structure

