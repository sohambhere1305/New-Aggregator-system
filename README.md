# New-Aggregator-system
News Aggregator System ("The Daily Breeze") is a web platform built using Django and the GNews API to collect, organize, and present real-time news articles across categories like Sports, Technology, Business, and World news.

# 📰 News Aggregator System ("The Daily Breeze")

A centralized web application designed to collect, organize, and present real-time news articles from multiple sources using the **GNews API**. Built with Django for the backend and modern frontend technologies, it streamlines news consumption by offering topic filtering, live search, and abstractive NLP news summarization.

---

## 👥 Authors & Contributors
- **Disha Birari** (IEN: 12327014)
- **Bhakti Patil** (IEN: 12217011)
- **Soham S. Bhere** (IEN: 12217012)
- **Shafe Ahemad** (IEN: 12347003)

**Guide:** Mrs. Swati Patil  
**Department:** Computer Science & Design, New Horizon Institute of Technology and Management (University of Mumbai)

---

## 🚀 Key Features

- **Real-Time News Aggregation:** Dynamic fetch using GNews API for live updates.
- **Categorized News Feed:** Browse articles under General, Sports, Entertainment, Business, Technology, Science, Health, World, and Nation.
- **Keyword Search & Filters:** Search for articles using keywords or filter by date and source.
- **NLP Abstractive Summarization:** Uses models like BART and T5 to generate concise news summaries.
- **Responsive UI:** Lightweight layout styled with W3.CSS / HTML5 / JavaScript for desktop and mobile access.

---

## 🛠️ Tech Stack & Requirements

### Software Stack
- **Backend Framework:** Python 3.13.2, Django 5.1.7
- **API Integration:** GNews API
- **Frontend:** HTML5, W3.CSS / CSS, JavaScript (ES2024)
- **IDE:** Visual Studio Code (v1.83.1)

### System Requirements
- **OS:** Windows 8+ or Android 10+
- **RAM:** Minimum 4 GB
- **Browser:** Google Chrome, Mozilla Firefox, or modern web browser

---

## ⚙️ Installation & Setup Instructions

### 1. Prerequisites
Make sure you have **Python 3.10+** and **Git** installed on your system.

### 2. Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)<your-username>/news-aggregator-system.git
cd news-aggregator-system

 Set Up Virtual Environment
Bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
4. Install Dependencies
Bash
pip install django requests
5. Configure GNews API Key
Register and generate an API key at GNews API.

Add your API key into your Django settings or environment configuration:

Python
# inside settings.py or .env file
GNEWS_API_KEY = "YOUR_ACTUAL_GNEWS_API_KEY"
6. Apply Database Migrations & Run Server
Bash
python manage.py migrate
python manage.py runserver
