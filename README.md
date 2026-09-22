# 🔎 Data Engineer Jobs Scraper

A Python web scraping project built with **Selenium** to collect real-world **Data Engineer** job listings from **Naukrigulf** and store the extracted information in a structured CSV dataset.

## 📌 Project Overview

The scraper searches for **Data Engineer** job opportunities and dynamically navigates through the **first three pages** of the search results.

For each job listing, the script extracts the most important job-related information and organizes it into a CSV file for further analysis or processing.

## 📊 Data Collected

The following information is extracted from each job listing:

* **Job Title**
* **Company Name**
* **Job Location**
* **Required Experience**
* **Full Job Description**

## 🛠️ Technologies Used

* **Python**
* **Selenium** – Browser automation and web scraping
* **Pandas** – Data processing and CSV export
* **CSV** – Structured data storage

## ⚙️ Workflow

```text
Search Data Engineer Jobs
          ↓
Navigate Through Pages 1–3
          ↓
Extract Job Information
          ↓
Store Data in Pandas DataFrame
          ↓
Export to CSV
```

## 📂 Project Structure

```text
├── scraper.ipynb
├── Jobs.csv
└── README.md
```

## ▶️ Installation & Usage

Install the required Python libraries:

```bash
pip install selenium pandas
```

Run the scraper:

```bash
python scraper.py
```

After execution, the extracted data will be saved in:

```text
Data_Engineer_Jobs.csv
```

## 👨‍💻 Author

**Anas Ahmed**

Python | SQL | Data Engineering
