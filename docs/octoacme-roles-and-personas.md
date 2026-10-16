# Roles and Personas

This document expands the set of personas used across OctoAcme project management processes. For each persona we provide: purpose, key responsibilities, typical artifacts, interactions (RACI-like), and escalation path. This addition implements the request in issue #4.

---

## Personas and Responsibilities

### Project Sponsor
- Purpose: Senior stakeholder who provides strategic direction and funding authority for projects.
- Key responsibilities:
  - Approve project initiation, major scope changes, and budget decisions.
  - Champion projects at the executive level and remove organizational barriers.
  - Validate alignment to business objectives.
- Typical artifacts:
  - Project charter, business case, executive status updates.
- Interactions / RACI-style:
  - Accountable (A) for project outcomes and major decisions.
  - Consulted (C) by Program Manager and Project Manager on escalations.
  - Informed (I) through regular executive summaries.
- Escalation path: Project Manager -> Program Manager / PMO -> Project Sponsor.

---

### Program Manager / PMO Representative
- Purpose: Coordinate multiple projects to ensure governance, standards, and cross-project alignment.
- Key responsibilities:
  - Maintain common processes, templates and tooling.
  - Track cross-project dependencies, portfolio-level risks, and resource conflicts.
  - Support prioritization decisions and reporting to executives.
- Typical artifacts:
  - Program roadmap, RAID logs, portfolio dashboards.
- Interactions / RACI-style:
  - Responsible (R) for governance and standards; Consulted (C) on cross-project impact.
  - Coordinates with Project Managers, Risk Owner, and Project Sponsor.
- Escalation path: Project Manager -> Program Manager -> Project Sponsor.

---

### Project Manager / Delivery Lead
- Purpose: Lead day-to-day project delivery, ensuring scope, schedule, budget and quality targets are met.
- Key responsibilities:
  - Create and maintain the project plan, manage resources, and monitor progress.
  - Drive risk mitigation and manage issues to resolution.
  - Coordinate communications and stakeholder engagement.
- Typical artifacts:
  - Project plans, schedules, risk & issue logs, status reports.
- Interactions / RACI-style:
  - Responsible (R) for delivery execution.
  - Accountable (A) for on-time/on-budget delivery to Sponsor (for operational matters).
  - Consulted (C) with Product Owner, Technical Lead, QA Lead, Release Manager.
  - Informs Stakeholder Liaison and Program Manager.
- Escalation path: Project Manager -> Program Manager -> Project Sponsor.

---

### Product Owner / Business Lead
- Purpose: Define product scope, priorities, and acceptance criteria representing the business perspective.
- Key responsibilities:
  - Prioritize backlog and define acceptance criteria.
  - Validate delivered increments against business needs.
  - Make scope trade-off decisions for features and requirements.
- Typical artifacts:
  - Product backlog, user stories, acceptance criteria, business requirements.
- Interactions / RACI-style:
  - Accountable (A) for scope and acceptance of deliverables.
  - Works closely with Project Manager, Business Analyst, UX Researcher, and QA Lead.
- Escalation path: Product Owner -> Project Manager -> Program Manager.

---

### Technical Lead / Architect
- Purpose: Provide technical direction and ensure architectural integrity and scalability.
- Key responsibilities:
  - Define system architecture and high-level technical approach.
  - Review designs, mentor developers, and ensure non-functional requirements are met.
  - Make technical trade-off decisions and maintain technical quality.
- Typical artifacts:
  - Architecture diagrams, design docs, technical decision records (TDRs).
- Interactions / RACI-style:
  - Responsible (R) for technical decisions and code quality.
  - Consulted (C) with Project Manager, Developers, QA Lead, and Security Champion.
- Escalation path: Technical Lead -> Project Manager -> Program Manager (for cross-project technical conflicts).

---

### Release Manager
- Purpose: Coordinate release activities across teams to ensure safe, repeatable deployments.
- Key responsibilities:
  - Own and maintain a release checklist and schedule.
  - Coordinate deployment windows, release approvals, and rollback plans.
  - Ensure release readiness (QA sign-offs, build verification, release notes).
