# 🪐 ExoHabitAI: AI-Driven Exoplanet Habitability Predictor

[![Frontend on Netlify](https://img.shields.io/badge/Frontend-Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://exohabitai-app.netlify.app/)
[![Backend on Render](https://img.shields.io/badge/Backend-Render-46E3B7?style=for-the-badge&logo=render)](https://exohabitai-1-emk9.onrender.com)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-orange?style=for-the-badge)](#)

**🌐 Live Application:** https://exohabitai-app.netlify.app/  
**🔌 Backend API:** https://exohabitai-1-emk9.onrender.com  

---

## 📋 Project Overview

**ExoHabitAI** is a full-stack machine learning web application that predicts whether an exoplanet has the potential to support life.  
The system evaluates **planetary, stellar, and orbital parameters** and classifies planets as **Habitable** or **Non-Habitable** using an AI-based decision model.

The project combines:
- Scientific data analysis
- Machine learning prediction
- Interactive web visualization
- Cloud deployment

---

## ⚡ Quick Highlights

- 🌍 **1,089** exoplanets analyzed  
- ⭐ **13** potentially habitable candidates identified  
- 🎯 **99.17%** prediction accuracy  
- 🔍 **83.33%** recall (habitable planet detection)  
- 🧪 **39** astrophysical parameters evaluated  
- ⚡ **< 50 ms** prediction response time  

---

## ⭐ Core Features

### 🧠 Intelligent Prediction Engine
- Machine learning-based habitability classification
- Optimized decision threshold for higher recall
- Supports both single and sample-based predictions
- Clear confidence score and ESI value

### 🖥️ Interactive Web Interface
- Modern dark-space themed UI
- Smooth animations and transitions
- Real-time loading indicators
- Simple and user-friendly design

### 📊 Ranking System
- Automatically ranks planets by habitability score
- Clear labels for habitable and non-habitable planets
- Filterable results for better analysis

### 📈 Data Visualization
- Pie chart: habitable vs non-habitable distribution
- Bar chart: confidence score ranges
- Top-10 planets by prediction confidence
- KPI cards for quick insights

---

## 🛠️ Technology Stack

| Layer | Technology |
|-----|-----------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python, Flask |
| **Machine Learning** | Scikit-Learn, XGBoost, Random Forest |
| **Visualization** | Chart.js |
| **Server** | Gunicorn |
| **Deployment** | Netlify (Frontend), Render (Backend) |

---

## 📊 Model Performance

| Metric | Value |
|------|-------|
| **Accuracy** | 99.17% |
| **Recall** | 83.33% |
| **Precision** | 38.46% |
| **F1 Score** | 52.63% |
| **Decision Threshold** | 0.0763 |

**Note:**  
The model is recall-optimized to avoid missing potentially habitable planets.

---

## 🚀 Getting Started (Local Setup)

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py

Backend runs at:

http://localhost:5000
Frontend Setup
Open index.html in a browser

Ensure API URL is correctly set:

const API_URL = "http://localhost:5000";
🌐 Live Deployment

Frontend: https://exohabitai-app.netlify.app/

Backend: https://exohabitai-1-emk9.onrender.com

📡 API Endpoints
GET   /               Backend status
POST  /predict        Single planet prediction
GET   /rank           Ranked habitability list
📁 Project Structure
ExoHabitAI/
├── backend/
│   ├── app.py              # Flask backend
│   ├── requirements.txt    # Python dependencies
│   └── model/              # ML model files
├── frontend/
│   ├── index.html          # Main UI
│   ├── style.css           # Styling
│   └── script.js           # Client-side logic
├── data/
│   └── dataset.csv         # Processed dataset
├── README.md
└── DEMO_SCRIPT.md
🧪 Testing Checklist

✅ Backend API reachable

✅ Prediction endpoint working

✅ Ranking page loads data

✅ Charts render correctly

✅ No console or server errors

🎓 Deployment Summary

Backend deployed using Flask + Gunicorn on Render

Frontend deployed as static site on Netlify

CORS configured for cross-origin requests

HTTPS enabled by default

📌 Project Status

✅ Completed & Deployed

👨‍💻 Author

Developed by: [Your Name]
Project Type: Final Year / Internship Project
Domain: Machine Learning & Web Development

🌌 Exploring habitability beyond Earth using Artificial Intelligence 🌌
