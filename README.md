# 🚀 Lead Generation Automation using n8n

## 📌 Project Overview

This project is an automated lead generation system built using n8n.

It collects business data (like gyms in a city) from Google Maps using SerpAPI, filters useful leads, and stores them in Google Sheets.

---

## ⚙️ Tech Stack

* n8n (workflow automation)
* SerpAPI (Google Maps data)
* Google Sheets API

---

## 🔄 Workflow

Webhook → Set Input → HTTP Request (SerpAPI) → IF (Filter Phone) → Set (Clean Data) → Google Sheets

---

## 📊 Features

* Automated lead collection
* Filters only businesses with phone numbers
* Stores structured data in Google Sheets
* Can be extended to send emails to clients

---

## 🧪 Example Output

* Name
* Phone
* Address
* Rating
* Website

---

## 🚀 How to Use

1. Import the workflow JSON into n8n
2. Add your SerpAPI key
3. Connect Google Sheets
4. Run the workflow

---

## 💡 Future Improvements

* Add email automation
* Add scheduling (daily runs)
* Multi-city search support

---

## 👨‍💻 Author

Sumit Solanki
