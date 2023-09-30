# GalaxEye-AOI-Tile-Intersection

GalaxEye is a full-stack web application that allows users to define an Area of Interest (AOI) on a map and retrieve satellite image tiles that intersect with the selected AOI.

## Aim

The primary goal of this project is to create an entire full-stack website with docker compose where user can draw their AOI to see tiles which are intersecting with AOI.

## Technologies

- **Frontend:** Built with React, using react-leaflet for mapping functionality and leaflet-draw for drawing AOIs.
- **Backend:** Powered by Node.js.
- **Database:** MongoDB.
- **Docker Compose:** Used for containerization.

## Dataset

The dataset for this project contains 100 tiles that cover the entire state of Karnataka.

## Output

The application will display the satellite image tiles that intersect with the user-defined AOI. AOIs are represented in blue on the map, while intersecting tiles are marked in red.
