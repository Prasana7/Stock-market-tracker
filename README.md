# Stock Market Tracker Bot

## What It Does
Automates daily stock data collection from public NSE APIs, processes JSON, stores in MySQL, sends email summaries.

## Features
✅ Scheduled Cron jobs (runs daily 9 AM)
✅ Python/Selenium web scraping
✅ MySQL CRUD operations
✅ Error handling & retry logic
✅ Email notifications

## Quick Start
1. `pip install -r requirements.txt`
2. Create MySQL database: `CREATE DATABASE stocks;`
3. Update config.py with Gmail credentials
4. `python stock_tracker.py`

## Demo Output
✅ RELIANCE: ₹2850.5, Target ₹3200 (Buy)
✅ TCS: ₹4200.0, Target ₹4500 (Hold)
📧 Email sent!

## Project Structure
stock-market-tracker/
├── stock_tracker.py (Main bot)
├── requirements.txt (Dependencies)
├── config.py (MySQL/Gmail config)
├── README.md
└── demo/
├── screenshot_output.png
├── email_summary.png
└── mysql_data.png

## Tech Stack
- Python 3.8+
- Selenium for web scraping
- MySQL for data storage
- SMTP for email delivery
- Cron for scheduling
