# SG Nearby Bus Stops

A modern web application that displays nearby bus stops in Singapore on an interactive map, built with vanilla JavaScript and Leaflet.

## Demo

https://yapweijun1996.github.io/Nearby-Bus-Stop-v2/

## Preview

<img width="1437" height="794" alt="Preview" src="og_img.jpg" />

## Features

-   **Locate Me**: Automatically detects and displays your current location on the map.
-   **Location Search**: Search for any location in Singapore using the integrated search functionality.
-   **Adjustable Radius**: Customize the search radius (100m to 2000m) to find bus stops within your preferred distance.
-   **Bus Stop Details**: Click on bus stop markers to view the bus stop code, description, and a direct link to check real-time bus arrival times.
-   **Fullscreen Mode**: Immersive fullscreen viewing for better map exploration.
-   **Mobile Responsive**: Optimized for mobile devices with touch-friendly controls and responsive design.
-   **Modern UI**: Clean, modern interface with custom-styled popups, zoom controls, and smooth animations.
-   **URL Sharing**: Share specific locations via URL parameters (e.g., `?lat=1.283&lon=103.860`).

## Technologies

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Mapping**: [Leaflet](https://leafletjs.com/) - Open-source JavaScript library for interactive maps
- **Geocoding**: [Nominatim API](https://nominatim.org/) - Free geocoding service by OpenStreetMap
- **Data**: Local JSON file containing Singapore bus stop information

## Data Source

Bus stop data is sourced from `bus_stop_list_sg.json`, which contains information about bus stops across Singapore including:
- Bus stop codes
- Descriptions
- Geographic coordinates (latitude and longitude)

## Installation & Usage

### Running Locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Grant location permissions when prompted to see nearby bus stops.
4. Use the search bar to find specific locations.
5. Adjust the radius slider to control the search distance.
6. Click on bus stop markers for detailed information.

### URL Parameters

You can share specific locations by appending coordinates to the URL:
```
https://yapweijun1996.github.io/Nearby-Bus-Stop-v2/?lat=1.283&lon=103.860
```

## Privacy & Permissions

This application requires geolocation permissions to:
- Automatically center the map on your current location
- Display nearby bus stops based on your position

Location data is processed locally in your browser and is not stored or transmitted to external servers.

## Business Use

This application is suitable for personal and non-commercial use. For business or high-traffic applications, please be aware that it relies on the free [Nominatim API](https://nominatim.org/release-docs/latest/api/Search/) for location searching, which has a strict [usage policy](https://operations.osmfoundation.org/policies/nominatim/). High-volume usage may require a commercial plan or a self-hosted instance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
