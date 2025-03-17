# Dev Summit Demos 2025

This is the source code for the demos presented at the session _Building Utility Network Applications with ArcGIS Maps SDK for JavaScript_ at Esri's Dev Summit 2025.

## Getting Started

1. Install the dependencies:

   ```sh
   npm install
   ```

2. Run the Vite dev server:

   ```sh
   npm run dev
   ```

3. Access the dev server by navigating to `http://localhost:5173/`.

## Configuration

Be sure to update the `id` property on the `arcgis-map` component in `index.html` with your own map ID:

```html
<arcgis-map item-id="YOUR_MAP_ID_HERE"> </arcgis-map>
```
