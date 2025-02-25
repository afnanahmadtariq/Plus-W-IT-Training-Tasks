# Class 5 Assignments

This document summarizes the assignments completed in **Class 5** of the Plus W IT Training Program. The tasks focus on automation, data handling, and web scraping.

## 📂 Directory Structure
```
Class 5/
├── Assignment_Tasks/
│   ├── Task1/
│   │   ├── backup_folder/
│   │   ├── csv_files/
│   │   ├── Automated_File_Management.ipynb
│   │   ├── output.csv
│   │   └── output.json
│   ├── Task2/
│   │   ├── Stock_Market_Data_Collection.ipynb
│   │   └── stocks.db
│   └── Task3/
│   │   ├── quotes.csv
│   │   └── Web_Data_Scraping.ipynb
├──  Class Code/
│   ├── practice/
│   │   ├── Class_5.ipynb
│   │   .
│   │   .
│   ├── Class5_LectureCode.ipynb
│   ├── data.csv
│   ├── data.db
│   ├── data.json
│   └── data.xls
└── Images Used/
    ├── image.jpeg
    └── image.jpg
```

## ❓ Questions
For any clarifications or queries, refer to the [Questions Document](./Assignment_Class5.pdf).

---

## 📌 Assignments

### 1️⃣ Automated File Management and Data Export System
**Objective:**
- Move all CSV files from the `csv_files` folder to the `backup_folder`.
- Create a sample DataFrame and export it to CSV and JSON formats using the `export_data` function.
- Organize the file system and handle backup operations efficiently.

**File:** [Automated File Management and Data Export System](./Assignment_Tasks/Task1/Automated_File_Management.ipynb)

---

### 2️⃣ Real-Time Stock Market Data Collection and Analysis Using Python and SQLite
**Objective:**
- Fetch live stock data from Yahoo Finance using the `yfinance` library.
- Store the stock data in an SQLite database.
- Retrieve and display the stock data of a specific symbol, such as `GOOGL`, over time.
- Implement automated data collection at regular intervals.

**File:** [Real-Time Stock Market Data Collection](./Assignment_Tasks/Task2/Stock_Market_Data_Collection.ipynb)

---

### 3️⃣ Scrape Data from a Website
**Objective:**
- Scrape quote data such as the quote text, author, and associated tags from an online quotes website (e.g., [Quotes to Scrape](http://quotes.toscrape.com/)).
- Use BeautifulSoup and requests to extract the relevant quote information.
- Save the extracted data into a CSV file for further analysis.

**File:** [Web Data Scraping](./Assignment_Tasks/Task3/Web_Data_Scraping.ipynb)

--- 