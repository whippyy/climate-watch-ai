# 🌍 Climate Watch AI

**AI-Powered Wildfire Risk Prediction and Environmental Monitoring**

Climate Watch AI uses machine learning and real-time environmental data to predict wildfire risks and visualize climate threats. This project is designed for solo development with a focus on quick MVP delivery within about a month, aiming to empower communities and decision-makers.

---

## 🚀 Project Goals (4–5 Week MVP)

- Build a baseline wildfire risk prediction model using historical data  
- Provide a simple backend API for risk prediction  
- Develop an interactive React dashboard with maps and charts  
- Deploy a live app with documented usage and insights  

---

## 🧠 Key Features

| Feature                     | Status (MVP Focus)                                |
|----------------------------|--------------------------------------------------|
| 🔥 Wildfire Risk Prediction | Baseline model with historical data              |
| 🗺️ Geospatial Dashboard      | Map view showing risk overlays                    |
| 📈 Data Visualization        | Simple charts with fire trends                    |
| 📡 Backend API               | `/predict-risk` endpoint                          |
| 🚀 Deployment                | Hosted frontend and backend                        |

---

## 🛠️ Tech Stack

### Backend
- Python, FastAPI, scikit-learn or XGBoost  
- Data processing with pandas and Jupyter notebooks

### Frontend
- React, Mapbox GL or Leaflet  
- Chart.js or Recharts for charts

### Deployment
- Render (backend)  
- Netlify or Vercel (frontend)

---

## 📁 Project Structure


climate-watch-ai/
│
├── backend/                    # Python API + ML models
│   ├── app/                    # FastAPI or Flask app
│   │   ├── main.py
│   │   ├── routes/
│   │   └── services/
│   ├── models/                 # Trained ML models, model scripts
│   ├── data_pipeline/          # ETL jobs for satellite/weather data
│   ├── requirements.txt
│   └── Dockerfile
│
├── frontend/                   # React dashboard
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── package.json
│   └── tailwind.config.js
│
├── notebooks/                  # Jupyter Notebooks for EDA & modeling
│   ├── 01_explore_wildfire_trends.ipynb
│   ├── 02_weather_risk_model.ipynb
│   ├── 03_geospatial_hotspot_analysis.ipynb
│   └── README.md
│
├── data/                       # Raw and processed data
│   ├── raw/
│   └── processed/
│
├── reports/                    # Data reports, visualizations, insights
│   ├── pdf/
│   ├── dashboard/
│   └── figures/
│
├── .env.example                # Template for environment variables
├── .gitignore
├── README.md
└── roadmap.md                  # Development milestones + feature plan

---

## 🧪 Example Use Cases

- 🌲 Predict regions at highest wildfire risk in the next 7 days
- 🧭 View climate trends over time (e.g., rising average temperatures)
- 🧹 Help city officials prioritize resource deployment during fire season
- 📣 Educate the public through interactive climate dashboards

---

## 📌 Status

🟢 **MVP in development**  
✅ Data collection and preprocessing  
🛠️ Working on: Fire risk prediction model + initial map dashboard

---

## 🙌 Contributions Welcome!

Want to help improve climate safety and environmental monitoring with code?  
Check out the [roadmap](./roadmap.md), open an issue, or submit a PR.

---

## 📜 License

MIT License © 2025 Henry Le  
Data sources belong to their respective providers (NASA, NOAA, USGS).

---

## 🌱 Inspired By

- Global Forest Watch
- Climate TRACE
- Google’s AI for Disaster Response