# 3. Stakeholder Analysis

The Master Brief explicitly describes three primary user groups: requesters, authorised staff, and management/oversight (Belgium Campus ITversity, 2026a). The analysis below also identifies project/lifecycle stakeholders that are implied by the organisation's business need and by mandatory operational/governance responsibilities. Those inferred stakeholders are labelled as such. Influence and interest ratings are team assessments for M1, not facts supplied by an interview.

| ID | Stakeholder | Basis | Needs / expectations | Influence / interest | Main conflict / trade-off |
|---|---|---|---|---|---|
| STK-01 | Requester | Explicit primary product stakeholder | Submit requests with appropriate information; categorise requests; view current status and history; receive meaningful feedback; have own information handled appropriately. | High / High | Transparency must not expose sensitive information to unauthorised people. |
| STK-02 | Authorised service staff | Explicit primary product stakeholder | View relevant requests; search/filter/sort; view details; take/assign responsibility; update status through controlled transitions; record actions/comments; resolve/close where authorised. | High / High | Operational flexibility can conflict with lifecycle control and accountability. |
| STK-03 | Management / oversight | Explicit primary product stakeholder | View useful service activity information; identify open/overdue/resolved/closed work; analyse by category/status or justified dimensions; support accountability and service-performance analysis. | High / High | Demand for broader reporting can expand scope and complexity. |
| STK-04 | Organisation / service owner | Inferred business stakeholder | A sustainable controlled platform that improves visibility and accountability without excessive technical, operational or financial burden. | High / High | Low-cost expectations can conflict with resilience, security, monitoring or advanced functionality. |
| STK-05 | System administration / operations | Inferred lifecycle stakeholder | Controlled configuration, access, secrets handling, deployment, logs, recovery and maintainable operation. | Medium / High | Operational controls consume effort that could otherwise be spent on visible features. |
| STK-06 | SEN381 project team | Project delivery / engineering stakeholder | Clear scope, traceable requirements, manageable workload, controlled decisions, meaningful peer review and sufficient evidence to engineer and defend CivicConnect successfully. | High / High | Engineering governance and evidence activities consume schedule capacity that could otherwise be spent on implementation, but these controls are mandatory for project success. |

The ratings above represent the team's M1 assessment rather than stakeholder interview evidence. Influence reflects the stakeholder's ability to affect product requirements, approval, operational use or project delivery, while interest reflects the extent to which CivicConnect's outcomes affect that stakeholder. These ratings will be reviewed if further stakeholder evidence becomes available.

## 3.1 Stakeholder Conflicts and M1 Responses

| Conflict | Why it matters | M1 response |
|---|---|---|
| Requester transparency vs confidentiality | Requesters need meaningful status/history, but sensitive details must not be exposed to other requesters or unauthorised staff. | Baseline authorised access and controlled user-facing feedback; detailed identity design remains a later decision. |
| Staff flexibility vs lifecycle control | Staff must progress work efficiently, but unrestricted status changes would recreate weak accountability. | Require controlled status transitions and traceable actions; the exact transition catalogue remains an open business rule. |
| Management reporting vs scope discipline | Management may want many dashboards and reporting dimensions. | Commit only to the minimum oversight capabilities in the brief; advanced analytics/export remains deferred unless justified. |
| Low cost vs operational readiness | Free/low-cost services are preferred, but security, recovery and observability still matter. | Treat cost as a decision criterion, not permission to ignore quality/security/operations. |
| Feature breadth vs quality/evidence | Additional features consume time needed for requirements, reviews, testing, security and evidence. | Use a conservative scope baseline and assess additions through controlled change. |
