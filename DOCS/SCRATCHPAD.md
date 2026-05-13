<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# SCRATCHPAD

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
