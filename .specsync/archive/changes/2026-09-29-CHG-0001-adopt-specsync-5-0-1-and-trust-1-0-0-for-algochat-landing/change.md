---
id: CHG-0001-adopt-specsync-5-0-1-and-trust-1-0-0-for-algochat-landing
state: archived
type: migration
base_commit: e803348815901cde49a70aa278271e2a0479ec7b
---

# Adopt SpecSync 5.0.1 and Trust 1.0.0 for AlgoChat landing

## Intent

Adopt SpecSync 5.0.1 and Trust 1.0.0 for AlgoChat landing

## Affected Canonical Specs

- None

## Acceptance Criteria

- Static landing and README checks pass; agents and Trust doctor are healthy; UI, content, links, and publication remain unchanged.

## No-spec Rationale

Governance and CI only; landing-page behavior, content, links, and publication are unchanged.

## Migration Note

Migrated by hand to SpecSync 6 per Leif's decision (2026-09-28); the 6.0.0 tool refused to archive this legacy record (`` exact-only delivery input `.github/workflows/trust.yml` changed after acceptance and requires an audited reopen; run `specsync change reopen CHG-0001-adopt-specsync-5-0-1-and-trust-1-0-0-for-algochat-landing` to re-verify the accepted change, or supersede it from a later change under a module granted the path by `owns` in `.specsync/config.toml` ``).

- Workflow v1 (SpecSync 5) record, accepted on 2026-07-13 by the closing approval already stored in `approvals.json`. SpecSync 6.0.0 reports its accepted evidence as stale, for the reason quoted above.
- Moved by hand from `.specsync/changes/CHG-0001-adopt-specsync-5-0-1-and-trust-1-0-0-for-algochat-landing/` into the layout `specsync change archive` writes: `accepted-state.json` is the unchanged accepted `state.json`, `state.json` is marked `archived`, and this file's front matter says `archived`.
- `approvals.json`, `verification.json` and every other artifact are the original SpecSync 5 evidence, unchanged. `verification.json` verifies commit `152bea3c5cf2a5ea81de556d8764b8634d24944a`, not the tree this record was archived from.
- There is no `verification-attempts.json`: SpecSync 5 did not write one for this record, and this migration does not invent attempt history.
- This migration added no verification evidence, test result, attempt history, or approval. It is a manual migration, not a fresh re-verification.
- Closing it through the tool takes `specsync change reopen`, `specsync change verify`, then `specsync change accept`, which writes a new closing approval. Per Leif's decision it was archived by hand instead, so no reopen or new approval is recorded.
