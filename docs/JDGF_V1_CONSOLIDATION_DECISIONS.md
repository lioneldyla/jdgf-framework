# JDGF v1.0 Consolidation Decisions

**Status:** Adopted architectural decisions for the v1.0 candidate  
**Date:** 2026-07-28

## 1. Purpose

This record resolves structural divergences identified during reconciliation of parallel JDGF drafts. It is authoritative for the v1.0 candidate unless superseded through documented change control.

## 2. Decision 1 — Eight governance dimensions

JDGF v1.0 adopts eight dimensions:

1. Leadership and institutional governance;
2. Legal, ethical, and rights-based governance;
3. Data architecture and interoperability;
4. Data quality and metadata;
5. Security, privacy, and continuity;
6. Data lifecycle and records governance;
7. Use, statistics, transparency, and responsible innovation;
8. Artificial intelligence readiness.

The first seven dimensions preserve the evidence-oriented architecture developed in the repository. Artificial intelligence readiness is extracted as a distinct dimension because it is central to the JDGF theory of change and requires capabilities that extend beyond the governance of individual AI use cases.

AI readiness does not mean AI deployment. The dimension evaluates whether an institution can make justified, lawful, rights-respecting, evidence-based decisions to authorize, constrain, suspend, reject, or retire AI.

### Consolidation of the prior ten concepts

| Prior concept | Canonical treatment |
|---|---|
| Quality | Dimension 4 |
| Standardization | Dimensions 3 and 4 |
| Institutional governance | Dimension 1 |
| Accountability | Cross-dimensional requirement, especially Dimensions 1 and 2 |
| Security | Dimension 5 |
| Interoperability | Dimension 3 |
| Statistics | Dimension 7 |
| Strategic steering | Dimension 1 |
| AI readiness | Dimension 8 |
| Human-centred justice | Foundational and cross-dimensional principle, especially Dimensions 2 and 8 |

## 3. Decision 2 — Formative maturity model with scores 0–5

JDGF v1.0 adopts the repository's formative capability model:

- six score categories from 0 to 5;
- eight governance dimensions;
- six recurring capability attributes;
- evidence-based anchors;
- design and operating-effectiveness requirements;
- critical-control gates and score caps;
- confidence ratings;
- explicit limitations and uncertainty;
- empirical validation before any validated or certified claim.

Level 0 represents absence or lack of credible evidence. Institutional maturity claims normally use Levels 1–5 after applicability has been resolved.

A future lightweight assessment profile may be developed for small or resource-constrained institutions. It must remain traceable to the canonical model and preserve critical safeguards. It is not required for the v1.0 baseline.

## 4. Decision 3 — Documentary assessment instrument is in scope

The prior scope distinction is revised.

The Markdown or paper questionnaire that operationalizes the maturity model is part of JDGF v1.0 because the model cannot be applied reproducibly without a structured instrument.

The following remain outside scope:

- JDGAT as a software product;
- automated or hosted assessment platforms;
- automated evidence ingestion or scoring;
- certification software;
- algorithmic conformity decisions;
- commercial dashboards presented as an authorized JDGF product.

The documentary instrument remains pre-validation and must be revised through expert review, cognitive testing, institutional piloting, and inter-rater analysis.

## 5. Decision 4 — Canonical and supporting research artifacts

- `docs/02-framework/JDGF-Dimensions.md` is the canonical dimensions document.
- `docs/03-maturity-model/JDGF-Maturity-Model.md` is the canonical maturity model.
- `docs/04-assessment/JDGF-Assessment-Instrument.md` is the canonical documentary instrument.
- `research/JDGF-Validation-Plan.md` is the canonical validation roadmap.
- simulated cases are illustrative and cannot support empirical-validation claims.
- the standards mapping and bibliography must be linked by stable reference identifiers rather than maintained as conflicting duplicate bibliographies.

## 6. Decision 5 — Language policy

English is the canonical normative language of the public repository for the v1.0 candidate. French may be used for working discussions, explanatory syntheses, and controlled translations.

No translation may silently alter normative meaning. Until an official French translation is approved, the English version prevails in case of divergence. See `LANGUAGE_POLICY.md`.

## 7. Change-control consequence

Any future proposal to change the number of dimensions, maturity architecture, assessment scope, or canonical language must:

1. identify the affected documents;
2. explain the scientific and operational rationale;
3. assess backward compatibility;
4. update the change log;
5. undergo documented review before merge.