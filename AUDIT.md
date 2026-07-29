# JDGF Repository Audit and v1.0 Readiness Plan

**Audit date:** 2026-07-29  
**Audited branch:** `agent/prepare-jdgf-v1`  
**Scope:** repository structure, 41 files changed in draft PR #1, framework coherence, maturity model, assessment instrument, case studies, research protocols, references, language governance, contribution controls, and release readiness.

## 1. Executive conclusion

The repository now contains a coherent candidate architecture for JDGF v1.0. The eight-dimension framework, formative maturity model, documentary assessment instrument, controlled validation workflow, and fictional Kadonia case are mutually aligned at a high level.

The repository is suitable for structured expert review and cognitive testing. It is not yet suitable for a stable or empirically validated v1.0 release.

The audit identified four classes of residual issue:

1. **validation debt:** expert review, cognitive testing, institutional piloting, and reliability testing remain unexecuted;
2. **reference debt:** clause-level standards mapping and bibliographic verification remain incomplete;
3. **instrument ambiguity:** the scoring treatment of formally applicable national requirements that are not implemented locally requires explicit clarification;
4. **repository-governance debt:** licensing and final release governance remain unresolved.

No claim of empirical validation is supported by the repository at this stage.

## 2. Repository integrity

### 2.1 Authoritative structure

```text
jdgf-framework/
├── README.md
├── AUDIT.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── docs/
│   ├── README.md
│   ├── JDGF_V1_CONSOLIDATION_DECISIONS.md
│   ├── JDGF_V1_SCOPE_EXCLUSIONS.md
│   ├── LANGUAGE_POLICY.md
│   ├── 01-foundations/
│   ├── 02-framework/
│   ├── 03-maturity-model/
│   ├── 04-assessment/
│   ├── 05-implementation/
│   ├── 06-case-studies/
│   ├── 07-glossary/
│   └── 08-references/
├── research/
│   └── review/
├── templates/
└── diagrams/
```

The separation between normative framework documentation, research materials, templates, and diagrams is appropriate. No substantive duplicate framework was identified in the audited branch.

### 2.2 Canonical language

English is consistently identified as the canonical normative language. French is treated as a controlled working and translation language. This distinction should be preserved in every future release artifact.

### 2.3 Scope control

The repository consistently excludes software products, automated scoring platforms, certification products, and predictive-justice systems from JDGF v1.0. The documentary assessment instrument is correctly included as a necessary component of the maturity model.

## 3. Scientific and conceptual coherence

### 3.1 Framework dimensions

The canonical framework contains eight interdependent dimensions:

1. Leadership and institutional governance;
2. Legal, ethical, and rights-based governance;
3. Data architecture and interoperability;
4. Data quality and metadata;
5. Security, privacy, and continuity;
6. Data lifecycle and records governance;
7. Use, statistics, transparency, and responsible innovation;
8. Artificial intelligence readiness.

Dimension 8 is positioned downstream from the first seven dimensions and does not make technology adoption a maturity objective. This is consistent with the JDGF theory of change.

### 3.2 Measurement model

The maturity model is explicitly formative. It uses:

- six recurring capability attributes;
- item scores from 0 to 5;
- documentary evidence requirements;
- confidence ratings;
- critical-control gates and caps;
- non-compensatory reporting rules.

This specification is methodologically defensible as a candidate model. Internal-consistency statistics must not be treated as decisive validation evidence for this formative construct.

### 3.3 Critical-control logic

The model appropriately prevents strong scores in one area from concealing unresolved legal, rights, security, continuity, evidentiary-integrity, unauthorized-use, or uncontrolled-technology failures. The complete dimensional profile, confidence ratings, exclusions, and critical findings must accompany any aggregate result.

### 3.4 Validation status

Kadonia and the simulated pilot are fictional methodological exercises. They demonstrate internal applicability and reveal ambiguities, but they do not provide empirical evidence about real judicial institutions.

## 4. Assessment instrument audit

