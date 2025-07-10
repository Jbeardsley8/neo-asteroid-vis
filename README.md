# 🚀 Near-Earth Asteroids: 3D Orbit Visualization

Interactive 3D Visualation of near-Earth asteroid orbits.

[![Live GitHub Page](https://img.shields.io/badge/Live%20GitHub%20Page-%23007ACC?logo=github&logoColor=white)](https://jbeardsley8.github.io/neo-asteroid-vis/)



## Overview

This project was created to deepen my experience working with APIs while exploring an area I find fascinating, space data.

### Demo

![3D Orbit Visualization](assets/msedge_MzyFU8t5XD.gif)

### Data Source

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

### NASA API Key

To run the data pull scripts, you will need a **NASA API key** (free and easy to obtain):

1. Visit [https://api.nasa.gov/](https://api.nasa.gov/).
2. Sign up for an API key.
3. Replace `api_key = "YOUR_KEY_HERE"` in the script with your personal key.

### File Structure

- `neo-asteroid-vis/`
  - `docs/`
    - `index.html` – GitHub Pages landing page
    - `asteroid_orbit_plot.html` – Interactive Plotly visualization
    - `asteroid_orbital_dataset.csv` – Exported asteroid data
    - `htmljpg/`
      - `starfield.jpg` – Space background image
  - `astroid_orbit.ipynb` – Notebook for API pull and visualization
  - `assets/` – GIF for README/demo
    - `orbit_demo.gif`
  - `README.md` 

### References

- [Wikipedia – Orbit Equation](https://en.wikipedia.org/wiki/Orbit_equation)
- [Wikipedia – Kepler Orbit](https://en.wikipedia.org/wiki/Kepler_orbit)
- [Wikipedia – Orbital Elements](https://en.wikipedia.org/wiki/Orbital_elements#Position_in_orbit)

