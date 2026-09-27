# Hometown Range

A first-person target range in any real place. Type a town, a street or a landmark, and the buildings and streets within about 400 m load from OpenStreetMap and are built in 3D in your browser. Clear the 10 targets hidden in the streets.

**Play:** https://stefanz92.github.io/hometown-range/

## How it works

- **Place search:** OpenStreetMap Nominatim, with Photon as a fallback.
- **Map data:** buildings, streets, water and parks from the Overpass API, downloaded live for each place.
- **3D:** building outlines are extruded to their mapped height, or an estimate from the building type. Windows are drawn per floor in a shader, and small homes get gable roofs.
- **Rendering:** plain WebGL, no libraries. Everything is in `index.html`.

## Controls

| | Computer | Phone |
|---|---|---|
| Walk | W A S D, Shift to run | Left thumb |
| Look | Mouse | Drag with right thumb |
| Shoot | Click (hold for rapid fire) | FIRE button |
| Pause | Esc | Menu |

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the ODbL.
