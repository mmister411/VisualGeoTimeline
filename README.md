# VisualGeoTimeline
A web application that lets users add events to a timeline and display their locations on a map. It uses Leaflet for map rendering and the OpenStreetMap Nominatim API for geocoding. Users can delete events from the timeline and map.


# Timeline and Map

This project is a simple web application that allows users to add events to a timeline and display their corresponding locations on a map. The events are stored in an array and are dynamically added to the timeline and map when the user submits the event details through a form.

## Installation

To use this project, simply download the `index.html` file and open it in a web browser. The required dependencies, including Leaflet and its CSS file, are loaded from external sources, so an internet connection is required.

## Usage

1. Open the `index.html` file in a web browser.
2. Fill in the event details in the form fields: event name, event place, and event time.
3. Click the "Add Event" button to add the event to the timeline and map.
4. The event will be displayed in the timeline as a colored bar with the event name. It will also be marked on the map as a popup with the event name.
5. To delete an event, click the "Delete" button next to the event in the timeline. The event will be removed from both the timeline and the map.

## Features

- Adding events: Users can add events to the timeline and map by filling in the event details in a form and clicking the "Add Event" button.
- Deleting events: Users can delete events from the timeline and map by clicking the "Delete" button next to the event in the timeline.
- Geocoding: The application uses the OpenStreetMap Nominatim API to geocode the event place and retrieve its latitude and longitude coordinates for displaying on the map.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- Leaflet: [https://leafletjs.com/](https://leafletjs.com/)
- OpenStreetMap Nominatim: [https://nominatim.openstreetmap.org/](https://nominatim.openstreetmap.org/)
