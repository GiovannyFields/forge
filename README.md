# FORGE

A mobile-first workout app that builds you a complete training program from your goals, your equipment and your schedule, then tracks every lift as you get stronger.

Everything runs in the browser — no account, no server, no data leaves your phone (progress is saved in the browser's local storage). It also installs to your home screen and works offline.

## Features

- **Pick your focus** — Men, Women, or Well Rounded, which tilts where a little extra volume goes.
- **Choose your gear** — 25+ equipment options; a live counter shows how many exercises you unlock.
- **Auto-built split** — tell it how many days a week you train and it writes a professional program (balanced muscle coverage, no repeated sub-regions in a day, machines and free weights mixed).
- **Swap anything** — don't like an exercise? Pick another that hits the same muscle with your gear.
- **Animated form demos** — every exercise has a looping figure showing the movement, plus form cues and where you should feel it.
- **Track your lifts** — log weight and reps, get coaching on whether to go heavier or lighter, and watch line charts climb over time.
- **Rest timer** — starts automatically after you log a set, tuned to the lift.

## Run it

It's a single self-contained page. Open `index.html` in any browser, or visit the hosted site.

## Roadmap

- [ ] Publish to the Google Play Store (as a Trusted Web Activity / PWA wrapper)
- [ ] Program presets you can name and save
- [ ] Cross-week streaks

## Tech

Plain HTML, CSS and vanilla JavaScript in one file. Exercise figures are SVG + SMIL animations. Installable PWA (manifest + offline service worker). No build step, no dependencies.
