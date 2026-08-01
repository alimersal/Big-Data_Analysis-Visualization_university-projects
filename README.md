<div align="center">

# 📊 Big Data Analysis & Visualization
### University Projects Collection

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=flat&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)

*A collection of university big data lab projects covering geospatial analysis, machine learning classification, seismic data exploration, and population trend visualization.*

</div>

---

## 📁 Projects Overview

| # | Project | Type | Tools |
|---|---------|------|-------|
| 1 | [🌍 World Countries Visualization](#1--world-countries-visualization) | Geospatial | Folium · Plotly · Matplotlib |
| 2 | [👥 Countries Population Analysis](#2--countries-population-analysis) | Data Analysis | Folium · Plotly · MongoDB |
| 3 | [🌊 Water Quality Classification](#3--water-quality-classification) | Machine Learning | Scikit-learn · Pandas |
| 4 | [🌋 Earthquakes Analysis 1990–2023](#4--earthquakes-analysis-19902023) | Data Exploration | Pandas · Plotly · MongoDB |

---

## 1 · 🌍 World Countries Visualization

**Goal:** Visualize world countries geographically using three different chart types, classifying each country by its position relative to the equator.

**What it achieves:**
- 🗺️ Interactive Folium map with clickable markers and country tooltips (name, lat, lon)
- 📊 Plotly choropleth — countries colored by latitude (Above / On / Below the Equator)
- 📉 Matplotlib scatter — global country positions with latitude zone bands

**Tools & Libraries:**
`pandas` · `folium` · `plotly.graph_objects` · `matplotlib` · `pymongo`

**Skills Gained:**
> Geospatial visualization · Choropleth mapping · Interactive map rendering · Data filtering

---

## 2 · 👥 Countries Population Analysis

**Goal:** Analyze and visualize global population trends from **1980 to 2050** across all countries.

**What it achieves:**
- 🗺️ World map with per-country population popups (multiple years)
- 📊 Choropleth map showing population distribution globally
- 📈 Bar chart & scatter plot for year-by-year population comparison

**Tools & Libraries:**
`pandas` · `folium` · `plotly.express` · `pymongo`

**Skills Gained:**
> Time-series analysis · Population data visualization · MongoDB data retrieval · Multi-chart dashboards

---

## 3 · 🌊 Water Quality Classification

**Goal:** Build and compare three ML classifiers to predict whether a water sample is **safe or unsafe** based on chemical and biological indicators.

**What it achieves:**
- 🤖 Three models trained and evaluated: **KNN · Naive Bayes · Logistic Regression**
- 📊 Accuracy and ROC-AUC comparison to identify the best classifier
- 🔬 Feature analysis of water quality indicators

**Tools & Libraries:**
`scikit-learn` · `pandas` · `numpy` · `matplotlib`

**Skills Gained:**
> Binary classification · Model evaluation (Accuracy, ROC-AUC) · Feature engineering · Comparative ML analysis

---

## 4 · 🌋 Earthquakes Analysis 1990–2023

**Goal:** Explore and analyze global earthquake data spanning over **33 years** to uncover patterns in magnitude, location, and frequency.

**What it achieves:**
- 📡 Data loading and processing from MongoDB
- 🗺️ Geospatial distribution of earthquakes worldwide
- 📊 Trend analysis by year, magnitude, and region

**Tools & Libraries:**
`pandas` · `plotly` · `pymongo`

**Skills Gained:**
> Large dataset handling · Temporal trend analysis · Seismic data exploration · Geospatial plotting

---

## 🛠️ Tech Stack

```
📦 Data Layer       →  MongoDB (NoSQL database)
🐍 Core Language    →  Python 3.x
📓 Environment      →  Jupyter Notebook
📊 Visualization    →  Plotly · Folium · Matplotlib
🤖 ML Framework     →  Scikit-learn
🔧 Data Handling    →  Pandas · NumPy
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects.git

# Install dependencies
pip install pandas numpy plotly folium pymongo scikit-learn matplotlib jupyter

# Start Jupyter
jupyter notebook
```

> ⚠️ **Note:** Projects 1, 2, and 4 require a running **MongoDB** instance at `localhost:27017` with the relevant collections loaded.

---

## 📬 Contact

**Ali Mersal** · [ali.m.mersal@gmail.com](mailto:ali.m.mersal@gmail.com) · [GitHub](https://github.com/alimersal)

---

<div align="center">
  <sub>🎓 University Big Data Lab Projects · Made with Python & Jupyter</sub>
</div>
