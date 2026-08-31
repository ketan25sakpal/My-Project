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
- Structured campus data
- Campus route/pathfinding demonstration
- Floor and room exploration
- **Computer Science Department — 5th Floor interior demonstration**
- **5th Floor passage view** based on the uploaded reference video
- **CS Lab 2 interior view** with computer rows, monitors and red chairs

## 5th Floor CS Interior

Open `cs-floor5.html` through the same static server to explore:

- Computer Science Department 5th Floor passage
- Corridor windows and cabinets/storage
- Classroom doors and notice boards
- CS Lab 2
- Computer desks and monitors
- Red laboratory chairs
- Teaching desk and display board

The interior is a visual demonstration based on the uploaded reference video. Dimensions and room positions should be calibrated against the real floor plan before treating the model as an accurate building map.

## Roadmap

1. Replace demo campus coordinates with the real college site plan.
2. Replace demo 5th-floor geometry with calibrated measurements.
3. Add actual room numbers and department locations.
4. Connect campus navigation to building/floor/room navigation.
5. Add current-location marker.
6. Add real 3D building models where available.
7. Add college branding, logo and accessibility improvements.
8. Deploy the production version on Vercel.

## Run locally

This is a static web app. Open `index.html` through a local static server for the best browser behavior.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

For the 5th-floor interior demo, open `http://localhost:8000/cs-floor5.html`.
