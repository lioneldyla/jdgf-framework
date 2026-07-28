# JDGF Repository Audit and v1.0 Readiness Plan

Audit date: 2026-07-28

## Executive finding

The repository began as a minimal public project containing two substantive root documents: `README.md` and `CLAUDE.md`. No substantive duplicate framework documents were detected. The principal gap was not duplication but the absence of an authoritative documentation architecture, research separation, contribution rules, version history, assessment guidance, and explicit v1.0 validation criteria.

## Initial inventory

| Element | Initial state | Audit finding | Action |
|---|---|---|---|
| `README.md` | Present | Useful public overview, but mixed project summary, framework structure, maturity model, and research positioning | Harmonize as repository gateway |
| `CLAUDE.md` | Present | Strong project instructions and scope controls | Retain and align with repository structure |
| `CHANGELOG.md` | Missing | No formal revision record | Created |
| `CONTRIBUTING.md` | Missing | No contribution or review rules | Created |
| `docs/` | Missing | No authoritative framework documentation space | Created |
| `research/` | Missing | Framework and research work were not structurally separated | Created |
| `templates/` | Missing | No controlled location for instruments | Created |
| `diagrams/` | Missing | No visual-document governance | Created |
| License | Not confirmed | Legal reuse terms remain unresolved | Decision required before v1.0 |
| Empirical validation | Not documented | No validated case study or pilot in the repository | Required before v1.0 |
| Bibliography | Not documented | Reference families named, but no validated bibliography | Required before v1.0 |

## Duplicate review

No substantive duplicate files were identified in the initial repository. The restructuring therefore avoids destructive deletion. Future duplication is controlled through:

- one authoritative glossary;
- one documentation map;
- dimension-level source-of-truth rules;
- research/framework separation;
- change and contribution controls.

## Restructuring applied

```text
jdgf-framework/
├── README.md
├── CLAUDE.md
├── AUDIT.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── docs/
│   ├── README.md
│   ├── 01-foundations/
│   ├── 02-framework/
│   ├── 03-maturity-model/
│   ├── 04-assessment/
│   ├── 05-implementation/
│   ├── 06-case-studies/
│   ├── 07-glossary/
│   └── 08-references/
├── research/
├── templates/
└── diagrams/
```

## Harmonization decisions

- JDGF is defined consistently as a scientific, methodological, and operational governance framework, not software.
- Responsible AI is positioned as a readiness and governance concern built on institutional and data-governance foundations.
- The original nine-topic README structure is replaced by a coherent authoritative documentation architecture.
- The maturity level previously called “Governed Intelligence” is replaced by “Adaptive” to avoid equating maturity with AI adoption.
- Claims requiring evidence are marked as draft, proposed, or requiring validation.
- The African judicial focus is retained without claiming that one national context represents the continent.

## JDGF v1.0 entry criteria

A v1.0 release should not be declared until the following are complete:

- [ ] foundations reviewed and approved;
- [ ] dimensions and sub-dimensions stabilized;
- [ ] authoritative glossary completed;
- [ ] actors, responsibilities, processes, controls, and indicators defined;
- [ ] maturity criteria defined for every dimension and level;
- [ ] assessment instruments and scoring method tested;
- [ ] implementation roadmap reviewed by practitioners;
- [ ] systematic or structured literature review completed;
- [ ] bibliography and standards mapping completed;
- [ ] at least one authorized pilot or case study documented;
- [ ] limitations and contextual adaptation guidance documented;
- [ ] confidentiality and publication safeguards validated;
- [ ] reuse license selected;
- [ ] independent scientific and institutional review completed;
- [ ] release notes and versioned publication package prepared.

## Priority next actions

1. Validate the proposed ten dimensions through literature and expert review.
2. Build the dimension-control-indicator matrix.
3. Define maturity criteria and evidence thresholds.
4. Produce the first assessment toolkit templates.
5. Complete the standards and literature mapping.
6. Select and govern an empirical pilot.
7. Resolve licensing and release governance.

## Residual risks

- premature presentation of draft components as validated standards;
- excessive scope expansion into technology products or general AI governance;
- unsupported claims of international alignment;
- inadequate handling of confidential judicial evidence;
- maturity scoring that creates false precision;
- insufficient participation by judicial practitioners and affected stakeholders.
