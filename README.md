# College 3D Campus Map

Interactive 3D college campus map prototype built with Three.js.

## Current features

- Interactive 3D campus scene
- Orbit camera: rotate, zoom and pan
- Clickable campus buildings
- Building search
- Category filters
- Building information panel
- Focus-location camera action
- Responsive mobile layout
- Structured campus data in `campus-data.json`

## Roadmap

1. Replace demo coordinates with the real college site plan.
2. Add building floors and room-level locations.
3. Add start/destination navigation with a highlighted route.
4. Add a current-location marker.
5. Add real 3D building models where available.
6. Add college branding, logo and accessibility improvements.
7. Deploy the production version on Vercel.

## Run locally

This is a static web app. Open `index.html` through a local static server for the best browser behavior.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Data model

`campus-data.json` separates campus locations and room metadata from the visual model. Demo room records show how department, floor and room information will be represented when real campus data is added.
