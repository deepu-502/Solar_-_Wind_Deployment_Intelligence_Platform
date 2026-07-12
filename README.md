<div align="center">

# ☀️ Solar & Wind Deployment Intelligence Platform

### AI-Powered Renewable Energy Site Recommendation System

Analyze environmental, geographical, and climatic data to identify the most suitable locations for solar and wind energy deployment.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker)

</div>

---

# 📌 Project Overview

The **Solar & Wind Deployment Intelligence Platform** is an AI-powered web application that helps renewable energy companies identify the best locations for solar farms and wind farms.

The platform analyzes:

- Solar Irradiance
- Wind Speed
- Terrain
- Elevation
- Land Cover
- Weather Conditions
- Infrastructure Availability
- Environmental Constraints

Using Machine Learning and GIS analysis, it predicts energy generation potential and recommends the most suitable deployment locations.

---

# 🚀 Features

- 🔐 User Authentication
- 🌍 Interactive GIS Maps
- ☀ Solar Energy Prediction
- 💨 Wind Energy Prediction
- 📍 Site Suitability Analysis
- 📊 Dashboard & Analytics
- 📈 Forecasting
- 📄 PDF Report Generation
- 🔔 Notifications
- 🐳 Docker Deployment

---

# 🏗️ System Architecture

```
React Frontend
        │
        ▼
FastAPI Backend
        │
 ┌──────┴───────┐
 │              │
 ▼              ▼
PostgreSQL   MongoDB
        │
        ▼
 ML Prediction Models
        │
        ▼
 GIS + Weather APIs
```

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Tailwind CSS
- Leaflet
- Axios

## Backend

- FastAPI
- Python
- SQLAlchemy
- JWT Authentication

## Database

- PostgreSQL
- PostGIS
- MongoDB

## Machine Learning

- Scikit-Learn
- TensorFlow
- XGBoost

## GIS

- GeoPandas
- Rasterio
- GDAL
- Shapely

## APIs

- NASA POWER
- Sentinel Hub
- OpenWeather
- OpenStreetMap

---

# 📂 Project Structure

```
Solar-Wind-Deployment-Intelligence/
│
├── backend/
├── frontend/
├── datasets/
├── models/
├── notebooks/
├── docs/
├── docker/
├── reports/
├── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/deepu-502/solar-and-wind-development-intelligence.git
```

## Backend

```bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|----------|------------------|----------------|
| POST | /auth/login | Login |
| POST | /solar/predict | Solar Prediction |
| POST | /wind/predict | Wind Prediction |
| POST | /site/analyze | Site Analysis |
| GET | /reports | Generate Reports |

---

# 📊 Workflow

```
Location
     │
     ▼
Environmental Data
     │
     ▼
GIS Processing
     │
     ▼
ML Prediction
     │
     ▼
Suitability Score
     │
     ▼
Deployment Recommendation
```

---

# 🎯 Future Enhancements

- Hybrid Solar + Wind Recommendation
- Live Weather Integration
- Satellite Image Classification
- AI Chatbot
- Mobile Application
- Real-time Monitoring

---

# 👩‍💻 Author

**Seelamsetty Deepika Sai**

Final Year B.Tech CSE

GitHub: https://github.com/deepu-502

---

# 📜 License

This project was developed as part of the **Infosys Springboard Virtual Internship**.

Licensed under the MIT License.

---

<div align="center">

⭐ Star this repository if you found it useful!

Made with ❤️ by **Seelamsetty Deepika Sai**

</div>
