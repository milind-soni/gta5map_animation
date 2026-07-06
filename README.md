# GTA 5 Map Switch

A web recreation of the GTA V character-switch camera transition, cycling through
real-world locations on a Mapbox satellite map.

Faithful to the game's sequence: three slow zoom-out punches with pulsating holds
between levels, a hazy high-altitude pan with clouds sweeping past, three punch-ins
onto the target, and the full color journey — olive-khaki monochrome over the source,
blown-out parchment bloom on the ascent, cool grey cloud haze at cruise, teal/cream
cross-process on the descent, snapping back to color at street level. All sound
effects are synthesized live with Web Audio (whooshes, bass thumps, heartbeat pulse,
altitude wind).

## Run

It's a single static `index.html` — open it in a browser, or deploy the folder
as-is to Vercel/Netlify. Click the splash to start (unlocks audio).

## Controls

| Input | Action |
|---|---|
| `Space` | switch to the next location |
| `1`–`9` | jump to a specific location |
| `H` | hide/show the panel |
| panel input | geocode and add any place |
| Auto | keep cycling automatically |
| Street/Sky zoom + Speed sliders | tune the camera levels and pacing (persisted) |
