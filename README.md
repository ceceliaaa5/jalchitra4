# JalChitra – Wetland Mapping & Seasonal Monitoring (NESFIC-D-14)
Single-file prototype, no build step or dependencies.

## Run
- Open `index.html` in any modern browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.
- Internet is only needed for the Google Font; the app works without it.

## What is real vs simulated
- Real: UI, season switching, per-wetland dashboard, table, layer toggles.
- Simulated: all wetland areas, canals, fishery data (sample values); schematic map. No satellite data, ML model or backend is connected.

## Edit data
Wetland records are in the `W` array in the `<script>`; season factors are in `SEASONS`.

## Documents
See `docs/` for the solution proposal PDF, proof-of-work PDF and the proposal planning spreadsheet.
