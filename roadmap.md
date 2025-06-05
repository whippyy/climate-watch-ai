# 🌍 Climate Watch AI – Project Roadmap

This document outlines the development plan for **Climate Watch AI**, from initial MVP to future feature expansions. The project focuses on combining machine learning, climate science, and geospatial visualization to help detect and predict wildfire risks.

---

## ✅ Phase 1: Foundation & MVP

**Goal:** Build a functional prototype that ingests data, runs a basic fire risk prediction model, and displays results in a simple dashboard.

### 🔹 Tasks
- [x] Set up GitHub repo and project structure
- [ ] Ingest historical wildfire & weather datasets (NASA, NOAA, USGS)
- [ ] Clean and process datasets into machine learning-friendly format
- [ ] Exploratory data analysis (wildfire trends, climate variables)
- [ ] Train first fire risk prediction model (XGBoost or Random Forest)
- [ ] Develop backend API with `/predict-risk` endpoint
- [ ] Build simple React frontend with map + chart visualizations
- [ ] Deploy backend (Docker + AWS or Render)
- [ ] Deploy frontend (Netlify or Vercel)

---

## 🔁 Phase 2: Data Expansion & Visualization

**Goal:** Improve model performance and user experience through better data, geospatial tools, and richer visuals.

### 🔹 Tasks
- [ ] Integrate real-time weather API (e.g., Open-Meteo or NOAA)
- [ ] Add vegetation/dryness index (NDVI from MODIS)
- [ ] Introduce PostgreSQL + PostGIS for spatial querying
- [ ] Improve dashboard UX with filtering, zoom, and timeline slider
- [ ] Generate dynamic heatmaps for fire risk
- [ ] Enhance charts with D3 or Recharts for better trend insight
- [ ] Begin publishing periodic PDF reports with insights and plots

---

## 🔮 Phase 3: Advanced ML & Real-Time Features

**Goal:** Build a scalable intelligence system that delivers meaningful real-time predictions.

### 🔹 Tasks
- [ ] Fine-tune deep learning models on satellite image tiles (CNN)
- [ ] Add anomaly detection on real-time sensor/weather streams
- [ ] Auto-update risk levels daily using scheduled ETL jobs
- [ ] Integrate push/SMS alerts using Twilio or Firebase
- [ ] Add authentication for responders to mark impacted zones

---

## 📊 Phase 4: Data Insights & Public Reporting

**Goal:** Use the platform for civic education and decision-making by producing data-driven insights.

### 🔹 Tasks
- [ ] Build notebook-based reporting pipeline (Jupyter → PDF)
- [ ] Visualize climate trends (temperature, rainfall, fire frequency)
- [ ] Share dashboards with non-profits or policymakers
- [ ] Create comparison tool: "How has your region changed?"

---

## 🤝 Long-Term Ideas (Stretch Goals)

- Community reporting feature (citizen fire spotting via app)
- Use drone data or edge devices for remote detection
- Expand globally (Amazon, Australia, Mediterranean regions)
- Integrate with emergency services APIs for real-time response
- Support other disasters (floods, droughts)

---

## 🗓️ Timeline Estimate

| Milestone | Target Date |
|-----------|-------------|
| Phase 1 Completion (MVP) | Mid–July 2025 |
| Phase 2 Visualization Enhancements | August 2025 |
| Phase 3 Real-Time Features | Fall 2025 |
| Phase 4 Insights & Public Launch | Winter 2025 |

---

## 🧑‍💻 Contribution Guidelines

- Use descriptive branches (e.g., `feature/model-v1`)
- Submit issues before large feature changes
- Document any scripts, datasets, or visualizations in `/notebooks/` or `/reports/`

---

## 📫 Stay Updated

Follow the project on GitHub or contact [Your Email or GitHub Profile] for questions and ideas.

