# Elevator Rush · 电梯调度

Free single-file HTML5 time-management game. One elevator, ten floors (twelve
in the late game), and a crowd of impatient riders — call the car, pick them
up, drop everyone at their floor before their patience runs out. One HTML
file, zero assets.

**Play:** https://shuangyueliao.github.io/elevator-rush/

## How to play

- Tap a floor button (or press keys 1-9, 0) to send the elevator
- It picks up waiting riders (max 4 in the car) and drops them at their
  destination floor for points — farther trips score more, consecutive
  deliveries build a combo
- A rider whose patience bar empties storms off and costs one heart (3 hearts)
- **Classic**: 90 seconds, floors 11-12 unlock as the rush builds
- **Challenge**: deliver 20 riders as fast as you can, no timer

## Features

- Mouse / touch / keyboard input, portrait-first responsive canvas
- Procedural graphics (building cross-section, sliding doors, cable, riders)
  and WebAudio synthesized sounds — no external assets at all
- Two modes, best score / best time saved locally, mute toggle
- Elevator state machine (idle / moving / door) with acceleration and
  braking; passengers with patience lifecycle (waiting / onboard / delivered /
  angry leave)
- Portal SDK loads only on crazygames / gamedistribution domains (gameplayStart
  / gameplayStop wired); standalone builds load nothing external

## Tech

Vanilla JavaScript, Canvas 2D, WebAudio. Single `index.html` (~36 KB),
no frameworks, no tracking, no external links. `store/` contains submission
materials (description, GameDistribution zip, itch.io zip).
