# itch.io page draft: Dungeon Scrawlers

Create at https://itch.io/game/new (logged in as James). Paste fields below. Leave Visibility on **Draft** until the build is uploaded and tested.

## Fields
- **Title:** Dungeon Scrawlers
- **Project URL:** dungeon-scrawlers
- **Short description / tagline:** Forge guns, master movement, and out-dance souls-style bosses in a first-person roguelite.
- **Classification:** Games
- **Kind of project:** Downloadable
- **Release status:** In development
- **Pricing:** No payments (free), or "Name your own price" with $0 minimum
- **Uploads:** `DungeonScrawlers_Win64.zip`, tick **Windows**
- **Genre:** Action
- **Tags (10 max):** roguelite, first-person, fps, parkour, movement, souls-like, boss-battle, unreal-engine, low-poly, singleplayer
- **AI generation disclosure:** James to answer (itch asks whether the project contains generative AI content)
- **Inputs:** Keyboard, Mouse
- **Community:** Comments on
- **Cover image:** `cover-630x500.png` (this folder)
- **Screenshots:** `screenshot-hero.png`, `screenshot-forge.png`, `screenshot-enemy.png`, `screenshot-camp.png`
- **Trailer:** optional, YouTube link later

## Description (paste into the body)

**Dungeon Scrawlers** is a first-person roguelite where you play a blacksmith who forges guns, masters parkour, and takes on souls-style bosses, one procedurally drafted room at a time.

**Draft your run.** Every room offers three doors, weighted by rarity. Clear rooms to earn **HammerScale**, the run's currency and XP, then spend it on rarer rooms, weapon crafting, and ability upgrades.

**Movement is the win condition.** Unlock Jump, Bunny Hop, Slide, and Wall Run. Each unlock opens a Challenge Room that pays out a guaranteed signature weapon. Bosses that are brutal on foot become a dance for a movement master.

**The anvil is the gamble.** Health and ammo share one pool. Every visit to the anvil is a decision: survive longer or shoot more.

**Fight back from death.** Die and your unbanked HammerScale drops in the room where you fell. That room comes back into the draft. Scrawl your way back to it, or lose it all.

**Bosses**
- The Forgewarden: a corrupted master smith with hammer slams, molten arcs, and heated floor grids
- The Slag Colossus: a raid-style construct with AoE rings, homing spit, and a wall-run-only phase two
- The Ashen Reaper: a souls-style duelist with delayed combos, teleport strikes, and closing death walls

*Pre-alpha. Built in Unreal Engine 5.8 (Blueprint + GAS).*

**Controls:** WASD move, Mouse aim, LMB fire, Space jump, Shift/Ctrl slide (confirm against the build's input map before publishing)

**Requirements:** Windows 10/11 64-bit, DirectX 12 GPU. The build is unsigned, so SmartScreen may warn: More info, then Run anyway.

**Team:** James Sypherd, Ethan Becker

## Uploading the build (pick one)
- **Web upload:** Edit game, Upload files, select the zip, tick Windows. Default limit is 1 GB per file; request more from itch if the zip is bigger.
- **butler (from the desktop):** install butler (https://itch.io/docs/butler/), `butler login`, then
  `butler push DungeonScrawlers_Win64 bettercodegoblin/dungeon-scrawlers:windows --userversion 0.1`
  (replace `bettercodegoblin` with James's itch username). butler only re-uploads changed files on later versions.

## Before flipping to Public
- Build launches on a clean machine (no UE install)
- Controls line above matches the build
- Credits confirmed with Ethan
- Portfolio card links to both the itch page and the GitHub Release
