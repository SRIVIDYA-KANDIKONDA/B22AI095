# B22AI095
# 🚀 URL Shortener Microservice  

## 📌 Overview  
This project implements a **URL Shortener Microservice** as part of the **AffordMed Campus Hiring Backend Assignment**.  
It allows users to:  
- Create short URLs for long links.  
- Redirect to the original URL using the short code.  
- Track statistics (click count, timestamp, referrer, location).  

---

## ⚡ Features  
✅ Shorten long URLs with optional custom shortcode.  
✅ Default expiry = **30 minutes** (configurable).  
✅ Redirection with **click tracking**.  
✅ Statistics API with click count and history.  
✅ Logging middleware for all requests.  
✅ Error handling for invalid/expired links.  

---

## 🛠️ Tech Stack  
- **Python 3.8+**  
- **Flask** (Web Framework)  
- **Datetime** (Expiry handling)  
- **Logging** (Request tracking)  

---

## 📂 Project Structure
url-shortener/
│-- app.py # Main Flask application
│-- README.md # Documentation
│-- requirements.txt # Dependencies (Flask)