- Typical artifacts:
  - Release checklist, deployment runbooks, cutover plans, release calendar.
- Interactions / RACI-style:
  - Responsible (R) for the release process execution.
  - Consulted (C) with Project Manager, QA Lead, DevOps/Operations, and Technical Lead.
  - Informs Stakeholders of release content/timing.
- Escalation path: Release Manager -> Project Manager -> Program Manager.

---

### QA Lead / Test Lead
- Purpose: Ensure delivered software meets agreed quality standards and acceptance criteria.
- Key responsibilities:
  - Define test strategy and test plans; maintain test environments.
  - Drive test execution and sign-off quality gates prior to release.
  - Track test coverage, defects, and quality metrics.
- Typical artifacts:
  - Test plans/cases, test reports, defect/bug reports, acceptance test results.
- Interactions / RACI-style:
  - Responsible (R) for QA activities and acceptance gate sign-off.
  - Consulted (C) with Developers, Product Owner, Release Manager, and Technical Lead.
- Escalation path: QA Lead -> Project Manager -> Technical Lead / Program Manager (depending on issue scope).

---

### Security Champion / Compliance Officer
- Purpose: Ensure security and compliance considerations are integrated throughout the project lifecycle.
- Key responsibilities:
  - Review designs and implementations for security and compliance issues.
  - Maintain compliance checklists and advise on controls and mitigations.
  - Coordinate security testing (SAST/DAST) and threat modeling if needed.
- Typical artifacts:
  - Security checklists, compliance reports, threat models, audit findings.
- Interactions / RACI-style:
  - Consulted (C) during design and code review phases.
  - Informs Project Manager and Program Manager of critical issues.
- Escalation path: Security Champion -> Technical Lead -> Project Manager -> Program Manager.

---

### Business Analyst
- Purpose: Translate business needs into clear requirements and acceptance criteria.
- Key responsibilities:
  - Elicit and document requirements, user journeys, and acceptance criteria.
  - Support Product Owner in backlog refinement and prioritization.
  - Clarify requirements for the development team and QA.
- Typical artifacts:
  - Requirements docs, user stories, acceptance criteria, process maps.
- Interactions / RACI-style:
  - Responsible (R) for requirements clarity and documentation.
  - Consulted (C) with Product Owner, Project Manager, UX, and QA Lead.
- Escalation path: Business Analyst -> Product Owner -> Project Manager.

---

### Stakeholder Liaison / Communications Lead
- Purpose: Manage stakeholder expectations and communications across the project lifecycle.
- Key responsibilities:
  - Maintain stakeholder register and communication plan.
  - Organize demos, status updates, and collect stakeholder feedback.
  - Manage publication of release notes and external communications.
- Typical artifacts:
  - Communication plan, stakeholder matrix, demo agendas, release communications.
- Interactions / RACI-style:
  - Responsible (R) for stakeholder communications and status dissemination.
  - Consulted (C) with Project Manager and Project Sponsor.
- Escalation path: Stakeholder Liaison -> Project Manager -> Program Manager.

---

## Presentation and Handoff Examples
To reduce ambiguity, include short sequences in this document or an appendix showing the typical handoff flows. For example:

- Feature delivery flow: Product Owner (defines) -> Business Analyst (refines) -> Devs/Technical Lead (implement) -> QA Lead (test) -> Release Manager (release) -> Stakeholder Liaison (announce)
  - RACI snippet: R: Devs/QA/Release; A: Product Owner (scope) / Project Manager (delivery);

- Incident / escalation flow: Developer discovers critical defect -> Technical Lead assesses -> Project Manager coordinates mitigation -> Program Manager and Project Sponsor informed if cross-project or high impact.

---

## Next steps
1. Review these entries with project stakeholders and validate titles and responsibilities.
2. Add short diagrams or sequence examples for the most common flows (planning, release, incident).
3. Iterate and incorporate stakeholder feedback; finalize acceptance criteria before publication.
