# ai-news-aggregator1
AI-powered news aggregation and summarization dashboard
TYour content is correct — just Markdown formatting is broken (missing closing
Here is the **fully corrected, clean, GitHub-ready version** 👇

---

# 📄 ✅ COPY THIS FINAL VERSION

`
markdown
# ai-news-aggregator

# 🚀 AI News Aggregator Dashboard

An AI-powered dashboard that aggregates, deduplicates, and summarizes the latest AI news from multiple high-quality sources.

---

## 📌 Features

- 📰 Multi-source AI News Aggregation (20+ sources)
- 🔁 Deduplication Logic
- 🧠 AI Summarization of articles
- ⭐ Favorites System
- 📣 Broadcast Options (Email, LinkedIn, WhatsApp - mocked)
- 📊 Dashboard Stats (Total News, Sources, Favorites)
- 🔄 Refresh Feed

---

## 🧱 System Architecture

RSS Sources → Fetcher → Normalization → Deduplication → Database → API → Frontend Dashboard

---

## ⚙️ Tech Stack

### Backend
- FastAPI
- SQLAlchemy
- Feedparser
- Newspaper3k
- Sumy

### Frontend
- React
- Axios

---

## 🗄️ Database Schema

- news_items → stores articles  
- favorites → saved items  
- broadcast_logs → broadcast history  

---

## 🚀 How to Run

### 🔹 Backend

cd backend
pip install -r requirements.txt
uvicorn main:app --reload
`
Open: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

---

### 🔹 Frontend

cd frontend
npm install
npm start
Open: [http://localhost:3000](http://localhost:3000)

---

### 🐳 Docker (Backend)

cd backend
docker build -t ai-news-backend .
docker run -d -p 8000:8000 ai-news-backend
---

## 📊 Dashboard

* Displays latest AI news
* Shows total sources, news count, favorites

### Actions:

* ⭐ Favorite
* 🧠 Summarize
* ✍️ Generate Caption
* 📣 Broadcast

---

## 🧠 AI Integration

* Extracts article content using Newspaper3k
* Summarizes using NLP (Sumy)
* Generates captions for sharing

---

## 📦 Deliverables Covered

* ✔ News ingestion & normalization
* ✔ Deduplication logic
* ✔ Dashboard visualization
* ✔ Favorites system
* ✔ Broadcast simulation
* ✔ Database integration
* ✔ Deployment-ready backend (Docker)

---

## ⚠️ Notes

* Some sources (e.g., Reddit) may block scraping → fallback summary used
* Broadcast features are mocked for MVP

---

## 👨‍💻 Author

Durva Pednekar

---


