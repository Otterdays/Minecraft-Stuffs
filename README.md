# Otters MC Studios

![Repo role](https://img.shields.io/badge/repo-hub-1f6feb?style=for-the-badge)
![Theme](https://img.shields.io/badge/focus-minecraft-2ea043?style=for-the-badge)
![Content](https://img.shields.io/badge/content-mods%20%7C%20panels%20%7C%20tools-8957e5?style=for-the-badge)
![Docs](https://img.shields.io/badge/docs-active-f59e0b?style=for-the-badge)

> Minecraft mods, server panels, tools, and voxel side projects under one studio
> banner.

`Minecraft-Stuffs` is the hub repo for **Otters MC Studios**. Most projects live in
their own repositories; this page is the map that ties the collection together.

**GitHub:** https://github.com/Otterdays/Minecraft-Stuffs
  
**Web:** [otterdays.github.io/Minecraft-Stuffs](https://otterdays.github.io/Minecraft-Stuffs/)

## Studio Brand

- Brand: `Otters MC Studios`
- Hub/repo: `Minecraft-Stuffs`
- Focus: Minecraft mods, server tools, utilities, and voxel experiments

## Start Here

- Landing page: `index.html`
- Project snapshot: `DOCS/SUMMARY.md`
- Working log: `DOCS/SCRATCHPAD.md`
- Dependency tracking: `DOCS/SBOM.md`
- Repo conventions: `DOCS/STYLE_GUIDE.md`

## What Lives Here

- Fabric mods and supporting libraries
- Minecraft server panels across multiple generations
- Utility tools for creators, server owners, and experiments
- Small voxel and game side projects

## Project Map

### Games & voxel

- [**A Voxel Christmas**](https://github.com/Otterdays/GAME-A-Voxel-Christmas)  
  Voxel-inspired winter scene with procedural terrain, particles, post-processing,
  and an optional Windows shell using **Three.js** plus **.NET / WebView2**. Play
  the alpha at
  [otterdays.github.io/GAME-A-Voxel-Christmas](https://otterdays.github.io/GAME-A-Voxel-Christmas/).

### Server panels & hosting

Panel lineage:
`Block-Panel-V1` -> `Block-Panel-V2` -> `Block-Panel-V3` -> `Block-Panel-V4`

- [**Block-Panel-V1**](https://github.com/Otterdays/Block-Panel-V1)  
  Browser-based Minecraft dedicated server dashboard (MC-26.1 / Fabric) with
  server and mod management plus an AI assistant. Formerly tracked as
  `MC-Server-repo`; this is the original Block Panel line.
- [**Block-Panel-V2**](https://github.com/Otterdays/Block-Panel-V2)  
  Native **Windows** desktop app for managing Minecraft servers with
  **Tauri v2**, **Rust**, **React**, and **TypeScript**.
- [**BlockPanel-V2-Public**](https://github.com/Otterdays/Block-Panel-V2-Public)  
  Public-facing portable Windows release repo and landing site for the V2 line.
- [**Block-Panel-V3**](https://github.com/Otterdays/Block-Panel-V3)  
  Self-hosted Minecraft control plane for Java and Bedrock servers using
  **Elixir / Phoenix LiveView** and **PostgreSQL**.
- [**Block-Panel-V4**](https://github.com/Otterdays/Block-Panel-V4) ·
  [Live](https://otterdays.github.io/Block-Panel-V4/)  
  Native **Windows** Minecraft Server Control Center — PowerShell + WPF,
  live console, properties, Modrinth queue. Double-click `launch.bat`.
- [**High-Craft**](https://github.com/Otterdays/High-Craft) ·
  [Live](https://otterdays.github.io/High-Craft/)  
  Main friends survival world and public landing for the crew series
  (Java 26.3 · Fabulously Optimized). Towns, kingdoms, infrastructure, lore.
- [**Otters-Den-Server**](https://github.com/Otterdays/Otters-Den-Server) ·
  [Live](https://otterdays.github.io/Otters-Den-Server/)  
  Whitelist-only Fabric survival den (Java 26.1) — community site with
  rules, stack, and join info.

### Mods, plugins & tools

- [**Mc-Core-Mod**](https://github.com/Otterdays/Mc-Core-Mod)  
  Fabric core library plus optional core mod/API jar for shared services, event
  hooks, ready-state dispatch, and update checks.
- [**Minecraft-Civ-Remixed**](https://github.com/Otterdays/Minecraft-Civ-Remixed)  
  Fabric civ/economy add-on with wallet commands, onboarding messages, jobs, and
  optional mining or combat payouts.
- [**advancement-fix**](https://github.com/Otterdays/advancement-fix)  
  Client-side Fabric mod that enlarges the vanilla Advancements screen without
  replacing advancement data.
- [**McOtterShaders**](https://github.com/Otterdays/McOtterShaders)  
  Shader pack work for OptiFine and Iris, with GLSL plus repo-side docs.
- [**MC-Helpy-Helper**](https://github.com/Otterdays/MC-Helpy-Helper)  
  Fabric mod that turns `/help` into a searchable command browser.
- [**Feeshman Deelux**](https://github.com/Otterdays/Feeshman-Deelux)  
  Fabric `1.20.1` mod focused on auto-fishing, HUD features, stats, and
  achievements.
- [**ChipperChopper**](https://github.com/Otterdays/ChipperChopper)  
  Fabric `1.20.1` project for autonomous AI tree harvesting with monitoring HUD.
- [**Minecraft-Fabric-Sample-Mod**](https://github.com/Otterdays/Minecraft-Fabric-Sample-Mod)  
  Barebones Fabric template for starting a new mod quickly.
- [**MC-Texture-Maker**](https://github.com/Otterdays/MC-Texture-Maker)  
  Python texture and skin editor with `CustomTkinter` and 3D preview tooling.
- [**MC-Companion-Map**](https://github.com/Otterdays/MC-Companion-Map)  
  Fabric `1.20.1` mod with a local HTTP API plus an Android overhead map
  companion over LAN.
- [**PaperMC-Plugins**](https://github.com/Otterdays/PaperMC-Plugins)  
  Minimal Paper plugin scaffold using Gradle Kotlin and the modern Paper line.

## Notes

- This repo is a curated index, not a monorepo.
- Linked repositories are adjacent projects, not root dependencies of this repo.
- Deeper maintenance context lives in `DOCS/`.
