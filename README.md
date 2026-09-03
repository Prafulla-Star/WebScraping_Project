# WebScraping_Project

A complete **Web Scraping + Data Cleaning + Database** project built with Python.

In this project I scraped product data from [Yamaha Music Store](https://yamahamusicstore.in/) using **BeautifulSoup** and **Requests**, cleaned the data, stored it in JSON, and finally inserted it into an **SQLite** database.

---

## Project Overview

- Scrape product categories and product details (name, price, rating, reviews, product link, images)
- Handle pagination
- Clean and structure the scraped data
- Save data as JSON (`all_products.json`)
- Insert cleaned data into SQLite database (`products.db`)
- Perform basic CRUD operations on the database

---

## Technologies Used

- Python 3.x
- Requests
- BeautifulSoup4
- SQLite3
- JSON
- Jupyter Notebook

---

## Setup Instructions (with Virtual Environment)

### 1. Clone the Repository

```bash
git clone https://github.com/Prafulla-Star/WebScraping_Project.git
cd WebScraping_Project

Install it in the virtual ENV
pip install requests beautifulsoup4 jupyter notebook

