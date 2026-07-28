# JDGF Language Policy

**Status:** Adopted for the JDGF v1.0 candidate  
**Date:** 2026-07-28

## 1. Canonical language

English is the canonical normative language of the public JDGF repository for the v1.0 candidate.

This choice supports international scientific review, comparison with global standards, external contribution, and publication across jurisdictions.

## 2. French working language

French may be used for:

- project discussions and working sessions;
- explanatory summaries;
- stakeholder engagement in francophone jurisdictions;
- draft translations;
- training and implementation materials where appropriate.

Use of French in project work does not create a second competing normative framework.

## 3. Translation status

A French document must identify one of the following statuses:

- **Working translation:** informative and not independently normative;
- **Reviewed translation:** checked for terminology and substantive consistency;
- **Official translation:** approved through JDGF change control.

Until an official translation is approved, the English canonical version prevails in case of divergence.

Recommended notice:

> This is a French translation of the canonical English JDGF text. In case of divergence, the English version prevails unless this translation is explicitly designated as official.

## 4. Terminology control

Translations must:

- use the controlled JDGF glossary;
- preserve requirement strength and modal verbs;
- preserve identifiers, maturity levels, formulas, gates, and scope boundaries;
- avoid translating the same defined term in multiple inconsistent ways;
- record unresolved terminology questions before publication.

## 5. Repository organization

During candidate development, canonical English documents remain in the existing directory structure. Controlled translations should be added only when their maintenance owner and review status are clear.

A future bilingual structure may use:

```text
docs/
├── en/   # canonical normative documents
└── fr/   # controlled translations
```

Migration to that structure requires a dedicated change because it affects links, references, contributor workflows, and release packaging.

## 6. Contribution policy

Contributions may be proposed in English or French. Normative changes must ultimately be incorporated into the canonical English document before release. Translators should not introduce substantive changes; substantive proposals must be reviewed as framework changes first.