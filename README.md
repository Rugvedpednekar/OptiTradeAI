# 🚀 OptiTradeAI – AI-Powered Options Sentiment & Signal Explorer

**MongoDB "AI in Action" Hackathon Submission**  
_A next-gen tool for understanding financial market sentiment and trading signals using AI and MongoDB Atlas Vector Search._

---

## 📌 Overview

Options trading is deeply influenced by sentiment and macro events — yet understanding these relationships in real time is hard. **OptiTradeAI** solves this by combining:

- **Real-time financial news and Reddit feeds**
- **AI-based sentiment analysis**
- **Vector embeddings + MongoDB Atlas Vector Search**
- **LLM-based insights**
- **Google integrations (charts, news, maps)**

🧠 Our goal: Help traders and analysts uncover hidden sentiment trends and find **similar historical market conditions** to guide trading decisions.

---

## 🔍 Features

- 🔎 **Search any stock ticker (e.g., AAPL, TSLA, NVDA)**
- 📰 Fetch real-time news and Reddit posts
- 💬 Sentiment classification (Bullish / Neutral / Bearish)
- 🧠 LLM summary: “What are traders saying about NVDA options this week?”
- 🧭 **Vector Search**: Find semantically similar market events using `sentence-transformers` and MongoDB Atlas
- 📈 Visualize options activity alongside sentiment trends and price movements
- 📊 Google Charts for historical overlays

---

## 🧰 Tech Stack

| Layer        | Tools Used |
|--------------|------------|
| **Frontend** | React.js, TailwindCSS, Google Charts |
| **Backend**  | Python (Flask), FastAPI |
| **Database** | MongoDB Atlas (Vector Search, Atlas Search) |
| **NLP / AI** | Sentence Transformers, FinBERT, OpenAI GPT-4 |
| **Google APIs** | Google Finance (for price overlays), News API |
| **Vector DB** | MongoDB Atlas Vector Search |

---

## 🧪 Demo

🔗 **Live Demo**:
📽️ **Demo Video**:
📦 **Devpost Submission**:

---

## 📂 Folder Structure
OptiTradeAI/
├── backend/ # Python Flask app
│ ├── routes/
│ └── utils/
├── frontend/ # React frontend
│ ├── src/
│ └── public/
├── vector_index/ # Sentence embedding setup
├── data/ # Sample dataset
├── README.md
├── requirements.txt
└── .gitignore


