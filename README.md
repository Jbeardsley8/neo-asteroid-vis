# 🚀 Near-Earth Asteroid 3D Visualization

Interactive 3D Visualation of near-Earth asteroid orbits.

## 🌌 Overview

This project was created to deepen my experience working with APIs while exploring an area I find fascinating, space data.

### 📸 Demo

![3D Orbit Visualization](assets\msedge_MzyFU8t5XD.gif)

#### 🛰️ Data Source

The near-Earth asteroid data used in this project was retrieved from the **[NASA Near-Earth Object Web Service (NeoWs) API](https://api.nasa.gov/)**.

Data includes:
- Semi-major axis
- Eccentricity
- Inclination
- Ascending node longitude
- Perihelion argument
- Orbital period
- Absolute magnitude
- Hazard status

The data was processed using Python for visualization in Plotly.

##### 🔑 NASA API Key

To run the data pull scripts, you will need a **NASA API key** (free and easy to obtain):

1. Visit [https://api.nasa.gov/](https://api.nasa.gov/).
2. Sign up for an API key.
3. Replace `api_key = "YOUR_KEY_HERE"` in the script with your personal key.

###### Acknowledgements

- **[NASA NeoWs API](https://api.nasa.gov/)** for providing access to near-Earth object data.
- **Plotly**, for enabling interactive 3D visualizations.
- **Python** and its data ecosystem (Pandas, NumPy, Matplotlib, Requests) for data processing and analysis.

