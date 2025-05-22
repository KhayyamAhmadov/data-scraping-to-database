# data-scraping-to-database
# Bina.az Data Scraper & SQL Server Loader

This project automatically scrapes real estate listings from **bina.az**, cleans and structures the data, and loads it into a **Microsoft SQL Server** database.

---

## Important Legal Notice

This project is intended for **educational**, **personal**, and **research purposes** only. It is important to comply with **bina.az’s terms of use**, **copyright policies**, and **data protection laws**.

When using this project, please consider the following:

- Do not overload the site’s servers (include regular delays).  
- Note: This project does not use an official API. Data is collected via automated web scraping from the website.

---

## Features

- **Dynamic web scraping**: Collects listing data using Selenium and BeautifulSoup.  
- **Data cleaning and structuring**.  
- **Appending updated data to the database**.

---

## Technical Requirements

- Python  
- Required modules:  
  - `selenium`  
  - `beautifulsoup4`  
  - `pandas`  
  - `pyodbc`  
  - `sqlalchemy`  
  - `time`  
  - `tqdm`  
  - `re`  
- Microsoft SQL Server  
- ChromeDriver