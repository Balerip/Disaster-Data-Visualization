# Disaster-Data-Visualization

## Real-Time Disaster Tracking Dashboard

This project integrates wildfire and earthquake data from **NASA FIRMS** and **USGS** APIs to visualize global natural disaster activity. A Python pipeline is used to fetch, clean, and geo-tag the data using **GeoPandas**, and the results are visualized with an interactive **Tableau Public dashboard**.

---

## Live Dashboard

🔗 [Click here to view the interactive Tableau dashboard](https://public.tableau.com/app/profile/panchami.baleri/viz/INFO_7374_Dashboard/FInalDashboard)

---

## Features

- Tracks wildfires using NASA FIRMS API
- Tracks earthquakes using USGS API
- Uses spatial joins to map lat/lon to countries
- Visualizes key insights with choropleth maps, dot plots, bar charts, and trend lines
- Designed for emergency planners, researchers, and policy makers

---

## Tech Stack

- **Python**:
  - `pandas`, `geopandas`, `requests`, `shapely`
- **Tableau Public** (for dashboard visualization)
- **Data Sources**:
  - [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/api/area/)
  - [USGS Earthquake API](https://earthquake.usgs.gov/fdsnws/event/1/)
- **Country shapefiles** from Natural Earth for spatial mapping

---

## Dashboard Insights: Earthquake Visuals Explained

### 1. Effected Areas Earthquake (Choropleth Map)
- Darker blue countries have higher earthquake frequency.
- Highlights seismic hotspots, especially along the Pacific Ring of Fire.
- Helps prioritize disaster preparedness in frequently affected regions.

### 2. Global Earthquake Map (Dot Map)
- Each dot is an earthquake; color represents magnitude.
- Tectonic boundaries are clearly visible.
- Useful for visualizing both density and intensity of seismic activity.

### 3. Top Countries - Earthquakes (Bar Chart)
- Ranks countries by number of events.
- Color shading indicates magnitude distribution within each country.
- Crucial for research, funding decisions, and emergency planning.

### 4. 7-Day Moving Average Earthquake (Line Chart)
- Smooths daily fluctuations to show overall trends.
- Peaks suggest periods of increased tectonic activity.
- Useful for identifying potential aftershock sequences or stress periods.

### 5. Magnitude vs Depth (Scatter Plot)
- Each point shows an earthquake’s depth vs. magnitude.
- Shallow, high-magnitude quakes are the most destructive.
- Key tool for assessing potential human and infrastructure impact.

---

These visualizations offer a global overview of seismic activity and its geographic distribution. When combined with wildfire data, this dashboard enables:

- Faster response by emergency teams
- Smarter resource allocation by policymakers
- Deeper insights for climate and environmental researchers

