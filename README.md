# Mapping_Earthquakes
## Table of Contents
- [Overview of the Analysis](#overview-of-the-analysis)
    - [Purpose](#purpose)
    - [About the Dataset](#about-the-dataset)
    - [Tools Used](#tools-used)
    - [Description](#description)
- [Results](#results)
- [Summary](#summary)
- [Contact Information](#contact-information)

## Overview of the Analysis
### Purpose:
This project aims to create an interactive world map for earthquakes. Multiple layers added to the map allow the user to select what mode (street, satellite, or dark) to view the map in, and which attributes (earthquakes, major earthquakes, and/or tectonic plates) to show on the map.

### About the Dataset:
This project makes use of GeoJSON data files off of the [USGS (United States Geological Survey) website](https://www.usgs.gov/programs/earthquake-hazards/earthquakes). A GeoJSON file specifically holds geographical data. It represents geographical features (eg: the location of the earthquake) and non-spatial attributes (eg: the magnitude of the earthquake). 

The following three GeoJSON files have been used in this project:
 - [Earthquakes GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
 - [Major Earthquakes GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson) (a 'major earthquake' hereby is defined as an earthquake with a magnitude greater than 4.5)
 - [Tectonic Plates GeoJSON file](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)

### Tools Used:
 - JavaScript ES6
 - HTML
 - CSS
 - Data-Driven Documents (D3) library
 - Leaflet library
 - Mapbox API

### Description:
The code for this project can be found in the [index.html file](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/index.html) and the [folder named 'static'](https://github.com/SohaT7/Mapping_Earthquakes/tree/main/static).

JavaScript and the Data-Driven Documents (D3) library is used to traverse and extract GeoJSON earthquake data and tectonic plate data.  This data is then used to populate a geographical world map, using the Leaflet.js Application Programming Interface (API). 

Each earthquake is represented on the map by a circle of varying size and color. The greater the magnitude of the earthquake, the larger the circle marker and the darker its color (as is shown in the legend on the map as well). Each earthquake circle marker can also be clicked to view its popup marker, which shows the location and magnitude of the earthquake. 

![Popup Marker](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_popupMarker.png)

Leaflet library and Mapbox API add user interface controls to the map, which add multiple layers to the map. The layers added in help view:
 - Earthquakes 
 - Major earthquakes
 - Tectonic plate boundaries

Three additional layers help view the map in different modes:
 - Street mode
 - Satellite mode
 - Dark mode

## Results
The user can toggle the multiple layers options to view the map in a specific mode, and showing only the features selected. 

The following images respectively show us the maps with the following features made visible by the user:
 - Earthquakes
 - Earthquakes and major earthquakes
 - Earthquakes, major earthquakes, tectonic plates 

![Earthquakes](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_earthquakes.png)

![Earthquakes and Major Earthquakes](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_majorEarthquakes.png)

![Earthquakes, Major Earthquakes, and Tectonic Plates](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_tectonicPlates.png)

The images below show the maps with all three features selected (earthquakes, major earhtquakes, and tectonic plates) in the following modes respectively:
 - Street
 - Satellite
 - Dark

![Street Mode](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_tectonicPlates.png)

![Satellite Mode](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_satellite.png)

![Dark Mode](https://github.com/SohaT7/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Images/i_dark.png)

## Summary
This project created an interactive world map that helps the user view earthquakes. Multiple layers added to the map enable the user to select which mode (street, satellite, or dark) to view the map in, and which particular geographical features (earthquakes, major earthquakes, tectonic plates) to view. Ideas for some additional layers that can be added to the geographical world map include adding earthquake data from the past month, the past year, and the past decade.

## Contact Information
Email: st.sohatariq@gmail.com

