# Giant Ground Pangolin Observations

An interactive web application that displays recent iNaturalist sightings of the Giant Ground Pangolin (*Smutsia gigantea*) on an interactive map.

## Features

- Interactive map showing recent pangolin observations
- Markers with details: common name, scientific name, observation date, observer, and link to original observation
- Refresh button to load latest observations
- Clear markers button
- Responsive design for mobile and desktop
- Uses Leaflet for mapping and Esri World Imagery as basemap

## Data Source

Observations are fetched from the [iNaturalist API](https://www.inaturalist.org/) for the species *Smutsia gigantea*.

## How to Run

1. Open `code` in a web browser (requires internet connection for API and map tiles)
2. Or serve locally: `python3 -m http.server` and navigate to `http://localhost:8000/code`

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [Leaflet](https://leafletjs.com/) for mapping
- [iNaturalist API](https://api.inaturalist.org/v1/docs/)

## License

Data from iNaturalist is available under their terms of service.
