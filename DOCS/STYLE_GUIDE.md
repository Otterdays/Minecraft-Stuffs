<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# STYLE_GUIDE

## Repo Intent

- This repo is a lightweight umbrella for Minecraft-related project indexing,
  notes, and future shared assets.
- Prefer clear, practical documentation over polished-but-vague marketing copy.

## Markdown Conventions

- Use short sections and flat lists unless hierarchy is truly needed.
- Prefer tables for project catalogs and side-by-side comparisons.
- Keep project descriptions to one sentence when possible.
- Use forward slashes in paths, even on Windows-oriented documentation.

## Naming

- Markdown docs: `Title_Case.md` only when already established, otherwise keep
  names stable and readable.
- Debug files: `debug_[timestamp].md`

## Trace Tags

- If code is later added to this repo and needs doc traceability, use:
  `// [TRACE: filename.md]`

## Comment Rules

- Comments should explain intent or trade-offs, not restate obvious behavior.
- Use `TODO:`, `FIXME:`, and `NOTE:` prefixes consistently.

## DOCS Maintenance

- All files under `DOCS/` must keep the preservation header at the top.
- New updates go at the top of the relevant section where practical.
- Never delete historical notes; amend with `[AMENDED YYYY-MM-DD]:` instead.
