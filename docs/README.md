# OctoAcme Project Management Docs

This README provides a concise entry point to OctoAcme's project management processes and direct links to the detailed documents in the docs/ folder. It is intended to help new team members and contributors quickly find the right process guidance for initiation, planning, execution, risk management, releases, and continuous improvement.

OctoAcme follows a clear project lifecycle: initiation, planning, execution, release, and retrospective. During initiation the team validates the business need, defines success metrics, identifies stakeholders, and produces a lightweight one-pager to align on goals and constraints. Planning turns approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release timeline that surfaces dependencies and risks.

Execution is organized around a steady delivery rhythm supported by project boards, daily standups, and a small-PR workflow that requires CI and at least one approval before merging. Project Managers coordinate schedules, risks, and communications while Product Managers define outcomes and priorities; developers implement and test features, and QA validates acceptance criteria. Cross-team dependencies are tracked and escalated via an agreed path from team triage to PM, Product Lead, and sponsor-level intervention when necessary.

Quality assurance is embedded throughout the process: work items include clear acceptance criteria, automated unit/integration tests run in CI, security scanning is part of the pipeline, and manual QA or smoke tests are performed for critical flows. After releases teams run post-deploy verifications and capture lessons learned in retrospectives so improvements are incorporated into future work.

Docs (in this repository's docs/ folder):
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

How to use this README:
- Use these links as the single source of truth for project processes.
- When adding or updating process docs, update this README to include new links and a short summary.
- To propose changes to these process docs, use the "Add Content to Project Management Process Docs" issue template located in .github/ISSUE_TEMPLATE/.
