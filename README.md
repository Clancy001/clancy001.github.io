# Harsh Sharma · Portfolio

**Indie Game Developer · 3D Artist · Unity & Unreal Engine**  
📧 clancy0786@gmail.com · [LinkedIn](https://www.linkedin.com/in/harshsharmadev) · [GitHub](https://github.com/Clancy001)

---

## Overview

This is my personal portfolio — designed, written, and coded entirely by hand over several weeks. I wanted something that reflected the kind of work I actually do rather than pulling from a template, so every section, interaction, and piece of artwork was built from scratch.

The site is a single self-contained HTML file. No frameworks, no dependencies, no build process. I made that choice deliberately — it keeps things fast, portable, and straightforward to maintain.

One thing I'm particularly proud of is the Gameplay Demos section, where I built three browser games from the ground up using the Canvas API. They're not just decorative — each one demonstrates real systems I work with when developing in Unity and Unreal Engine.

---

## Sections

| Section | What's in it |
|---|---|
| Hero | Introduction, availability status, animated background |
| About | Background, journey into game development, skill bars |
| Games | Three shipped project cards with descriptions and engine details |
| 3D Art | Filterable bento gallery — Vehicle, Character, Environment, VFX |
| Skills | Eight disciplines with short descriptions |
| Gameplay Demos | Three playable browser games with mobile touch controls |
| Contact | Email, LinkedIn, GitHub |

---

## Gameplay Demos

The three games are fully playable in the browser and include proper mobile support.

**Void Shooter** — Top-down space shooter. Features wave progression, three enemy variants, boss encounters every four waves, and a power-up system (shield, rapid fire, bomb, extra life). Includes a combo multiplier and screen shake on hit. Keyboard and mobile D-pad supported.

**Dungeon Run** — Procedurally generated dungeon crawler. The maze is built fresh each run via recursive backtracking, so layouts never repeat. Guard AI uses field-of-view cones and an alert system. Fog of war reveals as you explore, with a live mini-map tracking guards and the exit.

**Neon Racer** — Lane-based driving game with traffic dodging, coin collection, nitro boost, and a combo system. Background cycles through a day-night sequence. Difficulty scales with speed over time.

All three save high scores locally and display them on the game tabs.

---

## Under the hood

Built with HTML5, CSS3, and vanilla JavaScript — no libraries or frameworks of any kind. The games run on the Canvas 2D API. The 3D artwork across the gallery is all hand-written SVG, which keeps the page lightweight with no image requests. Typography uses Syne and DM Sans via Google Fonts.

The 3D art cards use mouse-tracked CSS transforms to create a perspective tilt on hover — each card physically rotates toward the cursor position. That took longer than I'd like to admit.

Tested across Chrome, Firefox, Safari, Edge, Android and iOS.

---

## File structure

```
portfolio/
├── index.html    — complete website, single file
└── README.md     — this document
```

---

## License

Released under the [MIT License](https://opensource.org/licenses/MIT).

The code is open to read and learn from. The design, visual identity, written content, and artwork are my own work — please don't reproduce or redistribute them.

---

*Harsh Sharma, 2026*
