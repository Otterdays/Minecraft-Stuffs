<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# ARCHITECTURE

## Overview

`Minecraft-Stuffs` currently acts as an umbrella/index repo rather than a compiled
application or library. Its main job is to organize links, notes, and project-level
documentation around adjacent Minecraft work.

## Structure

- `README.md`: public-facing project catalog
- `DOCS/`: internal status, conventions, rationale, and maintenance notes
- `DOCS/debugs/`: timestamped issue logs when debugging work happens

## Diagram

```mermaid
flowchart TD
    A[Minecraft-Stuffs repo] --> B[README.md]
    A --> C[DOCS/]
    B --> D[Games and voxel links]
    B --> E[Server panels and hosting links]
    B --> F[Mods, plugins, and tools links]
    C --> G[SUMMARY / SBOM / SCRATCHPAD]
    C --> H[STYLE_GUIDE / CHANGELOG / My_Thoughts]
    C --> I[debugs/]
```

## Current Boundary

- Linked repositories remain independent projects.
- This repo should not duplicate their source code unless there is a clear need for
  shared assets or cross-project documentation.
