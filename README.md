<div align="center">

# 📊 Big Data Analysis & Visualization

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

</div>

A collection of university big data lab projects covering geospatial analysis, machine learning classification, seismic data exploration, and population trend visualization.

---

## 📁 Projects Overview

| # | Project | Type | Tools |
|---|---------|------|-------|-----------------------|
| 1 | [🌍 World Countries Visualization](https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects/tree/master/world_country) | Geospatial | Folium · Plotly · Matplotlib |  
| 2 | [👥 Countries Population Analysis](https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects/tree/master/countries%20population) | Data Analysis | Folium · Plotly · MongoDB |  
| 3 | [🌊 Water Quality Classification](https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects/tree/master/Water%20Quality%20Classification%20Project) | Machine Learning | Scikit-learn · Pandas | 
| 4 | [🌋 Earthquakes Analysis 1990–2023](https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects/tree/master/Eartquakes-1990-2023.csv) | Data Exploration | Pandas · Plotly · MongoDB |

---

## 1 · 🌍 World Countries Visualization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alimersal/Big-Data_Analysis-Visualization_university-projects/blob/master/world_country/average-latitude-longitude-countries.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alimersal/Big-Data_Analysis-Visualization_university-projects/master?filepath=world_country/average-latitude-longitude-countries.ipynb)

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

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alimersal/Big-Data_Analysis-Visualization_university-projects/blob/master/countries%20population/last%20update%20task%20lab%20big%20data.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alimersal/Big-Data_Analysis-Visualization_university-projects/master?filepath=countries%20population/last%20update%20task%20lab%20big%20data.ipynb)

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

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alimersal/Big-Data_Analysis-Visualization_university-projects/blob/master/Water%20Quality%20Classification%20Project/Task.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alimersal/Big-Data_Analysis-Visualization_university-projects/master?filepath=Water%20Quality%20Classification%20Project/Task.ipynb)

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

### Option 1: Run Online (Recommended)
Click the **Colab** or **Binder** badges to run notebooks directly in your browser — no installation needed!

- **Google Colab:** Fast, free GPU/TPU, requires Google account
- **Binder:** No account needed, takes ~1 min to launch

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/alimersal/Big-Data_Analysis-Visualization_university-projects.git

# Install dependencies
pip install pandas numpy plotly folium pymongo scikit-learn matplotlib jupyter

# Start Jupyter
jupyter notebook
```

> ⚠️ **MongoDB Required:** Projects 1, 2, and 4 require a running **MongoDB** instance at `localhost:27017` with the relevant collections loaded.

---

## 📬 Contact

**Ali Mersal** · [ali.m.mersal@gmail.com](mailto:ali.m.mersal@gmail.com) · [GitHub](https://github.com/alimersal)

---

<div align="center">
  <sub> 🎓 University Big Data Lab Projects · Made with Python & Jupyter </sub>
</div>
