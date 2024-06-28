# Satellite Map API

This project demonstrates how to use the Mapbox API to display a route between two points on a map, with an option to toggle between satellite and streets views.

## Introduction

This project showcases a simple web application that utilizes the Mapbox API to visualize routes between two geographic points. It provides an easy-to-use interface to display satellite imagery, streets maps, and route information.

## Main Code Explanation

The main code is an HTML document (`index.html`) containing JavaScript to initialize the Mapbox map and display route information between two points. It allows users to switch between satellite and streets map styles.

The code sets up a Mapbox map, adds markers for the start and end points, and fetches route data using the Mapbox Directions API. The route is then displayed on the map as a line.

## Usage

To use this project, follow these steps:

1. Obtain a Mapbox access token from [Mapbox](https://www.mapbox.com/). Replace `'YOUR_MAPBOX_ACCESS_TOKEN'` in the code with your actual access token.

2. Open `index.html` in a web browser.

3. Customize the map by providing latitude, longitude coordinates, and map style (optional) as query parameters in the URL. Example URL format: `index.html?lat1=40.7128&lng1=-74.0060&lat2=34.0522&lng2=-118.2437&mapType=streets`.

## Testing

You can test the functionality of the map by providing different sets of latitude and longitude coordinates in the URL. The map will display the route between the specified points. You can also switch between satellite and streets views using the `mapType` parameter.

## Example URL Parameters

- `lat1`: Latitude of the starting point.
- `lng1`: Longitude of the starting point.
- `lat2`: Latitude of the destination point.
- `lng2`: Longitude of the destination point.
- `mapType` (optional): Map style, either `satellite` or `streets` (default is `streets`).

### Example URLs

- Streets view: `index.html?lat1=40.7128&lng1=-74.0060&lat2=34.0522&lng2=-118.2437&mapType=streets`
- Satellite view: `index.html?lat1=40.7128&lng1=-74.0060&lat2=34.0522&lng2=-118.2437&mapType=satellite`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

