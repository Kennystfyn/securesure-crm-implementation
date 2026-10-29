# SecureSure Insurance — CRM Implementation (Project Tiger)

**Case study:** SecureSure Insurance (~50,000 policyholders, Auto & Life)
**Project type:** Business Analysis Portfolio Case Study — CRM implementation
**Status note:** A proposed solution and analysis built around a case-study organization; no deployment or business results are claimed.

## Business context
SecureSure's Auto Sales, Life Sales, and Customer Service teams each ran on separate legacy tools with no shared customer view. Agents couldn't see a policyholder's prior interactions, coordinate follow-ups across product lines, or spot cross-sell opportunities — leading to repetitive work, inconsistent service, limited reporting, and missed retention opportunities.

## Approach
Delivered a full CRM implementation business analysis, "Project Tiger":
- **Stakeholder analysis** — 12 stakeholder groups mapped on a power-interest matrix (Executive Sponsor, PM, BA, Head of Sales, Sales teams, Customer Care, Head of IT, IT team, CRM vendor, Finance, Legal/Compliance, Policyholders)
- **RACI matrix** — 6 key activities (approve objectives, elicit requirements, approve solution design, data migration, UAT coordination, go-live approval) mapped across roles
- **AS-IS / TO-BE process mapping** — swimlane diagrams showing the current fragmented, repeat-everything workflow vs. a unified-CRM future state with identity verification, shared interaction timelines, and governed data sync
- **Gap analysis** — technology gaps (limited integration, duplicate identities, fragmented reporting), process gaps (manual handoffs, unclear ownership), and people gaps (inconsistent usage, training needs, change resistance)
- **Business Requirements Document (BRD)** — formal requirements catalogue with BR/FR/NFR IDs, type, and priority (Must/Should), business rules, acceptance/success criteria, dependencies & risks, and a sign-off page
- **Requirements and user stories** — including a full example user story with Given/When/Then acceptance criteria for cross-product interaction history
- **Data migration & integration strategy** — legacy inventory, identifier matching, field mapping, controlled-batch migration, reconciliation, and rollback planning
- **Change management & communication plan** — phased pilot rollout, department champions, role-based training, and a 5-audience communication plan (sponsor/steering, sales & care leads, IT/vendor, end users, legal/compliance)
- **Testing, UAT & release readiness**, plus a **KPI and benefits measurement plan**

## Key requirements (from the BRD)
| ID | Requirement | Priority |
|---|---|---|
| BR01 | Unified customer view across Auto and Life | Must |
| FR01 | Search customers by unique ID / approved attributes | Must |
| FR02 | Show Auto and Life policies in one authorized profile | Must |
| FR03 | Record calls, emails, and service cases on a timeline | Must |
| FR04 | Create and assign follow-up tasks with due dates | Must |
| FR05 | Flag duplicate candidate records for review | Must |
| FR06 | Dashboard by team, cases, opportunities, retention | Should |
| NFR01 | Role-based access and audit logs | Must |
| NFR03 | Protect personal data during migration and retention | Must |

## Proposed KPIs (illustrative targets, not achieved results)
| KPI | Proposed target |
|---|---|
| CRM active-user adoption | ≥85% within 90 days |
| Customer record completeness | ≥95% |
| Duplicate customer rate | <2% |
| Case handoff time | 30% below baseline |
| Follow-up completion | ≥90% |

## Outcome / Impact
A structured path from a fragmented, multi-system customer experience to a governed, unified CRM — with the requirements, risk register, migration strategy, and change management plan needed to take the business case to stakeholder sign-off. The report is explicit that CRM success depends as much on process redesign, data quality, and user adoption as on the software itself; no financial ROI is claimed without a measured baseline.

## Skills demonstrated
Stakeholder analysis & power-interest mapping · RACI matrix · AS-IS/TO-BE swimlane process mapping · gap analysis · Business Requirements Document (BRD) authoring · user stories & acceptance criteria · data migration strategy · change management & communication planning · UAT planning · KPI & benefits measurement planning

## Files
- [SecureSure_CRM_Implementation_BA_Portfolio_Report.docx](./SecureSure_CRM_Implementation_BA_Portfolio_Report.docx) — full business analysis portfolio report
- [SecureSure_Business_Requirements_Document.docx](./SecureSure_Business_Requirements_Document.docx) — formal Business Requirements Document (BRD)
- **[▶ View the AS-IS / TO-BE swimlane diagrams online](https://viewer.diagrams.net/#Uhttps%3A%2F%2Fraw.githubusercontent.com%2FKennystfyn%2Fsecuresure-crm-implementation%2Fmain%2FSecureSure_CRM_Process_Maps.drawio)** — opens in your browser, no download needed
- [SecureSure_CRM_Process_Maps.drawio](./SecureSure_CRM_Process_Maps.drawio) — editable source file (open at [app.diagrams.net](https://app.diagrams.net))
