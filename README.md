# Washington State COVID-19 Case Rate Per 10k Map

This project is an interactive web map showing COVID-19 case rates across counties in Washington State. It uses Mapbox GL JS to create a choropleth map based on COVID-19 case data from October 25, 2021.

## Features

- Interactive map of Washington State
- Choropleth visualization of COVID-19 cases by county
- Hover functionality to display county-specific data
- Legend explaining the color-coding of case numbers

## Technologies Used

- HTML
- CSS
- JavaScript
- Mapbox GL JS (v2.5.0)

## How It Works

1. The map initializes centered on Washington State.
2. COVID-19 case data is fetched from the GeoJSON file.
3. Counties are color-coded based on the number of COVID-19 cases.
4. Hovering over a county displays its name and case count.
5. A legend explains the color coding of case numbers.

## Data Format

The GeoJSON file should contain the following properties for each feature:
- `name`: The name of the county
- `cases`: The number of COVID-19 cases in the county

## Note

This project uses a Mapbox access token. For extensive use or deployment, replace the access token with your own.