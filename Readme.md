# UAE Fire Tracker
### Team Quantum Leapers

## 1. Project Overview
UAE Fire Tracker is a web-based application designed to visualize and monitor fire hotspot activity across the United Arab Emirates. It provides an interactive dashboard that displays fire-related data through charts, statistics, and geographical maps.

The project uses MODIS and VIIRS satellite data formats and allows users to explore fire activity across different years, analyze trends, and view hotspot locations.

## 2. Key Features

- **Interactive Dashboard:** Displays important fire activity statistics, including total active cells, peak activity day, and average Fire Radiative Power (FRP).
- **Year Selection:** Allows users to explore data from 2022 to 2026.
- **Burning Calendar:** Uses a heatmap to visualize daily fire activity throughout the selected year.
- **Baseline Comparison:** Compares the selected year's fire activity against a reference baseline.
- **Interactive UAE Map:** Displays geographical fire hotspot locations.
- **Data Visualization Modes:** Switches between harmonized grid and raw MODIS + VIIRS representations.
- **NASA FIRMS Integration:** Provides an option to retrieve recent satellite hotspot data using the NASA FIRMS API.
- **CSV Upload:** Allows users to upload satellite data in CSV format for visualization.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the application |
| CSS3 | Styling and dashboard layout |
| JavaScript | Application logic and data processing |
| Apache ECharts | Interactive charts and heatmaps |
| Leaflet.js | Interactive geographical maps |
| NASA FIRMS API | Satellite fire hotspot data |
| CARTO | Map tiles and geographical visualization |

## 4. How It Works

1. The application initially generates sample fire activity data for the selected year.
2. JavaScript processes the data and calculates important statistics.
3. ECharts displays the information through a burning calendar and comparison graph.
4. Leaflet.js displays geographical hotspot locations on an interactive UAE map.
5. Users can upload a CSV file containing NASA FIRMS data to visualize actual satellite observations.
6. Alternatively, users can retrieve recent hotspot information through the NASA FIRMS API.

## 5. Data Sources

The application is designed to work with satellite fire detection data from:

- **MODIS:** Moderate Resolution Imaging Spectroradiometer.
- **VIIRS:** Visible Infrared Imaging Radiometer Suite.
- **NASA FIRMS:** Fire Information for Resource Management System.

NASA FIRMS provides satellite-based fire and thermal anomaly observations.

Official resource: https://firms.modaps.eosdis.nasa.gov/

**Data Disclaimer:** The default historical dashboard uses programmatically generated sample data for demonstration purposes. Actual satellite observations can be loaded through the CSV upload functionality or retrieved through the NASA FIRMS API. Therefore, the default dashboard figures should not be interpreted as verified historical fire records.

## 6. Installation and Usage

No additional software installation is required.

1. Download or clone the project files.
2. Open the HTML file in a modern web browser.
3. Select a year from the dropdown menu.
4. Explore the charts, statistics, and geographical map.
5. Use the CSV upload option to load satellite hotspot data.
6. Use the NASA API option to retrieve recent fire observations.

An active internet connection is required to load the external libraries, map tiles, and NASA FIRMS data.

## 7. Project Objectives

- To develop an accessible platform for visualizing fire hotspot activity in the UAE.
- To make geographical and historical fire information easier to understand.
- To demonstrate the use of satellite-based environmental monitoring data.
- To apply web development and data visualization technologies to a real-world environmental problem.
- To provide an interactive interface for exploring fire activity patterns.

## 8. Future Improvements

- Integration of verified historical satellite datasets.
- Addition of more satellite data sources.
- Improved fire risk analysis and prediction.
- Automated data updates.
- More detailed regional and emirate-wise analysis.
- Development of an early-warning and notification system.

## 9. Team

**Team Name:** Quantum Leapers

**Project:** UAE Fire Tracker

**Category:** Environmental Monitoring and Data Visualization

---

*Developed as a student project to demonstrate how web technologies and satellite data can be used to support environmental monitoring and awareness.*