# StrumLoop

A free browser-based practice tool for building and looping guitar strumming patterns.

## Current MVP features

- 8th-note and 16th-note strumming grids
- 1-bar and editable 2-bar phrases
- Down-strum / up-strum direction labels
- Built-in metronome with BPM slider, number input, tap tempo, and count-in
- Practice ramp with configurable BPM increase and bar interval
- Separate metronome and strum playback toggles
- Separate metronome and strum volume controls
- Up/down sound toggles for both metronome and strum playback
- Pattern tools: randomize, clear, fill, and presets
- Shareable links for exact patterns and settings
- `localStorage` persistence for the last-used pattern and settings
- Mobile-friendly responsive layout

## Project structure

- `index.html`: app markup
- `styles.css`: layout and visual styling
- `app.js`: rendering, audio playback, interactions, and persistence

## Running locally

Because this is a static app, you can open `index.html` directly in a browser or serve the folder with any simple static server.

Examples:

```bash
python3 -m http.server 8000
```

or

```bash
npx serve .
```

Then open `http://localhost:8000` or the URL printed by your server.
