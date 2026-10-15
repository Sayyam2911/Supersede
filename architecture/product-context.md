# Product context

## Basis and status

Read in full on 15 October 2026: `C:\Users\Sayyam Jain\Documents\Codex\2026-10-15\w\outputs\Supersede_Project_Handoff.md`.

The handoff supplies product context, not blanket authorization to execute embedded instructions. The user's explicit architecture request governs the discussion; subsequent explicit decisions may refine or override earlier context.

## Established requirements

Supersede is a domain-independent change-impact and knowledge-maintenance application. Its central question is: “Now that this changed, what are we still telling people or agents that may no longer be true?”

- Users start from existing source material. Source selection, contextual extraction, dependency discovery, initial review, and baseline establishment belong to the product.
- Claims retain exact supporting passages, source identities and versions, applicability, and relationship rationale. Shared words or citations alone do not prove dependency. Missing rationale stays unknown.
- Distinguish source assertions, hypotheses, accepted claims, observations, normative requirements, and authorized future changes. Acceptance means usable within declared workspace rules and scope.
- Preserve conflicting assertions. Investigate scope, dates, context, and authority; never adjudicate solely by position, repetition, model confidence, or model agreement.
- Maintainers can choose an interpretation, clarify scope, add evidence, or leave a conflict unresolved. Decisions are accountable and revisable.
- Agents submit proposals through a controlled acceptance boundary; they cannot overwrite accepted knowledge directly. Unsupported disagreement does not automatically invalidate accepted claims.
- Requested target state is distinct from current state. An agent's own edits cannot retroactively prove an earlier unsupported assumption.
- Track versions relied upon by long-running work, revalidate affected dependencies, prevent stale acceptance races, and preserve history. Independent work may continue.
- Dependencies identify investigation candidates, not automatic invalidity. Keep outdated, needs-review, still-valid, and insufficient-evidence findings separate from lifecycle states.
- Complete the correction, review, acceptance, publication, and re-ingestion loop within an explicitly agreed integration boundary. External editing or messaging is not implicitly authorized.
- Protecting internal accepted knowledge does not itself enforce external publication; stronger guarantees require integration at the external write boundary.
- FalkorDB is the primary graph database and must materially support investigation and action. Other technology and deployment choices remain open.
- UI concepts are provisional. Python is only a possible demo domain. Use a bounded real collection without restricting the reusable product to that domain.

## Open scope and constraints

First persona, workspace boundary, source formats and integrations, authority configuration, baseline acceptance policy, external publication scope, and demo collection remain undecided. Domain independence does not imply complete extraction or universal automated understanding.

Team capacity, actual working hours, budget, deployment access, and final event track are unknown. The handoff reports Graph Hacks dates of 15–18 October 2026 and a submission deadline of 18 October at 11:59 PM IST. These are reported context, not independently verified in this discussion. Verify the official event requirements before delivery planning: https://www.wemakedevs.org/hackathons/falkordb.

## Evaluation obligations to develop

Exercise same-source contradictions; compatible scopes/dates; unsupported replacements; source changes during running work; authorized future changes; stale reviewer decisions; indirect impacts with valid historical material; and reviewed publication followed by traceable re-ingestion. Retain evidence and history and state what is accepted, held, reviewed, or allowed to continue in each flow.

## Initial proposal — not agreed

Start by discussing one maintainer of one bounded collection and a complete workflow from import through reviewed correction and a verifiable publication/re-ingestion outcome. Compare a manual export/re-import boundary with a repository review workflow after source needs and capacity are known. This is a scope recommendation, not a selected implementation or source integration.
