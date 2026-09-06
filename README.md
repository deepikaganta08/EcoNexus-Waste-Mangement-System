# EcoNexus — SIH Prototype

## Run
This version is a static multi-page prototype. Open `index.html` with a local server in VS Code (recommended: Live Server extension) or run:

python -m http.server 5500

Then open http://localhost:5500

## Real GPS
Disposal and Sanitization use `navigator.geolocation.getCurrentPosition()` with `enableHighAccuracy: true`.
The browser will request location permission. No fake coordinates are inserted by the app.

## Important
AI classification, reports, admin workflow and impact values are prototype/demo functionality. Real municipal integrations and production AI require backend/API integration.
