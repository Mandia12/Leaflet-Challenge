# Leaflet-Challenge

## Overview

This project is an interactive map visualization of earthquake data, showcasing the location, magnitude, and depth of earthquakes around the world. The map is built using D3.js and utilizes a GeoJSON data source to plot earthquake markers on a interactive map.

## Features

Interactive map displaying earthquake locations, sized by magnitude and colored by depth
Pop-up windows displaying important earthquake information, including:  
Location  
Time  
Magnitude  
Depth  
Legend showing the color scale used to represent earthquake depths

## Technical Details

Data source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/significant_month.geojson  
Tools: D3, Leaflet, Javascript, HTML, CSS  
Marker styling:  
  Size: proportional to earthquake magnitude  
  Color: based on earthquake depth, with a gradient of colors to represent different depth ranges  
  Pop-up windows: bound to each earthquake marker, displaying relevant information  

## How to Use

Open the index.html file in a web browser to view the interactive map.  
Zoom in and out using the mouse wheel or touch gestures.  
Click on an earthquake marker to view its corresponding pop-up window.
