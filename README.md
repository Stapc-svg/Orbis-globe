# Orbis Globe

Orbis Globe is an interactive 3D Earth explorer for discovering places and seeing the planet from a new perspective. Search for a city, country, or landmark, then explore the globe and its location details with a suite of map and astronomy tools.

## Features

- Search for cities, countries, and landmarks, then fly to matching places.
- Explore an interactive globe with day and night lighting, geographic labels, and location markers.
- Open place details with photos and related information.
- Use the **Time machine** to choose a date and preview the Sun's position and local solar time.
- Measure distances and waypoints or draw a shape to estimate its area.
- Find your current location, show the latitude/longitude grid, discover a random destination, or find where it is noon.
- Check live space and sky data, including the International Space Station position and geomagnetic activity.
- Ask Orbis AI questions about places.
- Save a screenshot of the current view or switch to full-screen mode.

## Run the site

The site is a standalone HTML page and does not need a build step or package installation.

1. Keep `orbis-globe12.html` and `orbis-globe-brand.svg` in the same folder so the browser can load the Orbis tab icon.
2. Open `orbis-globe12.html` in a current desktop or mobile browser.
3. Connect to the internet for search, photos, AI responses, and live data.

If your browser restricts network requests from local files, start a simple local web server from this folder and open the address it prints. For example, with Python installed, run:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000/orbis-globe12.html>.

## Data and connectivity

Orbis Globe retrieves information from external services, including Photon for place search, Wikimedia for place media, NOAA for geomagnetic data, Where the ISS at? for ISS positions, and Pollinations for AI responses. These features depend on those services being available and on an internet connection.