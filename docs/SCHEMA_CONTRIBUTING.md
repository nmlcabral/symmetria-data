# Contributing to Schemas

## When changing a schema
1) **Version bump** the filename, e.g., `prices_schema_v0.2.md`.
2) **Update docs** in the schema table and assumptions.
3) **Update samples** so they still match and remain <100 KB each.
4) **Changelog**: add a short note to `docs/DATA_POLICY.md` under “Changelog”.
5) **Open a PR** labeled `type:docs` and `area:data`, describing:
   - What changed and why
   - Impact on downstream tools
   - Any migration notes

## Naming
- Files: `snake_case` + `_vMAJOR.MINOR` (e.g., `prices_schema_v0.2.md`)
- Samples match schema version when fields change.

## Review
- CODEOWNERS will be requested automatically.
- Approvals required before merging to `main`.