# BodyBloom

A personal body progress record with a Wildflower meadow theme. Log weight, body fat, measurements, progress photos and notes, view trends, and keep a weekly record you can compare side by side.

## Files

| File | Purpose |
| --- | --- |
| index.html | The whole app (layout, theme, logic) |
| manifest.json | Lets the phone install it as an app with its own icon |
| sw.js | Service worker, keeps the app working offline |
| icons/ | Home screen icons |
| vercel.json | Vercel hosting settings |

## Deploy

1. Push this folder to a GitHub repo named `bodybloom`.
2. In Vercel, choose Add New, Project, import `bodybloom`, Framework Preset: Other, then Deploy.
3. Open the live link on your phone and choose Add to Home Screen.

## Data

All records are stored in the phone browser (IndexedDB). Use Settings, Export backup regularly. Clearing browser data deletes the records.
