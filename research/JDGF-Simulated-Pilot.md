# JDGF Simulated Pilot

**Version:** 1.0 Candidate  
**Status:** Simulation for instrument testing — not an institutional validation

## 1. Purpose and warning

This desk-based simulation demonstrates the JDGF scoring workflow, critical-control gates, confidence ratings, and reporting format. It does **not** use data from a real court, ministry, prosecution service, prison administration, or other institution. Its scores must not be cited as empirical findings or evidence that JDGF is validated.

## 2. Fictional institutional context

The fictional institution is a medium-sized first-instance court with:

- mixed paper and electronic case records;
- a case-management application;
- a small statistics unit;
- centralized infrastructure support;
- informal data-quality coordination;
- approved security procedures but limited evidence of periodic access review;
- no use of high-risk AI in adjudication.

## 3. Simulated evidence set

| Evidence ID | Fictional evidence |
|---|---|
| E01 | Court digital-transformation strategy approved two years ago |
| E02 | Information-security policy and incident procedure |
| E03 | Case-management user-role list and partial access-review record |
| E04 | Monthly judicial-statistics reports and extraction spreadsheet |
| E05 | Records retention schedule awaiting formal approval |
| E06 | Minutes of an informal data-quality working group |
| E07 | Sample data dictionary covering selected case fields |
| E08 | Backup test report from the prior year |
| E09 | Data-sharing agreement with a central judicial administration |
| E10 | Interview notes from registry, statistics, IT, and leadership staff |

## 4. Independent simulated scores

Two fictional assessors independently applied the candidate scoring anchors.

| Dimension | Assessor A | Assessor B | Moderated | Confidence | Principal simulated issue |
|---|---:|---:|---:|---|---|
| Leadership and institutional governance | 2.30 | 2.10 | 2.20 | Moderate | No formally approved data-governance mandate or assigned data owners |
| Legal, ethical, and rights-based governance | 2.70 | 2.50 | 2.60 | Moderate | Legal obligations recognized, but impact assessment and redress processes are incomplete |
| Data architecture and interoperability | 2.40 | 2.20 | 2.30 | Moderate | Partial inventory and dictionary; lineage is undocumented |
| Data quality and metadata | 2.20 | 2.00 | 2.10 | Moderate | Working group exists, but quality rules and issue management are informal |
| Security, privacy, and continuity | 2.80 | 2.50 | 2.60 | Moderate | Access reviews are incomplete and continuity testing is not current |
| Data lifecycle and records governance | 1.90 | 1.70 | 1.80 | Low | Retention schedule is not approved and disposition evidence is absent |
| Use, statistics, transparency, and responsible innovation | 2.60 | 2.40 | 2.50 | Moderate | Statistics are produced, but quality assurance and disclosure-risk procedures are incomplete |

`Simulated overall score = 2.30`

The overall descriptive result is **Level 2 — Emerging**. The profile is uneven and must be reported alongside the aggregate score.

## 5. Gate and cap demonstration

No fictional critical finding was classified as an immediate threat requiring the Level 2 cap, but the lifecycle dimension remains below Level 2 because its approved governance instruments and operational evidence are insufficient.

The court cannot claim Level 3 because:

- the data-governance mandate is not formally approved;
- ownership and stewardship are not consistently assigned;
- several key processes are informal;
- evidence of operating effectiveness is incomplete.

## 6. Simulated assessor agreement

The absolute difference between assessors ranges from 0.20 to 0.30 points at dimension level. This illustration shows how moderation can work, but it is not a reliability statistic because the case and ratings were constructed for demonstration.

A real pilot must calculate weighted agreement or intraclass correlation using independently collected ratings across actual institutions or representative cases.

## 7. Simulated improvement priorities

### Priority 1 — Establish institutional accountability

- approve a judicial data-governance charter;
- appoint accountable data owners and operational stewards;
- define decision rights and escalation routes;
- create a regular governance council agenda and evidence register.

### Priority 2 — Protect lifecycle and evidentiary integrity

- approve the retention schedule;
- document legal holds, archival transfer, and disposition authorization;
- test authenticity, chain-of-custody, and recovery procedures;
- retain verifiable disposition evidence.

### Priority 3 — Formalize quality and metadata

- identify critical data elements;
- approve common definitions and validation rules;
- establish thresholds and quality indicators;
- implement an issue register with root-cause analysis and accountable remediation.

### Priority 4 — Strengthen access and continuity assurance

- complete periodic access reviews;
- test backup restoration and service continuity;
- record incidents, lessons learned, and corrective actions;
- assess third-party and exchange risks.

### Priority 5 — Govern statistics and secondary use

- document statistical production and release controls;
- assess confidentiality and disclosure risk;
- formalize research and data-sharing approvals;
- inventory analytics and any future AI use before deployment.

## 8. Instrument observations from the simulation

The simulation suggests that the instrument should:

- require item identifiers and critical-item markers;
- separate design and operating-effectiveness evidence;
- record N/A rationale and approval;
- distinguish item score from evidence confidence;
- include an assessor disagreement log;
- prohibit unsupported half scores;
- automatically apply gates and caps without hiding the raw profile.

These observations informed the revised Maturity Model and Pilot Protocol. They remain hypotheses for testing in a real institutional pilot.

## 9. Conclusion

The simulation demonstrates that JDGF can generate a structured maturity profile and risk-based roadmap. It does not demonstrate external validity, reliability, feasibility, fairness, or institutional impact. Those claims require authorized real-world fieldwork under `JDGF-Institutional-Pilot-Protocol.md`.
