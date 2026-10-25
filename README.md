# Omkar's Quest

My product design portfolio ([omkarkhandalkar.online](https://omkarkhandalkar.online/)) turned into two browser games. Both tell the same story: education, work experience, case studies, photography, content, community work, and how to contact me.

Each game is a single self-contained HTML file. There's no build step and nothing to install.

## The games

### V2 · Hill Climb (`hill-climb/`)

A physics driving game in a Mumbai auto-rickshaw, with me in the driver's seat.

- 9 stages with their own scenery, from the Mumbai skyline to a neon arcade and a beach with a lighthouse
- 36 floating cards to drive through. Each one pops a short note, and the full details live in the **Collection**
- Fuel cans, coins, jump ramps, flips, and crashes that send you back to the stage checkpoint
- An engine sound that follows your speed, a horn, and chiptune music that changes at night
- A day/night cycle with headlights, lit windows and street lamps
- **Just show me the portfolio** on the start screen unlocks every card without playing

| Action | Keyboard | Phone |
|---|---|---|
| Gas | → or D | GAS pedal |
| Brake / reverse | ← or A | BRAKE pedal |
| Tilt in the air | gas tilts back, brake dips the nose | same |
| Honk | H or Space | HONK |
| Back to checkpoint | R | — |
| Collection | C | COLLECTION button |

### V1 · 8-bit Platformer (`8bit-platformer/`)

A classic side-scrolling platformer with a pixel-art version of me.

- 9 stages: home, skills, academy, career road, project arcade, photo gallery, studio, community, inbox
- Read signs, doors and arcade machines; bonk **?** blocks to reveal skills
- Climb the Zeus Learning tower to reach the promotion door
- Stomp "legacy bugs", collect coins, and warp between stages from the world map
- 8-bit sound effects, music, and a day/night cycle

| Action | Keyboard | Phone |
|---|---|---|
| Walk | ← → or A / D | ◀ ▶ |
| Jump | Space, ↑ or W | A |
| Read / interact | E or Enter | B |
| Map | M | MAP |

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

To host it for free, turn on **GitHub Pages** for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## Built with

Plain HTML, CSS and JavaScript on a `<canvas>`, with Web Audio for all sound. Fonts come from Google Fonts (Press Start 2P, VT323, Pixelify Sans). Built with Claude.
