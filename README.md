# SJ88 RPG Idle 3D · Babylon.js

เกมส์ idle RPG 3 มิติ สร้างด้วย **Babylon.js** — Microsoft-backed 3D engine ที่สวยที่สุดในกลุ่ม "out of the box"

## 🥇 Why Babylon.js?

| | Babylon.js | Three.js | PlayCanvas |
|---|---|---|---|
| 🎨 PBR Material | ✅ Built-in | ❌ Need addon | ⚠️ Limited |
| 💡 Lighting | ✅ Built-in | ⚠️ Need setup | ⚠️ Limited |
| 🔧 Physics (Havok) | ✅ Built-in | ❌ Need library | ❌ External |
| 🛠️ Playground Editor | ✅ Yes | ⚠️ Manual | ✅ Yes |
| 📚 Microsoft Support | ✅ Yes | ❌ Community | ❌ Community |
| ⚡ Out of the box | ✅ Beautiful | ⚠️ Assembly | ⚠️ Limited |
| 💻 Code simplicity | ✅ Easy | ⚠️ Verbose | ⚠️ Medium |

## 🎮 Features

### Core
- 3D world with PBR materials (6 maps with unique themes)
- ArcRotateCamera (orbit + zoom + pan)
- Real-time shadows (BlurExponentialShadowMap)
- Skybox with dynamic gradient
- Fog (atmosphere)
- 6 แผนที่ × 15 มอน × 6 BOSS

### Gameplay
- 12 classes × 3 tiers (auto-calculated bonuses)
- 12 active skills (AOE, heal, buff, summon)
- 6 BOSS with unique icons + HP bar
- Combat: auto-attack, crit, damage numbers
- Daily login (7-day cycle)
- 12 Achievements
- localStorage save + offline progress
- Keyboard 1-4: cast skills
- WASD/arrows: move
- Mouse: orbit camera
- Scroll: zoom

### Tech Stack
- **Babylon.js** (CDN, 8MB core + 700KB GUI)
- PBR materials
- Havok physics-ready (camera uses ArcRotate)
- ShadowGenerator with blur
- Procedural geometry (no external assets)
- DynamicTexture for emoji billboards
- Zero npm dependencies

## 📂 File Structure

```
SJ88-RPG-Idle-3D/
├── index.html    # The entire game
└── README.md     # This file
```

## 🚀 Live URLs

| Channel | URL |
|---|---|
| 🌟 **Production** | https://sj88rpg.sj88ai.com (HTTPS · Let's Encrypt · auto-renew) |
| 📦 **CodeHub** | https://codehub.sj88ai.com/sj88-rpg-idle-3d/ |
| 🖥️ **Dev VPS** | http://178.83.121.75:53300/ |
| 📂 **GitHub** | https://github.com/lnwsj/SJ88-RPG-Idle-3D |

> 👉 **Use `sj88rpg.sj88ai.com` as your primary URL** — main production deployment with SSL.

## 🎯 How to Play

1. **WASD/Arrows** — move
2. **Mouse drag** — orbit camera
3. **Scroll** — zoom
4. **A** — toggle auto-attack
5. **1-4** — cast active skills
6. **Space** — manual attack
7. **Walk to portal** — warp to new map
8. **Walk to monster** — auto-engage
9. **Menu buttons** — class change, skills, map, daily bonus, achievements, settings

## 🛠 Babylon.js Playground

The game's 3D setup is similar to what you'd build in Babylon.js Playground:
- ArcRotateCamera
- HemisphericLight + DirectionalLight (sun)
- PBRMaterial with environmentTexture
- ShadowGenerator
- MeshBuilder primitives
- DynamicTexture for sprites

You can copy the scene setup to https://playground.babylonjs.com/ and continue developing there.

## 📜 License

MIT
