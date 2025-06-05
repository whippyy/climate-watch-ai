# 🌍 Climate Watch AI

**AI-Powered Wildfire Risk Prediction and Environmental Monitoring**

Climate Watch AI is an open-source platform that uses real-time environmental data and machine learning to predict wildfire risk and visualize climate-related threats. It empowers communities, first responders, and policy makers with early warning systems and data-driven insights.

---

## 🚀 Project Goals

- Predict wildfire risk based on environmental and weather data
- Visualize climate threats using interactive maps and dashboards
- Provide open access to climate trends and insights through data analysis
- Build a scalable and extensible tool to support disaster preparedness and mitigation

---

## 🧠 Key Features

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🔥 Wildfire Risk Prediction | Machine learning models trained on historical wildfire + weather data      |
| 📈 Climate Data Analysis     | Exploratory notebooks and visualizations on trends, hotspots, and risk     |
| 🗺️ Geospatial Dashboard      | React-based map with risk overlays, trends, and statistics                  |
| 📡 Data Pipelines            | Automated ETL jobs for ingesting NASA, NOAA, and other open datasets        |
| 📊 Reports & Insights        | Shareable reports and visuals for communities and decision-makers          |

---

## 🛠️ Tech Stack

### Backend
- Python (FastAPI or Flask)
- Scikit-learn / XGBoost for ML
- PostgreSQL + PostGIS (geospatial DB)
- Docker for deployment

### Frontend
- React + TailwindCSS
- Mapbox or Leaflet for mapping
- Recharts or Chart.js for data viz

### Data & Analysis
- Jupyter Notebooks
- pandas, seaborn, geopandas
- NASA Earthdata, NOAA, USGS APIs

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