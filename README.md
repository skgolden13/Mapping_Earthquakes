# Mapping Earthquakes

## Project Overview

This project gathers earthquake GeoJSON data from the USGS API to create interactive maps of earthquakes around the world. The circle around each earthquake is tied to the magnitude of that earthquake. The locations of the tectonic plates is included on the map. The user can choose between a street view (Figure 1), a satellite view (Figure 2), and a dark mode (Figure 3).

This project uses HTML, CSS, JavaScript, Leaflet, and D3.

To use this repository, the user must create a Mapbox account and obtain an API token at [mapbox.com](mapbox.com). This API should be stored in static/js/config.js using the following syntax: const API_KEY = "YOUR TOKEN KEY HERE";

<p align="center">
  <img width="900" alt="Street_View" src="https://github.com/skgolden13/Mapping_Earthquakes/blob/main/Images/Street_View.PNG"><br/>
  Figure 1: Street View Map<br/>
<p/>

<p align="center">
  <img width="900" alt="Street_View" src="https://github.com/skgolden13/Mapping_Earthquakes/blob/main/Images/Satellite_View.PNG"><br/>
  Figure 2: Satellite View Map<br/>
<p/>

<p align="center">
  <img width="900" alt="Street_View" src="https://github.com/skgolden13/Mapping_Earthquakes/blob/main/Images/Dark_View.PNG"><br/>
  Figure 3: Dark Mode Map
<p/>
