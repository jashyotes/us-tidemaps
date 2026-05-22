# US Tidemaps

Standalone Pebble app showing NOAA tide predictions for a user-configured station. Designed for the Pebble Time 2 (emery).

48-hour hourly window centered on "now" (24 past, 24 future). UP / DOWN scroll the rendered window by one hour. SELECT toggles between 24h and 48h views. BACK exits.

## Build

```
npm install
pebble build
pebble install --emulator emery
```

## Configuration

Set a NOAA tide station ID via the Pebble app's settings page. Find your station's 7-digit ID at https://tidesandcurrents.noaa.gov/.

## Visual consistency with JY Time

This app is a sibling project to the JY Time watchface (https://github.com/jashyotes/simple-pixel-style). Visual changes to fonts, icons, or layout patterns should be mirrored across both projects where applicable so they read as the same family in a Pebble menu.

## License

Private.
