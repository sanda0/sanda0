---
title: "Blocky Blasters: Zombie Siege"
tags_display: "godot · gdscript · android · admob"
weight: 2
image: "images/projects/blocky-blasters.png"
featured: true
door: "games"
logo: "images/projects/logos/blocky-blasters.png"
blurb: "Blocky first-person shooter meets tower defense on Android. Build towers, survive the night."
gallery:
  - src: "images/projects/blocky-blasters/screenshot-1.jpg"
    alt: "Village Defense: build towers"
  - src: "images/projects/blocky-blasters/screenshot-2.jpg"
    alt: "Your towers fight beside you"
  - src: "images/projects/blocky-blasters/screenshot-3.jpg"
    alt: "Night is coming: get ready"
  - src: "images/projects/blocky-blasters/screenshot-4.jpg"
    alt: "Survival: a boss every 5 waves"
  - src: "images/projects/blocky-blasters/screenshot-5.jpg"
    alt: "Chain kills for big scores"
  - src: "images/projects/blocky-blasters/screenshot-6.jpg"
    alt: "Endless waves in the graveyard"
  - src: "images/projects/blocky-blasters/screenshot-7.jpg"
    alt: "Two ways to play"
links:
  - label: "google play"
    url: "https://play.google.com/store/apps/details?id=com.thepixelforge.blockyblasters"
---

First-person shooter with tower defense for Android. Build and upgrade towers, guard the village houses and survive 10 nights against a blocky horde, or hold a foggy graveyard against endless waves of zombies, ghosts, robots and bosses. Plays offline, free with optional ads, no in-app purchases.

## Game modes

- **Village Defense**: spend the day building Turret, Cannon, Ballista and Catapult towers on 10 spots along the roads, upgrade them to level 3 and repair them, then hold the night until dawn. Every house still standing earns souls and points. Survive 10 nights to save the village.
- **Survival**: endless waves in a foggy graveyard, with zombie runners, phasing ghosts, robots that shoot back, Orc Brutes and a boss every 5 waves. Upgrade between waves and chain headshots and kill combos for a high score.

## Highlights

- Fixed 60 Hz deterministic simulation, separated from rendering, with seeded randomness; towers, houses and the day/night cycle all run inside the sim, built so multiplayer can come later
- Custom capsule-vs-AABB player collision instead of the engine's built-in movement
- Data-driven maps and tuning, validated by a map checker and 600+ gdUnit4 tests
- Touch controls with aim assist, auto-fire and a fully movable/resizable button layout
- 50 achievements; each one unlocked adds souls to the start of every run
- Phone-friendly graphics on Godot's Compatibility renderer: night fog, shader grass, electric robot shots with a screen shock effect, and vibration feedback; steady 60 fps with 30 enemies on a Pixel 9a
- Optional rewarded ads (revive, repair houses at dawn) with AdMob and a consent flow

[Privacy policy](/apps/blocky-blasters/privacypolicy/) · [Terms of service](/apps/blocky-blasters/terms/)
