# Elevator Rush — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

One elevator, ten floors, zero patience. Call the car, pick up waiting riders
and drop them at their floors before patience runs out. Far trips and combos
score big. How many can you move in 90 seconds?

## Details

- Genre: Time Management / Arcade / Casual
- Controls: Mouse / Touch (tap a floor button to call the elevator). Keyboard: 1-9 and 0 map to floors 1-10, M toggles sound.
- Modes: Classic (90 seconds, floors 11-12 unlock mid-shift) and Challenge (deliver 20 riders, no timer, 12 floors from the start).
- Features: 4-rider car capacity with overload warning, patience bars, 3 hearts, combo scoring, best score / best time saving, mute toggle, procedural graphics (building cross-section, sliding doors, moving cable) and synthesized WebAudio sounds.
- Tech: Vanilla JavaScript, Canvas 2D, WebAudio. Single-file HTML5 (~36 KB), no external assets, no frameworks, no tracking, works offline once loaded.

## Tags
elevator, time-management, arcade, casual, simulation, rush-hour, single-file, highscore

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 and raw screenshot (capture from live build)

## GameDistribution
- Upload elevator-rush-gd.zip (contains index.html only; GD SDK auto-loads on
  gamedistribution / gd.games domains via the built-in domain guard)

## itch.io
- Upload zip (rename to elevator-rush.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480x720, kind: html
- Pricing: $0 (donations optional)
