<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# SUMMARY

## Project Status Update - 2026-05-13

- `README.md` now serves as a more thematic landing page for the repo hub.
- The public page now highlights the repo purpose, docs entry points, and the
  progression from `MC-Server-repo` to `Block-Panel-V2` to `Block-Panel-V3`.
- A standalone root `index.html` now provides a visual landing website for the repo
  links without requiring any build step.

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

## Notes

- Treat linked repos as adjacent projects, not vendored dependencies of this repo.
- Keep `README.md` user-facing and keep deeper maintenance context in `DOCS/`.
