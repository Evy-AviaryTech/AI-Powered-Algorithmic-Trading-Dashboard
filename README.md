# 📈 AI Stock Dashboard

A modern AI-powered stock market dashboard that fetches real-time stock prices and displays them using interactive charts. Built with **Next.js, Tailwind CSS, FastAPI, and Recharts**, this project showcases an **AI/ML-based stock prediction model** and a user-friendly frontend.

---

## 🚀 Features

✅ **Real-time Stock Price Fetching** via API
✅ **AI/ML Stock Price Prediction Model** *(Future Improvement)*
✅ **Beautiful UI** with **Tailwind CSS**
✅ **Interactive Data Visualization** using **Recharts**
✅ **Authentication System** *(Planned)*
✅ **Deployed on Vercel & Railway** *(Upcoming)*

---

## 🏗 Tech Stack

### **Frontend:**
- [Next.js](https://nextjs.org/) (React Framework)
- [Tailwind CSS](https://tailwindcss.com/) (Styling)
- [Recharts](https://recharts.org/en-US/) (Stock Chart Visualization)
- [SWR](https://swr.vercel.app/) (Data Fetching)
- [Auth0](https://auth0.com/) (Optional Authentication)

### **Backend:**
- [FastAPI](https://fastapi.tiangolo.com/) (Python-based API)
- [yfinance](https://pypi.org/project/yfinance/) (Stock Market Data)
- [PostgreSQL](https://www.postgresql.org/) (Database)
- [Redis](https://redis.io/) (Caching Layer for FastAPI)

### **Deployment:**
- **Frontend** → [Vercel](https://vercel.com/)
- **Backend** → [Railway](https://railway.app/) / [Render](https://render.com/)
- **Database** → [Supabase](https://supabase.com/) / PostgreSQL

---

## 📥 Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/ai-stock-dashboard.git
cd ai-stock-dashboard
```

### **2️⃣ Set Up the Frontend (Next.js + Tailwind)**
```bash
cd frontend
npm install  # Install dependencies
npm run dev  # Start development server
```
🌍 Open **http://localhost:3000** in your browser.

### **3️⃣ Set Up the Backend (FastAPI)**
```bash
cd backend
python -m venv venv  # Create a virtual environment
source venv/bin/activate  # Activate it (Mac/Linux)
# On Windows: venv\Scripts\activate
pip install -r requirements.txt  # Install dependencies
uvicorn main:app --reload  # Start FastAPI server
```
🌍 API will run at **http://localhost:8000**

---

## ⚙️ Usage

### **1️⃣ Fetch Stock Prices**
```bash
GET http://localhost:8000/stock/AAPL
```
📌 **Response Example:**
```json
{
  "ticker": "AAPL",
  "Close": 185.52,
  "Open": 182.34
}
```

### **2️⃣ Fetch AI-Based Predictions** *(Coming Soon!)*
```bash
GET http://localhost:8000/predict/AAPL
```
📌 **Response Example:**
```json
{
  "ticker": "AAPL",
  "predicted_price": 190.25
}
```
```

---

## 🔗 Deployment Guide

### **Frontend Deployment (Vercel)**
```bash
cd frontend
vercel deploy
```

### **Backend Deployment (Railway)**
1️⃣ Create a **Railway Project**  
2️⃣ Deploy the **FastAPI backend**  
3️⃣ Set Environment Variables:  
   - `DATABASE_URL=<your_postgres_db_url>`
   - `REDIS_URL=<your_redis_url>`

---

## 📊 Future Improvements

- ✅ **AI/ML Predictions** (LSTM model for time series forecasting)
- ✅ **User Authentication** (Auth0 or Clerk.js)
- ✅ **Dark Mode Support**
- ✅ **Portfolio Management Dashboard**
- ✅ **Stock News Sentiment Analysis**

---

## 🤝 Contributing
We welcome contributions! To contribute:
1️⃣ Fork the repository
2️⃣ Create a new feature branch (`git checkout -b feature-new`)
3️⃣ Commit changes (`git commit -m "Added new feature"`)
4️⃣ Push to your branch (`git push origin feature-new`)
5️⃣ Create a **Pull Request** 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

**💡 Have questions?** Open an issue or reach out! 🚀

