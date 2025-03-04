# OpenStreetMap-Visualisation
This project demonstrates how to build an OpenStreetMap (OSM) visualization from geocode data using Python. It uses the osmnx, geopy, and folium libraries to geocode an address, download OSM data, and create an interactive map.

Features
Geocode an address to get latitude and longitude.

Download OSM data for a specific location.

Visualize the map with markers and OSM data using Folium.

Save the map as an interactive HTML file.

Requirements
To run this project, you need the following Python libraries:
osmnx
geopy
folium
The script generates an interactive map with:

Customization
Change Location: Replace "New York, USA" with any other address or place name.

Network Type: Modify network_type in ox.graph_from_place() to drive, walk, bike, or all.

Styling: Customize the map's appearance (e.g., marker color, line thickness) using Folium's options.
