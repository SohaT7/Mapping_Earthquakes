# Mapping_Earthquakes
## Table of Contents
- [Overview of the Analysis](#overview-of-the-analysis)
    - [Purpose](#purpose)
    - [About the Dataset](#about-the-dataset)
    - [Tools Used](#tools-used)
    - [Description](#description)
- [Results](#results)
    - [Preprocessing the Data for Principal Components Analysis](#preprocessing-the-data-for-Principal-Components-Analysis)
    - [Reducing Data Dimensions Using Principal Components Analysis](#reducing-data-dimensions-using-Principal-Components-Analysis)
    - [Clustering Cryptocurrencies Using K-Means](#Clustering-Cryptocurrencies-Using-K-Means)
    - [Visualizing Cryptocurrencies Results](#Visualizing-Cryptocurrencies-Results)
- [Summary](#summary)
- [Contact Information](#contact-information)

## Overview of the Analysis
### Purpose:
This project aims to create an interactive world map for earthquakes. 

### About the Dataset:
This project makes use of data stored in a GeoJSON file. 


uses GeoJSON data...which represents geographical features (eg: location where the earthquake occurred) and non-spatial attributes (eg: magnitude of the earthquake). 

### Tools Used:
 - JavaScript ES6
 - Data-Driven Documents (D3) library
 - GeoJSON
 - Mapbox API
 - Leaflet library

### Description:
An option to view the map in 'Street' or 'Satellite' mode was added. This was followed by adding tectonic plate outlines to the map, major earthquakes greater than a magnitude of 4.5, and a third map with a dark styling to it. 

JavaScript and the Data-Driven Documents (D3) library is used to traverse and extract GeoJSON earthquake data and tectonic plate data.  This data is then used to populate a geographical world map, using the Leaflet.js Application Programming Interface (API). 

Leaflet library and Mapbox API...
API requests made to a server to host the geographical map...

Each earhtquake is represented on the map by a circle of varying size and color. The greater the magnitude of the earthquake, the larger the circle marker and the darker its color. Each earthquake circle marker can also be clicked to view its popup marker, which shows the location and magnitude of the earthquake. 

Leaflet control plugins are used to add user interface controls to the map, which add multiple layers to the map. The layers added in help view:
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

## Contact Information
Email: st.sohatariq@gmail.com

