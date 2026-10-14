# OctoAcme Project Management Docs (README)

This README consolidates OctoAcme's project management processes and provides quick links to the process documents stored in this repository's docs/ folder.

Summary

OctoAcme runs cross-functional projects with clear roles (Product Manager, Project Manager, Developers, QA), an iterative delivery cadence, and a lightweight set of artifacts (Project One-pager/Charter, prioritized backlog, risk register, and release plan). Initiatives start with a short one-pager to validate problem, goals, and success metrics and move through planning into execution where work is tracked on a project board. The team works in small, testable increments with defined acceptance criteria and a Definition of Done to keep scope clear and reduce risk.

Key workflows include a structured backlog-to-release flow (Backlog → Ready → In Progress → In Review → QA → Done), a pull request policy encouraging small PRs with linked issues and CI checks before review, and a release checklist that includes staging smoke tests and rollback planning. Communication practices center on daily standups for blockers and coordination, weekly delivery syncs for progress and risk review, and regular demos/reviews at the end of sprints or milestones.

Quality assurance emphasizes automated testing and security checks (unit, integration, and end-to-end smoke tests), CI-based security scanning, and manual QA when required for feature acceptance. Retrospectives after sprints or incidents capture learnings and convert them into tracked action items that are reviewed in regular PM syncs.

Process documents (links)

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

Suggested next steps

- Link this README from the repository root README and from any project templates or Copilot Spaces entrypoints.
- Create a pull request from this branch to merge the README into the docs/ folder and include `Closes #2` in the PR description to link the issue that requested this change.

Suggested PR title

[Process Doc Update]: README — project management processes summary and links to docs in docs/

Suggested PR description

This PR adds docs/README.md which consolidates OctoAcme project management process summaries and provides direct links to each document in docs/. It includes a short overview of key workflows, roles, communication cadence, and quality practices.

Closes #2
