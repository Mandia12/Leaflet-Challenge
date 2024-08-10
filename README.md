# Leaflet-Challenge

## Overview

This project is an interactive map visualization of earthquake data, showcasing the location, magnitude, and depth of earthquakes around the world. The map is built using D3.js and Leaflet, utilizing a GeoJSON data source to plot earthquake markers on an interactive map.

## Features

- **Interactive Map**: Displays earthquake locations, sized by magnitude and colored by depth.
- **Pop-up Windows**: Show important earthquake information, including:
  - Location
  - Time
  - Magnitude
  - Depth
- **Legend**: Shows the color scale used to represent earthquake depths.

## Technical Details

- **Data Source**: [USGS Earthquake GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/significant_month.geojson)
- **Tools**:
  - D3.js for data manipulation and binding
  - Leaflet for interactive map visualization
  - JavaScript for logic and interaction
  - HTML and CSS for structure and styling
- **Marker Styling**:
  - **Size**: Proportional to earthquake magnitude
  - **Color**: Based on earthquake depth, with a gradient of colors representing different depth ranges
  - **Pop-up Windows**: Bound to each earthquake marker, displaying relevant information

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser to view the interactive map.
3. Use the mouse wheel or touch gestures to zoom in and out of the map.
4. Click on an earthquake marker to view its corresponding pop-up window.
