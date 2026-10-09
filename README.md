# ZombieCraft

First-person zombie survival with building. Stand your ground through escalating waves, gather wood and scrap, and build walls, ramps, turrets, spikes, heal pads, and buff towers between attacks.

**Play live:** https://afreakydapizza.github.io/zombiecraft/

## Controls

| Input | Action |
|---|---|
| WASD | Move |
| SPACE | Jump |
| SHIFT | Sprint |
| MOUSE | Look |
| CLICK | Shoot (LMB = left mech arm) |
| RMB | Sniper scope / right mech arm |
| SCROLL | Cycle weapons |
| F | Skip next wave (when offered) — it doubles the one after |
| R/E | Reload |
| 1-9 / 0 | Hotbar (weapons, Hammer at 8, Build mode at 9) |
| B / Q | Inventory |
| T | Shop |
| V | Summon ghosts (Reaper) |
| X | Switch build type |
| [ ] | Rotate structure |
| ENTER | Restart after death |

## Lobby / Progression

Pick a **Map** (click or press 1-5 to jump straight in), spend **💠 z-coins** earned each run on weapon upgrades (damage +25%, mag +15% per level, up to LV 4), and unlock **Classes**:

- **Brawler** (500💠) — 👊 Fists of Doom melee, zombies drop +65% wood
- **Gunsmith** (850💠) — start with pistol + shotgun and +500 ammo, but -10% HP
- **Tanker** (1000💠) — +50 HP and a free minigun, but -25% move speed
- **Drone Man** (1000💠) — a combat drone buzzes in every 20 kills (max 3)
- **Repair Man** (1000💠) — can build HEAL PADS (heal while standing on them) and BUFF TOWERS (+50% turret damage and -50% structure damage taken nearby)
- **Reaper** (1500💠) — scythe melee that harvests souls from kills; press **V** with 3 souls to summon ghost allies
- **Mech Pilot** (2000💠) — pilot a 5000-HP mech suit with dual fling cannons (LMB/RMB), +20% speed; when it's destroyed it drops +50 wood and +10 scrap

## Maps

- **Town** — buildings, trees, streets
- **Arena** — open ring with central platforms
- **Ruins** — scattered walls and ruined towers
- **Z-CHURCH** — a barricaded gothic church survivor base: stone courtyard, stained glass, sandbag walls, glowing altar and an eerie mist ring
- **Construction** — tower crane, scaffolding towers, concrete foundations, freight containers, bulldozer and a gravel yard

## Weapons

Rifle, Shotgun, SMG, Sniper, Pistol, Minigun, Fling Thrower, Railgun, and Uzi (inventory-only).

- **Fling Thrower** — lobs an orb that hurls zombies sky-high; they take fall damage on the way down
- **Railgun** — a heavy piercing beam that plows through up to 12 zombies in a line

## Zombies

Walker, Runner, Crawler, Exploder, Spitter, Hound, Brute, Tank — plus specials:

- **Witch** — summons fresh undead around her
- **Driller** — burrows underground and bursts up with a surprise attack
- **Golem** — extremely tanky, slow, steady chip damage
- **Z-Hog Rider** — rider on a gore hog: very fast, fragile, hits hard
- **Corruption** — leaves a corruption puddle on death; zombies inside regen and shrug off 30% of damage
- **Slime** — splits into 2, then 4 smaller slimes before finally dying

Every 4th wave ends in a **Boss** — huge, armored, and horned, with eight personalities (Colossus, Gargant, Mounted Golem, Totem Thrower, Spooky Witch, Hog Swarm, Electrozombie, Bomber Doom).

## Tech

Single-file game built on [three.js](https://threejs.org/) r126 (loaded from unpkg). Open `index.html` in a browser, or use the GitHub Pages link above. Progress (z-coins, upgrades, classes) is saved in `localStorage`.