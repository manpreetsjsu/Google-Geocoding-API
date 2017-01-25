# Google-Geocoding-API

The Python program that prompts for a location, contact a web service (Google Geocoding API) and retrieve JSON and parse that data, and retrieve the formatted (correct) address from the JSON.

Geocoding is the process of converting addresses (like "1600 Amphitheatre Parkway, Mountain View, CA") into geographic coordinates (like latitude 37.423021 and longitude -122.083739), 
which you can use to place markers on a map, or position the map.

The Google Maps Geocoding API provides a direct way to access these services via an HTTP request. 

Google Maps Geocoding API Request Format

A Google Maps Geocoding API request takes the following form:

https://maps.googleapis.com/maps/api/geocode/outputFormat?parameters
where outputFormat may be either of the following values:

json (recommended) indicates output in JavaScript Object Notation (JSON); or
xml indicates output in XML
To access the Google Maps Geocoding API over HTTP, use:

http://maps.googleapis.com/maps/api/geocode/outputFormat?parameters

Reference:-https://developers.google.com/maps/documentation/geocoding/intro
