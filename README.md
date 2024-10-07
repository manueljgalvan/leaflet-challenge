# USGS Earthquake Data Visualization

## Project Overview

The **United States Geological Survey (USGS)** plays a crucial role in collecting scientific data related to natural hazards, ecosystems, environmental health, and the impacts of climate and land-use changes. However, despite the vast amount of earthquake data collected worldwide, USGS currently lacks an efficient and informative way to visualize this information.

This project is dedicated to building an earthquake data visualization tool to help USGS better educate the public, government organizations, and researchers on seismic activity, while also showcasing the importance of funding for natural hazard research and mitigation.

## Features

This tool provides a dynamic and interactive map using **Leaflet** and **D3.js** that visualizes real-time earthquake data fetched from the USGS's public **GeoJSON API**. Key features include:

1. **Map Visualization:**
   - An interactive map that displays earthquake data using a layered tile-based map interface.
   - Multiple map layers, including Street View and Topographic View, that can be toggled by the user.
   - Markers on the map scale in size according to the magnitude of each earthquake.

2. **Marker Details:**
   - Earthquake markers are color-coded based on the depth of the quake, providing an easy-to-understand visualization of seismic activity.
   - A legend is provided to show the relationship between earthquake depth and the corresponding marker colors.
   - Each marker includes a tooltip that displays detailed information, including the earthquake's magnitude, location, and depth.

3. **Live Data Fetching:**
   - The app connects to the USGS GeoJSON API to fetch up-to-date earthquake data for the last seven days.
   - Earthquake data points are dynamically plotted on the map based on their geographic coordinates.

## Installation and Usage

### Prerequisites
To run this project, you will need:
- A modern web browser (Google Chrome, Firefox, etc.)
- Internet connection (to fetch earthquake data from the USGS API)
- Basic knowledge of HTML, JavaScript, and CSS

### How to Run
1. Clone or download this repository.
2. Open the `index.html` file in your browser.
3. The map will load, and earthquake data for the last seven days will be displayed automatically.

### Technology Stack
- **JavaScript**: The core scripting language for interactivity.
- **Leaflet**: For rendering the interactive map.
- **D3.js**: For data handling and visualization.
- **USGS GeoJSON API**: For fetching live earthquake data.

## Requirements

The project satisfies the following requirements:

### Map (60 Points)
- The **TileLayer** loads correctly without errors.
- The app connects to the USGS **GeoJSON API** using D3 without errors.
- Earthquake markers vary in size based on magnitude.
- A legend clearly indicates the depth of each earthquake and its corresponding marker color.

### Data Points (40 Points)
- Earthquake marker sizes scale with the magnitude of each quake.
- Marker colors change based on the depth of the earthquake.
- Each marker includes a tooltip showing magnitude, location, and depth.
- All earthquake data points load in the correct geographic locations.

