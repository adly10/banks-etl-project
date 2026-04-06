# 🏦 Largest Banks ETL Project

## 📌 Overview

This project extracts, transforms, and loads (ETL) data about the **top 10 largest banks in the world by market capitalization**.

The pipeline:

* Extracts data from Wikipedia
* Transforms it into multiple currencies (GBP, EUR, INR)
* Stores results in CSV and SQLite database
* Logs execution steps

---

## ⚙️ Technologies Used

* Python
* Pandas
* BeautifulSoup
* SQLite3
* NumPy

---

## 📊 Features

* Web scraping from Wikipedia
* Currency conversion using exchange rates
* Data storage:

  * CSV file
  * SQLite database
* Logging system for tracking execution

---

## 📂 Project Structure

```
banks_project.py
exchange_rate.csv
Largest_banks_data.csv
Banks.db
code_log.txt
```

---

## 🚀 How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the script

```bash
python banks_project.py
```

---

## 📈 Sample Output

* CSV file with transformed data
* SQLite database table: `Largest_banks`
* Log file: `code_log.txt`

---

## 🧠 What I Learned

* ETL pipeline design
* Web scraping using BeautifulSoup
* Data transformation with Pandas
* Database handling using SQLite
* Logging in Python

---

## 📎 Data Source

Wikipedia: Largest banks by market capitalization

---

## 👨‍💻 Author
Mahmoud Essam Adly

Your Name
