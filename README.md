# Ravenbrook Manor: The Clocktower Curse

A web and VR horror game from **PenGame Publishing, LLC**, set in the town from *Halloween Haunts: A Spooky Coloring Adventure* by Darnell Clark.

**Play:** https://mrimagemakers.github.io/RavenbrookManor/

- Eight boards, from the cemetery gates to the clocktower, with bosses on boards 2, 5 and 8
- Keyboard and mouse, touch screens, Xbox and PlayStation controllers, and Meta Quest (WebXR)
- ULTRA graphics mode, a built-in How to Play guide (press **H**), and adjustable safety settings for flashing lights, jump scares and blood

For players 18 and over. See the in-game "Content, privacy and credits" section for the full content notice.

## Hosting

The site is a static page served by GitHub Pages from the `main` branch. Everything it needs ships in this repository:

| Path | What it is |
|---|---|
| `index.html` | The game |
| `lib/` | three.js r128 and the loaders and effects it uses (MIT License, see `lib/LICENSE-three.js.txt`) |
| `npc/` | Character models |
| `tex/`, `guide/` | Optional photographic textures and guide illustrations; the game runs without them |

Multiplayer parties need the version hosted on Claude; on GitHub Pages the game runs solo.

## Rights

© 2026 PenGame Publishing, LLC. *Halloween Haunts: A Spooky Coloring Adventure* © Darnell Clark. All rights reserved. The source is visible here so the game can be hosted; it is not licensed for reuse. three.js is © the three.js authors under the MIT License.
