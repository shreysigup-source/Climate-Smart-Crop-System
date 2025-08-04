Climate-Smart Crop Recommendation System

A machine learning–based intelligent crop recommendation system designed to assist farmers in choosing the best crop to grow, based on soil nutrients and real-time weather conditions. This project promotes sustainable agriculture by bridging traditional farming with modern data science tools.

Project Overview

Agriculture remains a critical sector in India, yet farmers often lack access to scientific tools that support decision-making. Our system solves this by using machine learning to predict the **most suitable crop** based on:

- Soil nutrients (N, P, K)
- Environmental factors (temperature, humidity, rainfall)
- Soil pH
- Real-time weather data (via OpenWeatherMap API)

 Key Features

- ✅ **Naive Bayes Model** with ~99.27% accuracy
- 🌐 **Real-Time Weather Data** using OpenWeatherMap API
- 📊 **Power BI Dashboard** for advanced visual insights
- 💡 **Dual Input Modes**: Manual entry and live API-based prediction
- 📱 Future-ready: Designed for eventual mobile and IoT integration

Technologies Used

- **Python** (core implementation)
- **Scikit-learn** (ML models)
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Power BI** (visualization dashboard)
- **OpenWeatherMap API** (live temperature & humidity)
- **GitHub** (version control and collaboration)

ML Models Tried

- Naive Bayes ✅ (Best performer)
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors

Power BI Dashboard Highlights

- 🌦️ Weather trends vs crop yield
- 🧪 NPK distribution per crop
- 🌱 Crop suitability vs pH and rainfall
- 🗺️ Weather map with live API integration
- 🔘 Interactive filters for custom views

Dataset Information

- Source: Kaggle Crop Recommendation Dataset
- Size: 2,200 rows × 8 columns
- Features: `N`, `P`, `K`, `temperature`, `humidity`, `pH`, `rainfall`
- Target: `Crop` (22 classes)
