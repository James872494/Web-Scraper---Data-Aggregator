# 🕸️ Web Scraper & Data Aggregator

## 📌 Overview

This project is a Python-based web scraper that extracts the **10 most recent job postings** from [https://vacancymail.co.zw/jobs/](https://vacancymail.co.zw/jobs/), consolidates the information into a CSV file, and optionally schedules the task to run daily.

---

## ⚙️ Features

- Extracts job title, company, location, expiry date, and description.
- Saves structured data into a CSV file.
- Cleans duplicates automatically.
- Logs all events and errors.
- Can run on a schedule (daily at 09:00).

---

## 🛠️ Setup Instructions

1. Clone or download this repo.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
