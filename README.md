# Massachusetts Population Map (1980) Visualization

## Overview

This project involves the creation of an interactive data visualization using D3.js to represent the population of Massachusetts by town in the year 1980. The map is divided into three sections, each providing different perspectives on the population data.

## Files

1. **index.html**: The main HTML file containing the structure of the webpage, including the necessary HTML, CSS, and JavaScript code.

2. **libs/d3.js**: The D3.js library for data visualization.

3. **libs/d3jstopojson.v1.js**: Additional library for working with TopoJSON data.

4. **data/towns.topojson**: TopoJSON file containing geographic information about Massachusetts towns.

5. **data/gini_index.csv**: CSV file containing the Gini index data per county.

## Features

### HTML Structure

- The HTML file includes the necessary metadata, title, and external script and style references.
- It defines a container with three sections for different visualizations, each accompanied by a title and a tooltip container.

### CSS Styling

- The CSS file includes styling for tooltips, paths, and the overall container layout.
- Hover effects on paths enhance user interaction and highlight the selected area.

### JavaScript (D3.js)

- The script dynamically loads TopoJSON and CSV data using Promises.
- Three separate functions (`generateMap`, `generateMapa`, and `generateMapb`) create different visualizations, each focusing on a specific aspect of the population data.
- Projections, scales, and color interpolations are used to create visually appealing and informative maps.
- Tooltips provide additional information when hovering over map elements.

## Usage

1. Clone the repository.
2. Open the `index.html` file in a web browser.

## Data Sources

- **Towns TopoJSON**: Geographic data for Massachusetts towns.
- **Gini Index CSV**: Gini index data per county.

## Libraries Used

- D3.js: A powerful JavaScript library for creating interactive data visualizations in the web browser.
- TopoJSON: An extension of GeoJSON that encodes topology. Used for efficient storage and rendering of geographic data.
