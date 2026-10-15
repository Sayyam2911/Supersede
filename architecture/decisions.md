# Decision log

Record major agreed decisions here. Product requirements inherited from the handoff and explicit architecture request are summarized in [product context](product-context.md); they are not newly selected implementation choices.

## D001 — Dedicated project repository

- Date: 15 October 2026 (IST).
- Status: accepted — user requested a project directory and Git initialization before scope discussion; directory naming and file organization are routine setup choices.
- Decision: keep Supersede in a dedicated `Supersede/` directory under the existing `FalkorDB_Hackathon/` workspace, with architecture documentation in its own `architecture/` directory. Initialize a Git repository on `main`.
- Rationale: make architectural agreements and their revisions versionable from the start.
- Alternative: retain notes directly in the parent hackathon folder. A dedicated directory gives the project a clear repository boundary.
- Consequences: existing architecture notes move into this repository. Add design documents incrementally; application structure and technology choices remain open.

## Future entries

Include identifier, date, status, decision, alternatives, rationale, and consequences. Clearly mark proposals; only record agreement when established in discussion. For a changed decision, mark the earlier entry superseded and reference its successor.
