# Disaster-Data-Visualization

# Real-Time Disaster Tracking Dashboard

This project integrates live wildfire and earthquake data from **NASA FIRMS** and **USGS** APIs to visualize natural disaster activity across the globe. It uses a Python data pipeline to clean, enrich, and geo-tag data using **GeoPandas** before visualizing it through an interactive **Tableau dashboard**.

> This project is built with Tableau **Public**

---

## 📊 Dashboard Preview

[View Dashboard on Tableau Public](https://public.tableau.com/app/profile/panchami.baleri/viz/INFO_7374_Dashboard/FInalDashboard)

---

## Features

- Tracks **wildfires** from NASA FIRMS
- Tracks **earthquakes** from USGS
- Performs **country-level mapping** using spatial joins with shapefiles
- Visualizes hotspots, trends, and regions of concern in Tableau


---

## 🧰 Tech Stack

- **Python**
  - `pandas`, `geopandas`, `requests`, `shapely`
- **Tableau Public** (for dashboard visualization)
- **NASA FIRMS API** – fire data
- **USGS Earthquake API** – seismic activity
- **Country shapefiles** – for spatial joins




