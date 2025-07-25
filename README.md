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

## Dashboard Insights: 


Earthquake Visuals Explained
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

Fire Visuals Explained


### 2.⁠ ⁠Global Map Fire:

Next, on the Global Fire Map, each orange dot represents a detected fire event, plotted using satellite data.
•⁠  ⁠This map gives a more granular view, showing exactly where fires have occurred, not just which countries are affected.
•⁠  ⁠Notice the dense clusters of fires in central Africa, Southeast Asia, and Australia. These clusters can indicate either seasonal burning, agricultural practices, or extreme wildfire events.
•⁠  ⁠This level of detail is especially useful for researchers and disaster managers who need to pinpoint specific locations for intervention or further study.

### 3.⁠ ⁠Top Countries

Moving on to the Top Countries by Fire Count bar chart, we can see the countries with the highest number of fire detections.
•⁠  ⁠South Sudan leads with the most fire events, followed by the Central African Republic, India, and several other African and Asian countries.
•⁠  ⁠This ranking helps us understand not just where fires are happening, but which countries are facing the greatest frequency and possibly the greatest risk.
•⁠  ⁠Such insights are crucial for allocating international aid, focusing research, or launching awareness campaigns in the most affected regions.


### 4.⁠ ⁠Trend

Here we have the Fire Trend in the United States over time, shown as a line chart of maximum fire brightness.
•⁠  ⁠The chart tracks the intensity of fires detected each day from January to April.
•⁠  ⁠We see that fire activity is persistent, with several peaks and valleys, indicating periods of higher and lower fire intensity.
•⁠  ⁠Monitoring these trends helps agencies anticipate when resources might be most needed and can reveal the impact of weather, policy, or prevention efforts.

### 5.⁠ ⁠Brightness vs frp
Finally, the Brightness vs Fire Radiative Power (FRP) scatter plot lets us explore the relationship between a fire’s brightness (how hot or intense it is) and the energy it releases.
•⁠  ⁠Each dot represents a fire event, colored by continent.
•⁠  ⁠As expected, we see a positive trend: higher brightness generally means higher FRP, which indicates more intense and potentially more damaging fires.
•⁠  ⁠This plot is valuable for scientists and analysts who want to distinguish between regular, low-intensity fires and the most severe, high-impact events.

These visualizations offer a global overview of seismic activity and its geographic distribution. When combined with wildfire data, this dashboard enables:

- Faster response by emergency teams
- Smarter resource allocation by policymakers
- Deeper insights for climate and environmental researchers

