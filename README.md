# Omkario

My product design portfolio ([oskorp.github.io](https://oskorp.github.io/)) as an 8-bit side-scrolling platformer, starring a pixel-art version of me.

**Play:** https://oskorp.github.io/omkario/

Prefer driving? Try the hill-climb version: [Sahyadri Climbing](https://oskorp.github.io/sahyadriclimbing/).

## What's in it

- 9 stages: home, skills, academy, career road, project arcade, photo gallery, studio, community, inbox
- Read signs, doors and arcade machines; bonk **?** blocks to reveal skills
- Climb the Zeus Learning tower to reach the promotion door
- Stomp "legacy bugs", collect coins, and warp between stages from the world map
- 8-bit sound effects, music, and a day/night cycle

## Controls

| Action | Keyboard | Phone |
|---|---|---|
| Walk | ← → or A / D | ◀ ▶ |
| Jump | Space, ↑ or W | A |
| Read / interact | E or Enter | B |
| Map | M | MAP |

## Run it locally

The whole game is one self-contained `index.html`. Open it in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Built with

Plain HTML, CSS and JavaScript on a `<canvas>`, with Web Audio for all sound. Fonts from Google Fonts (Press Start 2P, VT323). Built with Claude.
