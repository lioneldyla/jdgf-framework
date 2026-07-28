# JDGF Review and Revision Log

**Version:** 1.0 Candidate  
**Purpose:** Trace every material comment, test finding, decision, and resulting change made during expert review, cognitive testing, pilot assessment, and release preparation.

## 1. Governance rules

- Never delete a substantive review comment from the record.
- Record accepted, partially accepted, rejected, deferred, and duplicate comments.
- Provide an evidence-based rationale for every decision.
- Identify the affected version and files.
- Separate editorial changes from conceptual, methodological, legal, security, and scoring changes.
- Require explicit approval for changes to dimensions, maturity anchors, critical controls, formulas, or scope.
- Do not use reviewer seniority as a substitute for evidence or documented reasoning.

## 2. Status values

- **Open** — not yet assessed;
- **Under review** — evidence or consultation being gathered;
- **Accepted** — change approved;
- **Partially accepted** — some but not all of the proposal approved;
- **Rejected** — proposal not adopted, with reason;
- **Deferred** — valid issue assigned to a later version or research phase;
- **Duplicate** — already covered by another entry;
- **Implemented** — approved change committed;
- **Verified** — implementation independently checked.

## 3. Severity values

- **Critical:** could invalidate the framework, create serious rights or safety risk, or make scoring materially misleading;
- **High:** major conceptual, legal, methodological, or operational weakness;
- **Moderate:** meaningful clarity, feasibility, consistency, or evidence problem;
- **Low:** editorial or limited improvement opportunity.

## 4. Master log

| Log ID | Date | Source type | Source code | Affected component | Item / section | Finding or proposal | Evidence / rationale | Severity | Decision | Decision rationale | Owner | Target version | Commit / implementation reference | Verification | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| REV-0001 | | Expert / cognitive test / pilot / audit / public comment | | | | | | | | | | | | | Open |

## 5. Dimension-change register

Any proposal to add, remove, merge, split, or rename a dimension must complete this section.

| Proposal ID | Current structure | Proposed structure | Problem addressed | Supporting evidence | Crosswalk impact | Instrument impact | Scoring impact | Decision authority | Decision |
|---|---|---|---|---|---|---|---|---|---|
| | | | | | | | | | |

## 6. Scoring-change register

| Proposal ID | Current rule | Proposed rule | Triggering evidence | Expected benefit | Gaming / inflation risk | Comparability impact | Retesting required | Decision |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

## 7. Critical-control register

| Control ID | Dimension | Failure condition | Harm rationale | Current cap | Proposed change | Expert support | Pilot evidence | Decision | Verification condition |
|---|---|---|---|---:|---|---|---|---|---|
| | | | | | | | | | |

## 8. Terminology register

| Term | Problem observed | Contexts affected | Current definition | Proposed definition | Translation impact | Decision |
|---|---|---|---|---|---|---|
| | | | | | | |

## 9. Release-decision summary

Before a release candidate is approved, summarize:

- unresolved critical findings;
- unresolved high findings;
- deferred items and their justification;
- changes requiring renewed expert or cognitive testing;
- backward-compatibility implications;
- evidence supporting release;
- evidence still absent;
- authorized decision-maker and decision date.

## 10. Verification checklist

For every implemented material change:

- ☐ affected documents updated;
- ☐ cross-references updated;
- ☐ glossary updated where needed;
- ☐ assessment items updated;
- ☐ scoring formulas and gates checked;
- ☐ examples or case studies re-scored if affected;
- ☐ bibliography and standards mapping updated;
- ☐ language implications recorded;
- ☐ change entered in `CHANGELOG.md`;
- ☐ independent verification completed.
