# Supersede

A domain-independent change-impact and knowledge-maintenance application.

> Now that this changed, what are we still telling people or agents that may no longer be true?

Supersede builds evidence-linked knowledge from existing sources and investigates downstream impact when those sources change. Agents propose corrections; controlled review and acceptance protect accepted knowledge.

## Project status

Architecture discussion started on 15 October 2026. Application implementation has not begun. FalkorDB is required as the primary graph database; other technology choices and MVP scope remain open.

Start with the [architecture index](architecture/README.md).

## Repository structure

```text
Supersede/
├── README.md
├── .gitignore
└── architecture/
    ├── README.md             # Design status, index, and next discussion
    ├── product-context.md    # Established requirements and open scope
    └── decisions.md          # Agreed decisions and their rationale
```

Add requirements, design, model, flow, evaluation, and implementation-plan documents as those areas are discussed. Application directories will follow agreed implementation boundaries.

## Documentation workflow

Discuss one decision area at a time. Keep proposals separate from agreements. Record major agreements and update the affected documents before committing. When a decision changes, preserve the previous rationale and link its replacement.

Do not commit credentials or private source collections. Decide source storage and demo-data handling during architecture design.
