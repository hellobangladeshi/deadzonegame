# DEAD ZONE: ZOMBIE SURVIVAL

> SURVIVE THE OUTBREAK.

A browser-based 3D zombie survival game built with Three.js. Fully offline-capable, no install required.

## Features
- 🎮 10 story missions across 4 areas (City, Hospital, Military Base, Lab)
- 🧟 5 enemy types: Walker, Runner, Brute, Bloater, Alpha (boss)
- 🔫 8 weapons: Pistol, Revolver, Shotgun, AR, SMG, Sniper, Bat, Machete
- 💊 Health, stamina, medkits, loot drops
- 🗺️ Live minimap, boss health bar, headshot multipliers
- 💾 Local save (missions, settings, total kills)
- 📱 Mobile touch controls + desktop keyboard/mouse

## Play
1. Open `index.html` in any modern browser
2. Click **NEW GAME**
3. Or serve locally: `python -m http.server 8000` then visit `http://localhost:8000`

## Controls
| Action | Desktop | Mobile |
|--------|---------|--------|
| Move | WASD / Arrows | Left joystick |
| Look | Mouse | Right side drag |
| Fire | Left Click | FIRE button |
| Reload | R | RELOAD button |
| Swap weapon | Q or 1-8 | SWAP button |
| Heal | H | +MED button |
| Crouch | C | CROUCH button |
| Jump | Space | JUMP button |
| Flashlight | F | (in HUD) |
| Pause | Esc | ❚❚ button |

## Tech
- Three.js (via CDN)
- Pure HTML/CSS/JS — no build step
- localStorage for saves

## License
MIT — see LICENSE file.
