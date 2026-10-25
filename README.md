# MishFish - Fishing Forecast

A static fishing forecast page: weather, barometric pressure trend, wave and swell trends, sea currents (with a current map), moon phase, and a 7-day wave chart.

**Live:** https://mishkazk.github.io/MishFish-forecast/

## How it works

- Pick a spot by tapping the map, searching an address, using your browser location, or entering coordinates.
- Weather, pressure, marine and geocoding data come from [Open-Meteo](https://open-meteo.com/) (free for non-commercial use, CC BY 4.0) - no API keys.
- Moon phase is computed locally in the browser.
- Map by [Leaflet](https://leafletjs.com/) with [OpenStreetMap](https://www.openstreetmap.org/copyright) tiles.

Everything runs client-side in one `index.html`. No build step, no accounts, no keys, no tracking.

Note: near-coast current data is coarse model output - treat it as a guide, not precise at the beach.
