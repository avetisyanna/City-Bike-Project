# Citi Bike Data Analysis Project

This project analyzes Jersey City Citi Bike trip data for 2025.

It follows a step-by-step data analytics workflow: downloading data, cleaning and enriching it, adding weather information, creating visualizations, and exploring neighborhood-level geospatial patterns.

---

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── data
│   └── citibike
            └── JC ── .gitkeep
├── .gitignore
└── notebooks
    ├── 1_Download_Citibike_Jersey_Data.ipynb
    ├── 2_Data_Enrichment.ipynb
    ├── 3_Weather_Data.ipynb
    ├── 4_Data_Visualization.ipynb
    └── 5_Neighborhood_Analysis.ipynb
```

---

## Technologies Used

- **Python 3**: Main programming language
- **Pandas & NumPy**: Data cleaning, transformation, and aggregation
- **Plotly Express**: Interactive visualizations
- **Folium**: Map-based visualizations
- **GeoPandas**: Neighborhood-level geospatial analysis
- **Jupyter Notebook**: Step-by-step analysis workflow

---

## Project Workflow

### 1. Data Download

The first notebook downloads Jersey City Citi Bike trip data for 2025, extracts monthly files, and creates a combined yearly dataset.

### 2. Data Enrichment

The second notebook prepares the dataset for analysis by handling missing values and creating useful derived columns, including:

- ride duration
- date
- month
- month name
- day of week
- hour
- season

### 3. Weather Data

The weather notebook collects daily weather data and prepares it for merging with Citi Bike ride activity.

### 4. Data Visualization

The visualization notebook analyzes ride patterns by:

- month
- season
- day of week
- hour
- top start stations
- top end stations
- weather conditions

### 5. Neighborhood Analysis

The final notebook focuses on geospatial analysis, including:

- station-level activity
- top routes
- route lines on maps
- neighborhood-level activity
- choropleth maps

---

## Main Goal

The goal of this project is to practice a complete data analytics workflow using real-world transportation data and to understand how ride activity changes across time, stations, weather conditions, and neighborhoods.

---

## Note

This project was completed as part of my learning process in data analytics.

Some parts are still being improved, especially the geospatial analysis section.
