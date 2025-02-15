# Web Text Extraction & JSON Conversion

## Overview
This extracts and processes text from web pages, specifically identifying biology-related content. It utilizes **BeautifulSoup** and **Requests** for web scraping, implements **error handling and retry mechanisms**, and structures the extracted data into **JSON format**.

## Features
- Extracts webpage text and tables using **BeautifulSoup** and **Requests**.
- Filters content based on predefined **biology-related keywords**.
- Removes unnecessary elements like scripts and styles.
- Handles errors with **retry mechanisms** for failed requests.
- Saves extracted data in a structured **JSON file** for easy analysis.

## Algorithm
1. **Fetch webpage content** using `requests` with headers.
2. **Parse HTML** using `BeautifulSoup`.
3. **Remove unwanted elements** (script, style, nav, footer, etc.).
4. **Extract relevant text** (headings, paragraphs, list items).
5. **Identify and filter** text based on biology-related keywords.
6. **Extract tables**, structuring data into key-value pairs.
7. **Store extracted data** in a dictionary format.
8. **Implement retry mechanism** for handling request failures.
9. **Save the structured content** as a JSON file.

## Installation
```bash
pip install requests beautifulsoup4
