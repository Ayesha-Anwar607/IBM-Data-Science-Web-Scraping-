# IBM Data Science: Web Scraping & Data Extraction Portfolio

This repository contains a collection of Jupyter Notebooks focusing on web scraping and data extraction assignments completed as part of the **IBM Data Science Professional Certificate** on Coursera. 

The projects demonstrate practical knowledge of extracting structured and unstructured data from websites, parsing HTML, and transforming it into clean tabular formats for analysis.

## 🚀 Overview of Scraped Concepts

these labs focus on the fundamentals of the data engineering pipeline—specifically **Data Acquisition**. 

The typical workflow implemented in these notebooks includes:
1. Sending HTTP requests to target URLs.
2. Parsing the webpage's DOM structure.
3. Filtering and extracting targeted text/tables.
4. Converting the extracted data into a `pandas` DataFrame for data analysis.

## 🛠️ Tech Stack & Libraries Used

* **Python 3**
* **BeautifulSoup4 (`bs4`):** Used for parsing HTML documents and extracting specific tags, classes, and IDs.
* **Requests:** Used for handling HTTP protocol methods (`GET` requests) to download the webpage content safely.
* **Pandas:** Used to structure the scraped raw arrays into organized DataFrames and export them to CSV files.
* **Html5lib / Lxml:** Backend parsers utilized by BeautifulSoup to navigate the web tree.
