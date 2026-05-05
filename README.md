# 🤖 Telegram Data Analyzer Bot

A Telegram bot that automatically analyzes datasets (CSV, Excel, JSON) and generates a detailed data quality report.

---

## 🚀 Features

* 📊 Dataset summary (rows, columns)
* 🔁 Duplicate detection
* ❌ Missing value analysis
* 🔍 Column-wise validation:

  * Emails
  * Numeric values
  * Dates
  * Phone numbers
* ⚠️ Detects:

  * Invalid formats
  * Extra spaces
  * Data inconsistencies

---

## 🛠️ Tech Stack

* Python
* Pandas
* python-telegram-bot

---

## 📸 Demo

### Input/Code File

<img width="1649" height="972" alt="image" src="https://github.com/user-attachments/assets/9a4e1c5c-d60b-4d7b-89f3-6b53896153b5" />


### Output Report

<img width="640" height="751" alt="image" src="https://github.com/user-attachments/assets/b61ab99e-8b5d-4121-9917-5fc1ea4e4e82" />


---

## ⚙️ Setup Instructions

### 1. Clone repository

```bash
git clone (https://github.com/VedantElite/Telegram-Bot-Data-Analyzer.git)
cd telegram-data-analyzer-bot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Setup environment variables

Create  file:
VS Code bot.py
Then VS code Need to Run While Running Put the File, then run again for New File
```
BOT_TOKEN=your_telegram_bot_token
```

Or set it manually:

**Linux/Mac:**

```bash
export BOT_TOKEN=your_telegram_bot_token
```

**Windows (CMD):**

```bash
set BOT_TOKEN=your_telegram_bot_token
```

### 4. Run the bot

```bash
python bot.py
```
---

## 📁 Supported File Types

* CSV
* Excel (.xlsx)
* JSON

---

## 💡 Use Case

This bot helps:

* Data Analysts
* Data Scientists
* Businesses cleaning datasets

---

## 📌 Future Improvements

* Data visualization
* Auto-cleaning suggestions
* Dashboard integration

---
