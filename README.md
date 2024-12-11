# Recipe Collector
This project is a Recipe Collector that automates the process of extracting, cleaning, and organizing recipes from various sources like web pages and PDFs. The extracted data is processed into a structured format (CSV), making it suitable for further analysis or integration into applications.

## Features
### Web Scraping:
Uses BeautifulSoup and requests to scrape recipe data from web pages.
Extracts titles, ingredients, and instructions using regex for pattern matching.
### PDF Parsing:
Utilizes pdfplumber for extracting text from PDFs, even with varying formats.
Identifies and extracts sections such as titles, ingredients, and instructions using custom rules.
### Data Cleaning:
Applies preprocessing techniques to remove unwanted characters and standardize the recipe format.
Handles special characters and converts them into standard equivalents.
### Data Organization:
Saves extracted data into a structured CSV file using pandas, with columns for titles, ingredients, and instructions.
### Customizable Rules:
Rules for extracting specific sections are configurable to adapt to different formats and structures of recipes.
