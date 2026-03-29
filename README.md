
# 🎧 Spotify Listening Behavior Analysis & Skip Prediction

## 📌 Project Overview

This project focuses on analyzing Spotify listening behavior and predicting whether a track will be skipped using Machine Learning. It also includes an interactive Power BI dashboard to visualize album, artist, and track-level insights.

## 🚀 Key Features

* ✅ Data Cleaning & Preprocessing
* ✅ Time-based Feature Engineering
* ✅ Skip Prediction using Random Forest Classifier
* ✅ Recommendation System based on listening patterns
* ✅ Interactive Dashboard (Power BI)
* ✅ Album, Artist & Track-level Analysis

---

## 🧠 Machine Learning Model

* **Algorithm Used:** Random Forest Classifier
* **Target Variable:** `skipped` (0 = Not Skipped, 1 = Skipped)
* **Input Features:**

  * Platform
  * Shuffle
  * Listening Time (Hour, Day, etc.)
  * Track / Artist / Album Encoded Features

---

## 📊 Dashboard Insights (Power BI)

The dashboard provides:

* 📈 Listening trends over time
* 🎤 Top Artists & Albums
* 🎵 Most Played Tracks
* 🔄 Skip behavior patterns
* 📱 Platform-based usage analysis

---

## 🛠️ Tech Stack

* **Programming:** Python 🐍
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook / VS Code

---

## 📂 Project Structure

```
spotify-analysis/
│
├── data/
│   └── spotify_data.csv
│
├── notebooks/
│   └──  spotify_analysis_model.ipynb
│
├── dashboard/
│   └── spotify_dashboard.pbix
│
├── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── model.py
│   └── recommendation.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Data Preprocessing Steps

* Handled missing values:

  * Filled categorical columns with `"Unknown"`
  * Converted boolean columns (`shuffle`, `skipped`) to integers
* Removed invalid or null target values
* Encoded categorical features using Label Encoding / One-Hot Encoding

---

## 🔍 Feature Engineering

* Extracted:

  * Hour of listening
  * Day of week
  * Session behavior
* Converted timestamps into meaningful patterns
---

## 🎯 Recommendation System

A simple recommendation system was implemented:

* Suggests tracks based on:

  * User listening history
  * Frequently played artists
  * Similar patterns

---

## 📈 Results

* Successfully predicted skip behavior
* Identified key patterns in:

  * User engagement
  * Platform usage
  * Listening habits
---

## 💡 Future Improvements

* Deep Learning models (LSTM for sequence prediction)
* Real-time recommendation system
* Deployment using Streamlit / Web App
* Advanced NLP for song metadata

---
