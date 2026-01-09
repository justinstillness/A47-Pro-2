# A47-PRO-2

Concept repository system for the Agenda 47 Explained content project.

## Repository Structure

```
A47-Pro-2/
├── Archive/      → Superseded versions
├── Guides/       → Governing documentation
├── ICR/          → Interim Concept Repositories (staging)
├── Index/        → Navigation and lookup files
├── Volumes/      → Master concept repositories by domain
└── README.md
```

## Folders

| Folder | Purpose |
|--------|---------|
| **Volumes/** | Master concept repositories organized by domain (CIV-SYS, CTRL-MECH, LIB-MECH, EPIST, THEO, HIST, GEOPOL, PSYCH, STRAT-OPS, META) |
| **ICR/** | Staging area for work-in-progress concept repositories before merge into Volumes |
| **Index/** | Navigation files for looking up concepts across volumes |
| **Guides/** | Governing documentation (Concept Repository Guide, Editorial Guide, Style Guide) |
| **Archive/** | Superseded versions of artifacts, retained for reference |

## File Naming Convention

```
A47-PRO-2_[TYPE]_[DESCRIPTOR]_v[VERSION].txt
```

**Types:** VOL, ICR, Index, Guide, Card, Outline, Draft

**Examples:**
- `A47-PRO-2_VOL_CIV-SYS_v1.txt` — CIV-SYS domain volume
- `A47-PRO-2_ICR_S03-Extraction_v1.txt` — Interim repository from source S03
- `A47-PRO-2_Guide_Concept-Repository_v1.2.txt` — Concept Repository Guide

## Fetching Files

Raw file URL pattern:
```
https://raw.githubusercontent.com/justinstillness/A47-Pro-2/refs/heads/main/[FOLDER]/[FILENAME]
```

## Current Artifacts

| File | Location | Description |
|------|----------|-------------|
| Concept Repository Guide v1.2 | Guides/ | Governing document for concept extraction and repository management |
| Master Volume v252 | Volumes/ | Combined concept repository (252 concepts) |
| Master Index v252 | Index/ | Lookup index for all concepts |

## Domains

The concept repository system organizes concepts into ten domains:

| Code | Domain |
|------|--------|
| CIV-SYS | Civilizational Systems |
| CTRL-MECH | Control Mechanisms |
| LIB-MECH | Liberation Mechanisms |
| EPIST | Epistemology |
| THEO | Theology/Worldview |
| HIST | Historical |
| GEOPOL | Geopolitical |
| PSYCH | Psychological |
| STRAT-OPS | Strategic Operations |
| META | Meta/Process |

---

*Last updated: January 9, 2026*
