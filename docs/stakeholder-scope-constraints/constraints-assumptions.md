# 5. Assumptions and Constraints

## 5.1 Explicit Project Constraints and Mandatory Engineering Controls

The following project constraints and mandatory engineering controls are derived directly from the Master Project Brief (Belgium Campus ITversity, 2026a). Their engineering implications represent the team's analysis of how these controls should influence later project work.

| ID | Type | Constraint | Source | Engineering implication |
|---|---|---|---|---|
| C-001 | Team size | Exactly 3 students. | Master Brief Section 4 | All controlled work must fit a three-person team; substantive PR review capacity must be planned. |
| C-002 | Schedule | Four formal milestones within the SEN381 delivery period. | Master Brief Section 4 | Scope and evidence must progress incrementally; late reconstruction of evidence is not acceptable. |
| C-003 | Cost / resources | Prefer free or low-cost services where practical and identify limits/likely operational cost. | Master Brief Section 4, Section 18 | Later platform choices must consider total cost and free-tier limitations. |
| C-004 | Scope | Committed scope must be baselined and controlled. | Master Brief Section 4, Section 14 | Additional features must undergo impact analysis instead of being silently absorbed. |
| C-005 | Quality | Quality attributes must be defined and later supported by measurable evidence. | Master Brief Section 4, Section 15 | Requirements must include testable quality expectations linked to later verification. |
| C-006 | Security | Security is a lifecycle-wide responsibility, not a final add-on. | Master Brief Section 4, Section 16 | Security/privacy concerns must influence requirements, repository controls, design, testing and deployment. |
| C-007 | Technology | No stack, architecture or platform is prescribed. | Master Brief Section 4, Section 18.1 | Technology selection must be deferred until evidence-based comparison against requirements, team capability, cost, security and deployment constraints. |
| C-008 | Institutional environment | BC cannot guarantee support/compatibility for every technology or external service. | Master Brief Section 25 | The team must investigate compatibility before committing and manage the risk of unavailable/unsupported technology. |
| C-009 | Configuration management | Protected main, PRs and two non-author approvals are mandatory for substantive changes. | Master Brief Section 9 | Review capacity becomes part of the schedule; substantive direct development on main is not acceptable. |
| C-010 | AI accountability | AI output is not authoritative evidence; material use must be recorded and verified. | Master Brief Section 10 | AI-assisted work must be independently checked and remains the team's responsibility. |

## 5.2 Controlled Assumptions / Evidence Gaps

The following assumptions identify information that is not specified in the project brief and will require validation as further project evidence becomes available.

| ID | Assumption / evidence gap | Treatment |
|---|---|---|
| A-001 | The supplied project briefs are the current authoritative source for M1; no stakeholder interview evidence has been supplied at this stage. | Validate if the lecturer/client provides additional evidence. |
| A-002 | CivicConnect is treated as a single-organisation platform; multi-tenant operation is not baselined. | Revisit only if a stakeholder requires multi-tenancy. |
| A-003 | Users will have controlled identities/roles, but the identity mechanism is not chosen in M1. | Require evidence before the M2 authentication decision. |
| A-004 | The brief does not provide production workload volumes. | Do not claim workload/performance facts until evidence exists. |
| A-005 | The exact category catalogue, status-transition catalogue and overdue rule are not supplied. | Treat as high-priority open business-rule gaps. The team must define and validate these rules before detailed design; however, the requirement to identify overdue requests remains baselined. |
| A-006 | The brief states that sensitive request information may exist but does not define detailed data-classification or retention rules. | Perform security/privacy analysis before persistence design. |

## 5.3 Constraint Interactions / Ripple Effects

| Interaction | Engineering consequence |
|---|---|
| Three-person team + two non-author approvals + fixed milestone schedule | Because every substantive PR needs review by both non-author members, review capacity is a real schedule constraint. Large late PRs would create a bottleneck. The team should therefore use smaller coherent changes and review progressively. |
| Low cost + quality/security/operational readiness | A free platform is not automatically acceptable. Future technology/platform decisions must still support secure configuration, testing, deployment, recovery and operational evidence. |
| Scope + schedule + quality | Adding optional features increases implementation and verification work. Under schedule pressure the correct response is controlled scope change, not silently reducing testing, security or evidence. |
