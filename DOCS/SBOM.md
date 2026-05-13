<!-- PRESERVATION RULE: Never delete or replace content. Append or annotate only. -->
# SBOM

## 2026-05-13 README Landing Page Pass

- Reviewed dependency state during the README redesign.
- No packages, runtimes, or bundled third-party assets were added or removed.

## 2026-05-13 Baseline Inventory

- Repo root currently appears documentation-only.
- No package manifests were found at the root during this pass, including:
  - `package.json`
  - `pyproject.toml`
  - `build.gradle`
  - `Cargo.toml`
  - `.csproj`
- No third-party packages were installed, removed, or updated during this pass.

## Scope Notes

- External GitHub repositories linked from `README.md` are project references only.
- Those linked repos are not counted as dependencies of this repository unless their
  source or artifacts are later vendored into this repo.

## Update Rule

- Add a new top entry whenever packages, runtimes, or bundled assets are introduced.
- If a prior statement becomes outdated, amend it with an
  `[AMENDED YYYY-MM-DD]:` note instead of deleting it.
