# 🏀 NBA Player Prop Prediction System

A machine learning system that analyzes NBA player stats and betting odds to identify value-based player prop predictions. The project uses public NBA data and FanDuel odds to train models that estimate the likelihood of player performance outcomes and align them with favorable betting lines.

---

## 🚀 Features

- 🧠 Predicts NBA player prop outcomes (over/under)
- 🔗 Integrates real-time FanDuel odds using The Odds API
- 📊 Uses historical player stats for data-driven modeling
- ⚙️ Automated data collection, model retraining, and deployment with GitHub Actions
- 🌐 FastAPI backend for serving model predictions via API
- 🔔 Optional alerts for high-confidence bets via webhook or Discord

---

## 📦 Tech Stack

- **Python 3.9**
- **Pandas**, **NumPy**, **Scikit-learn**, **TensorFlow**
- **FastAPI**, **Uvicorn**
- **GitHub Actions** (automation)
- **Render / Railway** (optional deployment)
- **The Odds API** (for sportsbook odds)

---

## 🔧 Project Structure

```text
nba-prop-model/
│
├── data/ # Raw and processed data files (CSV, JSON)
├── models/ # Saved machine learning models
├── fetch_nba_stats.py # Script to fetch historical NBA player stats
├── fetch_fanduel_odds.py # Script to fetch FanDuel odds via The Odds API
├── merge_data.py # Combines player stats with odds data
├── train_model.py # ML/DL model training script
├── predict.py # Script to make predictions using the trained model
├── app.py # FastAPI app to serve predictions as an API
├── send_alerts.py # Optional script to send alerts for high-confidence picks
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .env # Environment variables (API keys) — not committed to GitHub
```


## 🧠 Inspiration

This project was built as a demonstration of applying data science and machine learning to real-world 
analytics, not as a gambling tool. The focus is on statistical modeling, automation, and MLOps.