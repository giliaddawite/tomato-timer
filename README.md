# Tomato Timer

A simple Pomodoro timer that runs in the browser. One HTML file, plain CSS and vanilla JavaScript, no build step and no dependencies.

## What it does

- Big countdown (starts at 25:00) inside a dial with one tick per minute
- Start / Pause / Resume and Reset buttons
- Set your own length from 1 to 99 minutes with the Length field
- Plays a short chime when time runs out (made with the Web Audio API, so there are no sound files)
- Keeps track of how many sessions you finished today
- Light and dark mode follow your system setting

## Running it

Just open `index.html` in a browser. That's it.

The fonts (DM Mono and Bricolage Grotesque) load from Google Fonts. If you're offline it falls back to your system fonts and still works fine.

## Shortcuts

- `Space` starts or pauses
- `R` resets

## Notes

- Browsers block sound until you've clicked something on the page, so the chime is unlocked when you press Start.
- The timer checks the real clock instead of counting seconds, so it stays accurate even if the tab sits in the background.
- Your last chosen length, the daily session count, and the sound setting are saved in your browser's local storage.
