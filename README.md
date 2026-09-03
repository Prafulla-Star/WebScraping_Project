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

## Folder Structure
WebScraping_Project/
│
├── Scraping_with_Database_Insertion/
│   ├── Web_Scraping.ipynb          # Main scraping notebook (BeautifulSoup + Requests)
│   ├── database.ipynb              # Load JSON → Create SQLite DB → Insert & CRUD
│   ├── all_products.json           # Scraped & cleaned product data
│   ├── products.db                 # SQLite database
│   ├── downloaded_image.webp       # Sample downloaded product image
│   └── Prafu.jpg                   # Extra image
│
├── python_tutorial_series/         # Python learning notebooks
│   ├── Python_Basics_Code 1.ipynb
│   ├── Python_ControlStructures_Code 2.ipynb
│   ├── Python_Collections_Code 3.ipynb
│   ├── Python_Functions_Code 4.ipynb
│   ├── python_strings 5.ipynb
│   ├── Python_FileHandling_Code 6.ipynb
│   ├── Python_ErrorHandling_Code 7.ipynb
│   ├── python_oops 8.ipynb
│   ├── python_basics.ipynb
│   └── steps.txt
│
├── python_basics.ipynb             # Extra basics notebook
├── git_commands.txt                # Useful Git commands
├── .gitignore
└── README.md



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



pip install --upgrade pip
pip install requests beautifulsoup4 jupyter notebook

