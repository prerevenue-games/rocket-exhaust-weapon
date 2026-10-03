# Rocket Exhaust Weapon

An Asteroids-style shooter where your guns are dead and the only weapon left is your engine's exhaust. Firing at enemies pushes you away from them, so the skill is in drifting to keep the burn on target.

The whole game is one file, `index.html`: plain JavaScript and the browser's canvas, with sound synthesized live. Nothing to install or build.

## Controls

| Action | Keys |
|---|---|
| Rotate | ← → / A D |
| Burn | ↑ / W |
| Tight / wide plume | Shift or F |
| RCS strafe | Q E |
| RCS retro | ↓ / S |
| Handbrake (auto RCS all-stop) | Space |
| Dump fuel | X |
| Pause | P / Esc |
| Mute | M |

Touch screens get on-screen buttons.

## Tuning

Every gameplay number is in the `TUNE` block at the top of the script in `index.html`.

## Publishing

- **GitHub Pages** serves `index.html` from the repo root (Settings → Pages → Deploy from a branch → `main`, `/ (root)`).
- **itch.io** gets a new build automatically when `index.html` changes on `main`, via `.github/workflows/itch.yml`. Setup steps are at the top of that file.
