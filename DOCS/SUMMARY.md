<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# SUMMARY

## Project Status Update - 2026-08-21 (hub map expand)

- Added [`Block-Panel-V4`](https://github.com/Otterdays/Block-Panel-V4) +
  [live landing](https://otterdays.github.io/Block-Panel-V4/).
- Added [`High-Craft`](https://github.com/Otterdays/High-Craft) as the main friends
  server + [live site](https://otterdays.github.io/High-Craft/).
- Otter's Den now links the public site
  [otterdays.github.io/Otters-Den-Server](https://otterdays.github.io/Otters-Den-Server/).
- Panel lineage on hub: `V1` -> `V2` -> `V3` -> `V4`.

## Project Status Update - 2026-08-21

- Panel V1 naming corrected across the hub: the MC server / original panel repo is
  [`Block-Panel-V1`](https://github.com/Otterdays/Block-Panel-V1) (formerly listed
  as `MC-Server-repo`). Lineage is now
  `Block-Panel-V1` -> `Block-Panel-V2` -> `Block-Panel-V3`.
  [AMENDED 2026-08-21]: lineage extended to `Block-Panel-V4`.
- `README.md` and `index.html` link and copy updated to match.

## Project Status Update - 2026-05-13

- `README.md` now serves as a more thematic landing page for the repo hub.
- The public page now highlights the repo purpose, docs entry points, and the
  progression from `MC-Server-repo` to `Block-Panel-V2` to `Block-Panel-V3`.
  [AMENDED 2026-08-21]: V1 is `Block-Panel-V1`, not `MC-Server-repo`.
- A standalone root `index.html` now provides a visual landing website for the repo
    links without requiring any build step.
- Public-facing branding now presents the collection as `Otters MC Studios` while
  keeping `Minecraft-Stuffs` as the hub repo name.
- `README.md` now links directly to the live GitHub Pages site near the top for
  faster click-through.

## Project Status

- `Minecraft-Stuffs` is a lightweight umbrella repo for Minecraft-related projects,
  notes, and shared documentation.
- Current repo state: documentation-first. No package manifests or build scripts are
  present at the root at this time.
- Current pass: baseline `DOCS/` scaffolding plus README project-index cleanup.

## Quick Links

- Public index: `README.md`
- Status log: `DOCS/SCRATCHPAD.md`
- Dependency/security tracking: `DOCS/SBOM.md`
- Repo conventions: `DOCS/STYLE_GUIDE.md`
- Change history: `DOCS/CHANGELOG.md`
- Rationale log: `DOCS/My_Thoughts.md`
- Structure overview: `DOCS/ARCHITECTURE.md`

## Snapshot

- Root purpose: act as a hub for project links and high-level organization.
- Current categories in `README.md`:
  - Games and voxel projects
  - Server panels and hosting tools
  - Mods, plugins, and utility tools
- Newly indexed repos in the current README pass:
  - `Mc-Core-Mod`
  - `Minecraft-Civ-Remixed`
  - `advancement-fix`
  - `Block-Panel-V2`
  - `MC-Server-repo`
  - [AMENDED 2026-08-21]: `MC-Server-repo` entry replaced by `Block-Panel-V1`
  - [AMENDED 2026-08-21]: also `Block-Panel-V4`, `High-Craft`; Otter's Den live site wired

## Notes

- Treat linked repos as adjacent projects, not vendored dependencies of this repo.
- Keep `README.md` user-facing and keep deeper maintenance context in `DOCS/`.
