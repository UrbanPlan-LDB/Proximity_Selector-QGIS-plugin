# ProximitySelector Plugin for QGIS

## Description

ProximitySelector is a QGIS plugin that selects geometries based on their proximity. Users input a distance, and the plugin selects geometries with another geometry within that distance. It can apply the selection to all or only selected features.

## Installation

1. Download the plugin as a .zip file.
2. Open QGIS.
3. Go to `Plugins > Manage and Install Plugins... > Install from ZIP`.
4. Browse to the location of the downloaded .zip file and click `Install Plugin`.

## Usage

1. Open QGIS and load your layer.
2. Go to `Plugins > ProximitySelector`.
3. In the `ProximitySelector` dialog, select your input layer from the `Input layer` dropdown.
4. Input your desired buffer distance in the `Buffer distance (meters)` field.
5. Check the `Apply only to selected features` box if you want to apply the selection only to currently selected features.
6. Click `Run`.
7. The plugin will create a new layer with the selected geometries.

## License

This project is licensed under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.
