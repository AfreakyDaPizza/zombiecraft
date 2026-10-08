# ZombieCraft

First-person zombie survival with building. Stand your ground through escalating waves, gather wood and scrap, and build walls, ramps, turrets, and spikes between attacks.

**Play live:** https://afreakydapizza.github.io/zombiecraft/

## Controls

| Input | Action |
|---|---|
| WASD | Move |
| SPACE | Jump |
| SHIFT | Sprint |
| MOUSE | Look |
| CLICK | Shoot |
| RMB | Sniper scope |
| F | Skip next wave (when offered) — it doubles the one after |
| E/R | Reload |
| 1-7 | Weapons (Rifle, Shotgun, SMG, Sniper, Pistol, Minigun, Fling Thrower) |
| 8 | Hammer (upgrade structures) |
| 9 | Build mode |
| Q | Inventory |
| C | Crafting |
| T | Shop |
| B | Toggle build mode |
| F | Place structure |
| X | Switch build type |
| [ ] | Rotate structure |

## Maps

- **Town** — buildings, trees, streets
- **Arena** — open ring with central platforms
- **Ruins** — scattered walls and ruined towers

## Zombies

Walker, Runner, Crawler, Exploder, Spitter, Hound, Brute, Tank — plus specials:

- **Witch** — summons fresh undead around her
- **Driller** — burrows underground and bursts up with a surprise attack
- **Golem** — extremely tanky, slow, steady chip damage
- **Z-Hog Rider** — rider on a gore hog: very fast, fragile, hits hard
- **Corruption** — leaves a corruption puddle on death; zombies inside regen and shrug off 30% of damage
- **Slime** — splits into 2, then 4 smaller slimes before finally dying

Every 4th wave ends in a **Boss** — huge, armored, and horned.

## Fling Thrower

Gravity cannon (slot 7, buy at the Shop) — lobs an orb that hurls zombies sky-high; they take fall damage on the way down.

## Tech

Single-file game built on [three.js](https://threejs.org/) r126 (loaded from unpkg). Open `index.html` in a browser, or use the GitHub Pages link above.
