<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# SCRATCHPAD

## Active Task - 2026-08-21 Hub map: Den site, High-Craft, V4

- Goal: wire live sites + new main server + Block Panel V4 into the hub map.
- Status: completed.
- Outcome: `README.md` and `index.html` now include:
  - Otter's Den live: https://otterdays.github.io/Otters-Den-Server/
  - High-Craft (main friends server) + live: https://otterdays.github.io/High-Craft/
  - Block-Panel-V4 + live: https://otterdays.github.io/Block-Panel-V4/
  - Lineage extended through V4.

## Last 5 Actions

1. Added Otters Den live-site click-through on README + landing cards.
2. Indexed High-Craft as main friends SMP with GitHub + Pages links.
3. Indexed Block-Panel-V4 with GitHub + Pages landing.
4. Extended panel lineage to V4 on public surfaces.
5. Updated SUMMARY / CHANGELOG / SCRATCHPAD (append-only).

## Next Steps (from list check)

- Optional: related but unlisted MC repos — `My-Minecraft-Server`,
  `Mc-Server-Architecture-Fabric-Bedrock-Java`.

## Out-of-Scope Observations

- [AMENDED 2026-08-21]: `Block-Panel-V4` and `High-Craft` are now on the hub map.

## Active Task - 2026-08-21 Block-Panel-V1 rename on hub

- Goal: fix the hub project list so the MC server / original panel points at
  `Block-Panel-V1`, not `MC-Server-repo`.
- Status: completed.
- Outcome: `README.md`, `index.html`, `DOCS/SUMMARY.md`, and `DOCS/CHANGELOG.md`
  updated. Confirmed GitHub: `MC-Server-repo` resolves to
  https://github.com/Otterdays/Block-Panel-V1 (v1.4.8, Fabric + Python helper).

## Active Task - 2026-05-13 README Web Link

- Goal: add the live landing page URL near the top of `README.md`.
- Status: completed.
- Outcome: `README.md` now exposes the GitHub Pages link prominently for fast access.

## Last 5 Actions

1. Re-read `DOCS/SUMMARY.md`, `DOCS/SBOM.md`, `DOCS/SCRATCHPAD.md`, and
   `DOCS/STYLE_GUIDE.md`.
2. Re-read the top section of `README.md`.
3. Added the live site URL directly under the GitHub repo link.
4. Started the doc checkpoint for the README link pass.
5. Updated status docs for the change.

## Active Task - 2026-05-13 Branding Pass

- Goal: brand the public landing materials as `Otters MC Studios`.
- Status: completed.
- Outcome: public-facing copy now leads with `Otters MC Studios` while preserving
  `Minecraft-Stuffs` as the repo/hub identifier.

## Last 5 Actions

1. Re-read the current `index.html`, `README.md`, `DOCS/SCRATCHPAD.md`,
   `DOCS/SUMMARY.md`, and `DOCS/CHANGELOG.md`.
2. Confirmed the site currently uses `Minecraft Stuffs` as the visible public brand.
3. Chose a light rebrand approach: keep the repo identity, upgrade the public-facing
   brand.
4. Targeted the public surfaces first: `index.html` and `README.md`.
5. Applied the brand pass and updated the status docs.

## Active Task - 2026-05-13 Root HTML Landing Page

- Goal: add a real root landing website for the repo links.
- Status: completed.
- Outcome: added a single-file `index.html` landing page with a dark themed layout,
  grouped project cards, and direct repo links.

## Last 5 Actions

1. Re-read `DOCS/SUMMARY.md`, `DOCS/SBOM.md`, `DOCS/SCRATCHPAD.md`, and
   `DOCS/STYLE_GUIDE.md` before starting the HTML pass.
2. Listed the repo root to confirm no existing `index.html` or site assets.
3. Re-read the themed `README.md` to mirror its public structure.
4. Chose a single-file static landing page approach to keep the repo simple.
5. Added `index.html` and linked it from `README.md`.

## Active Task - 2026-05-13 README Landing Page Pass

- Goal: turn `README.md` into a stronger thematic landing page for the repo hub.
- Status: completed.
- Outcome: `README.md` now reads like a front door instead of a plain project list,
  with a stronger intro, clearer navigation, and an explicit server-panel lineage.

## Last 5 Actions

1. Read `DOCS/SUMMARY.md`, `DOCS/SBOM.md`, `DOCS/SCRATCHPAD.md`, and
   `DOCS/STYLE_GUIDE.md` before editing.
2. Re-read the current `README.md` to confirm the current public structure.
3. Confirmed the repo still acts as an index/meta repo rather than a codebase.
4. Identified a truncated `MC-Server-repo` description in `README.md` that should be
   corrected during the redesign.
5. Rewrote `README.md` into a themed landing page and corrected the V1 panel entry.

## Active Task - 2026-05-13

- Goal: bring the repo closer to the documented workflow with a simple docs baseline.
- Status: completed initial `DOCS/` scaffold and aligned the root `README.md` with
  additional project links supplied during this session.

## Blockers

- None at the moment.

## Last 5 Actions

1. Checked the current root layout and confirmed the repo only had `README.md`.
2. Reviewed the current `README.md` project index.
3. Added missing project entries for recent linked Minecraft repos.
4. Created the `DOCS/` directory and `DOCS/debugs/`.
5. Seeded baseline docs for status, SBOM, conventions, changelog, and architecture.

## Next Steps

- Keep `README.md` as the public-facing index.
- When code, scripts, or package manifests land in this repo, update `DOCS/SBOM.md`
  immediately.
- Log future debugging work as `DOCS/debugs/debug_[timestamp].md`.

## Out-of-Scope Observations

- This repo is currently more of an index/meta repo than a codebase.
- If it grows into shared tooling, the docs should be expanded with ownership,
  release process, and packaging details.
