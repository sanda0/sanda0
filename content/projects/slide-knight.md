---
sitemap:
  priority: 0.7
title: "Slide Knight"
tags_display: "godot · gdscript · go · android · admob"
weight: 3
image: "images/projects/slide-knight.png"
logo: "images/projects/logos/slide-knight.png"
blurb: "Pixel-art sliding puzzle game for Android. Swipe, slide until you hit a wall, reach the stairs in as few moves as you can."
video: "videos/slide-knight-trailer.mp4"
video_poster: "images/projects/slide-knight/trailer-poster.png"
links:
  - label: "google play: coming soon"
gallery_portrait: true
gallery:
  - src: "images/projects/slide-knight/screenshot-1.png"
    alt: "Swipe. Slide. Stop at the wall."
  - src: "images/projects/slide-knight/screenshot-2.png"
    alt: "Grab keys, push crates, ride the rails"
  - src: "images/projects/slide-knight/screenshot-3.png"
    alt: "Reach the stairs in par for 3 stars"
  - src: "images/projects/slide-knight/screenshot-4.png"
    alt: "Dodge spiders, or slay them with a sword"
  - src: "images/projects/slide-knight/screenshot-5.png"
    alt: "Sneak past the statue beams"
  - src: "images/projects/slide-knight/screenshot-6.png"
    alt: "100 puzzles in 10 dungeons"
---

A puzzle game for Android built on one rule: when you swipe, the knight slides until something stops him. Plan your route through 100 small dungeon rooms, reach the stairs, and match the par move count for 3 stars. Free, with optional ads and a one-time "Remove Ads" purchase.

## Ten dungeons

Each chapter adds one idea and then mixes it with the ones before: coins and stairs, keys and doors, crates to push, spikes and chests, mine carts on rails, patrolling spiders, swords that kill a spider on touch, ghost potions that let you pass through one wall, statue beams with pressure plates, and a final Grand Temple that uses everything.

## Highlights

- Pure rules core: `board.gd` takes a state and a swipe and returns the new state plus a list of events; scenes only animate those events
- A Go mirror of the rules with a BFS solver and a seeded level generator; every level's par and solution come from the solver, never by hand
- Parity tests run the same move sequences through Go and GDScript, so the two rule sets can't drift apart
- Juice through one autoload: squash and stretch, afterimages, dust, hit stop, screen shake and haptics
- Pixel-perfect portrait layout that fills any phone screen and keeps buttons out of notches and gesture bars
- Rewarded hints and undos with AdMob (consent flow included), interstitials capped and never before level 10, Remove Ads through Play Billing
- Store screenshots and devlog videos recorded from the real game with Godot's Movie Maker

[Privacy policy](/apps/slide-knight/privacypolicy/)
