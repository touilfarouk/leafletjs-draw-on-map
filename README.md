README
Site SIG Map

This project is a web-based map application built using Leaflet, a popular JavaScript library for interactive maps. It allows users to view various map layers and features, draw shapes, measure distances, and export drawn data as GeoJSON.
Features

    Map Layers: Users can switch between different base map layers, including Google Street Map, Stamen, CyclOSM, OpenTopoMap, and more.
    Markers: Customizable markers with pop-up information.
    Controls: Includes controls for zooming, measuring distances, drawing shapes, and exporting drawn data.
    Minimap: Provides a minimap for an overview of the entire map.
    Bookmarks: Allows users to bookmark specific locations on the map.
    Scale: Displays a scale bar for estimating distances on the map.

Usage

    Accessing the Map: Open the index.html file in a web browser to access the map.

    Navigation:
        Use the mouse to pan and zoom the map.
        Use the zoom controls provided on the map interface.

    Drawing Shapes:
        Click on the drawing icon in the control panel to activate drawing mode.
        Choose the desired shape (point, line, polygon) from the drawing options.
        Click on the map to start drawing the selected shape.
        Finish drawing by clicking on the starting point or using the control panel.

    Measuring Distances:
        Click on the ruler icon in the control panel to activate measuring mode.
        Click on the map to start measuring distances.
        Double-click to finish measuring.

    Exporting Drawn Data:
        Click on the "Télécharger les données de dessin (GeoJSON)" link to export drawn data as a GeoJSON file.

    Bookmarks:
        Use the bookmarks control to save and access favorite locations on the map.

File Structure

    index.html: Main HTML file containing the map interface and JavaScript dependencies.
    css/: Directory containing CSS files for styling the map interface.
    js/: Directory containing JavaScript files for Leaflet plugins and custom scripts.

Technologies Used

    Leaflet: JavaScript library for interactive maps.
    jQuery: JavaScript library for DOM manipulation and AJAX.
    GeoJSON: Format for encoding various geographic data structures.

Notes

    This project is intended for demonstration purposes and may require further customization and optimization for specific use cases.
    Ensure proper attribution and usage rights for map layers and data sources used in the application.
    Additional features and improvements can be implemented based on specific requirements and feedback from users.