The documentary instrument covers all eight dimensions and is linked to the maturity model. It requires evidence references, findings, confidence ratings, and proposed actions.

The principal unresolved scoring issue is the distinction between:

- an obligation or policy that exists at national level but is neither recognized nor implemented in the assessed institution;
- an obligation that is recognized locally but only addressed through isolated or informal practice;
- a formally implemented institutional capability.

The scoring guide should state explicitly that the existence of an external legal or policy requirement does not, by itself, establish institutional capability. Local recognition without implementation may support Level 1 only when credible evidence of awareness or isolated practice exists. Otherwise, the capability remains Level 0. Implementation and operating effectiveness are required for higher levels.

This clarification should be tested during expert review and cognitive interviews rather than treated as empirically settled.

## 5. Case-study audit

The revised Kadonia case is appropriately labelled fictional and simulated. It applies eight dimensions, six attributes, evidence confidence, and critical-control logic.

The dual-rating simulation is useful as an instrument-development exercise. The observed agreement must not be reported as validated inter-rater reliability. Its main value is diagnostic: the disagreements identify scoring language that requires clarification before field testing.

## 6. Reference architecture audit

The repository contains two complementary evidence layers:

- normative and institutional references supporting requirements and standards mapping;
- academic and research literature supporting conceptual development, contextual interpretation, and publication work.

These layers should remain distinct and cross-referenced rather than physically merged into a single undifferentiated bibliography.

Within the current corpus, Dimensions 5 and 6 have comparatively limited Africa-focused academic support. This is a corpus gap and a literature-review priority; it is not evidence that relevant research does not exist.

## 7. Review and pilot readiness

The expert-review and cognitive-testing materials establish a credible pre-pilot workflow. Before data collection begins, the research team should freeze:

- the exact commit under review;
- the item set and scoring anchors;
- participant eligibility criteria;
- consent and confidentiality procedures;
- analysis rules and revision thresholds;
- the review-and-revision log.

Issue #3 should remain the operational tracker for expert review and cognitive testing. Issue #2 should remain the tracker for the subsequent authorized institutional pilot.

## 8. Editorial and provenance audit

Tool-specific drafting instructions and tool-named repository metadata are not part of the scientific framework and have been removed from the active branch. Substantive discussion of artificial intelligence remains because it is an explicit research object and the subject of Dimension 8.

The audit does not attempt to rewrite Git history or conceal the use of research tools. Commit history, pull-request events, and third-party review-bot activity remain part of the platform record. Scientific provenance should be governed through transparent authorship, contribution, source-verification, and review practices rather than claims about a particular writing process.

## 9. Release blockers

A stable JDGF v1.0 release remains blocked until the following conditions are met:

- [ ] expert content review completed and documented;
- [ ] cognitive testing completed for every assessment item and critical control;
- [ ] material interpretation and applicability issues resolved;
- [ ] clause-level standards mapping completed and checked;
- [ ] bibliographic metadata and source currency verified;
- [ ] at least one authorized institutional pilot completed;
- [ ] at least two independent assessors used on a representative subset;
- [ ] inter-rater agreement, feasibility, burden, missingness, and fairness analysed;
- [ ] scoring anchors revised using collected evidence;
- [ ] repository license selected and approved;
- [ ] final validation report and release notes published.

## 10. Priority sequence

1. Freeze the candidate commit for expert review.
2. Resolve the external-rule/local-implementation scoring ambiguity provisionally.
3. Recruit and brief the multidisciplinary expert panel.
4. Conduct independent content review and log every decision.
5. Conduct cognitive interviews with intended assessors and institutional respondents.
6. Revise and freeze the pre-pilot instrument.
7. Execute an authorized institutional pilot with independent raters.
8. Analyse agreement, feasibility, fairness, and evidence availability.
9. Complete references, licensing, and release governance.
10. Decide whether the evidence supports a stable v1.0 release.

## 11. Final audit judgement

**Status:** coherent JDGF v1.0 candidate; ready for structured pre-pilot validation activities; not empirically validated; not ready for stable release.
