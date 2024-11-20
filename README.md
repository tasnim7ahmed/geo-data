# CesiumJS Web Applications

Welcome to the **CesiumJS Web Applications** repository! This collection showcases a variety of interactive web applications built using [CesiumJS](https://cesium.com/platform/cesiumjs/). Whether you're looking to measure distances, manipulate terrain and imagery layers, control the camera, or work with GeoJSON data, you'll find practical examples here to help you get started with CesiumJS.

## Table of Contents

- [Features](#features)
  - [1. Distance Measurement Tool](#1-distance-measurement-tool)
  - [2. Terrain and Imagery Layers](#2-terrain-and-imagery-layers)
  - [3. Camera Control](#3-camera-control)
  - [4. Styling Entities with GeoJSON](#4-styling-entities-with-geojson)
  - [5. Load GeoJSON Data](#5-load-geojson-data)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Examples](#running-the-examples)
- [Customization](#customization)
- [License](#license)
- [Contact](#contact)

## Features

### 1. Distance Measurement Tool

Measure distances on the Cesium globe with an intuitive user interface.

- **Features:**
  - Click to place two points on the globe.
  - Visualize the distance with a line and label.
  - Interactive measurement mode with cursor changes.

- **File:** `distance-measurement.html`

### 2. Terrain and Imagery Layers

Manipulate terrain exaggeration and imagery layers to customize the globe's appearance.

- **Features:**
  - Exaggerate terrain by a specified factor.
  - Change the base imagery to OpenStreetMap.
  - Add overlay layers from WMS services with transparency settings.

- **File:** `terrain-imagery-layers.html`

### 3. Camera Control

Control the camera with zoom, fly-to locations, and track entities.

- **Features:**
  - Zoom in and out with buttons.
  - Fly to a predefined location with specified orientation.
  - Track an entity, making the camera follow it.

- **File:** `camera-control.html`

### 4. Styling Entities with GeoJSON

Load and style GeoJSON data dynamically on the globe.

- **Features:**
  - Load GeoJSON files.
  - Style point entities based on properties (e.g., magnitude).
  - Customize colors, sizes, and outlines.

- **File:** `styling-entities.html`

### 5. Load GeoJSON Data

Simple example to load and visualize GeoJSON data on the Cesium globe.

- **Features:**
  - Load GeoJSON files.
  - Visualize data points and geometries.
  - Zoom to the loaded data for better visibility.

- **File:** `load-geojson.html`

## Getting Started

Follow these instructions to set up and run the examples on your local machine.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A local web server (optional but recommended for loading local GeoJSON files).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/cesiumjs-web-apps.git
   cd cesiumjs-web-apps
   ```

2. **Install a Local Web Server (if needed):**

   You can use [http-server](https://www.npmjs.com/package/http-server) or any other web server.

   ```bash
   npm install -g http-server
   ```

### Running the Examples

1. **Start the Web Server:**

   ```bash
   http-server
   ```

   By default, it serves at `http://localhost:8080`.

2. **Open the Desired Example:**

   - **Distance Measurement Tool:** [http://localhost:8080/distance-measurement.html](http://localhost:8080/distance-measurement.html)
   - **Terrain and Imagery Layers:** [http://localhost:8080/terrain-imagery-layers.html](http://localhost:8080/terrain-imagery-layers.html)
   - **Camera Control:** [http://localhost:8080/camera-control.html](http://localhost:8080/camera-control.html)
   - **Styling Entities with GeoJSON:** [http://localhost:8080/styling-entities.html](http://localhost:8080/styling-entities.html)
   - **Load GeoJSON Data:** [http://localhost:8080/load-geojson.html](http://localhost:8080/load-geojson.html)

   > **Note:** Ensure that the `data` folder containing `BGD.geo.json` is correctly placed relative to the HTML files for GeoJSON examples to work.

## Customization

Each example includes comments and code that can be modified to suit your needs. Feel free to explore and enhance the functionalities:

- **Cesium Ion Access Token:**

  Replace the default access token with your own Cesium Ion token for better quota and access to private assets.

  ```javascript
  Cesium.Ion.defaultAccessToken = 'YOUR_CESIUM_ION_ACCESS_TOKEN';
  ```

- **GeoJSON Data:**

  Update the GeoJSON file paths or use your own datasets.

- **Styling and UI:**

  Modify CSS styles or add new UI elements to improve the user experience.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions, suggestions, or contributions, please open an issue or contact [tasnimahmed@iut-dhaka.edu](mailto:tasnimahmed@iut-dhaka.edu).

---

Happy Mapping! 🚀