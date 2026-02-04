# OctoAcme Project Management Docs

Welcome — this folder contains the core project management process documentation used by OctoAcme. The goal of this README is to provide a concise orientation to our lifecycle, key workflows, personas, communication cadence, and quality practices, and to link directly to detailed process documents in this directory.

OctoAcme runs projects through a clear lifecycle: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement. Initiation uses a lightweight one-pager that captures problem statements, success metrics, stakeholders, and a go/no-go decision. Planning turns approved initiatives into a prioritized, estimated backlog, defines a Definition of Done (DoD), and produces a release plan with milestones and dependency calls. Execution emphasizes small, incremental delivery via the project board and disciplined PR workflow, with explicit blocker escalation and regular demos. Release activity follows a checklist-based approach (pre-release checks, smoke testing, rollback plan) and post-deploy verification. Retrospectives capture learning, create action items, and feed improvements back into the backlog.

Workflows and day-to-day execution focus on visible status and repeatability. We use a project board (Backlog → Ready → In Progress → In Review → QA → Done), small PRs with linked issues and acceptance criteria, CI gates (tests, linting, security scans), and a requirement for reviews/approvals. Blockers are triaged in daily standups; unresolved or high-impact blockers escalate to PM → Product Lead → Sponsor. The execution process includes an execution checklist (branching conventions, CI, risk register updates, demos) and explicit reporting on velocity, burndown, and key success metrics.

Roles and communication are explicit to minimize ambiguity. PMs coordinate schedules, risks, and stakeholder updates; Product Managers define outcomes and prioritize the backlog; Developers implement and test; QA validates acceptance criteria and leads manual/acceptance testing; Stakeholders provide approvals and business context. Communication cadence includes daily standups, weekly delivery syncs, a weekly PM–PdM alignment, sprint/milestone demos, and monthly stakeholder updates. QA practices enforce unit and integration tests, E2E smoke tests for critical flows, CI-based security scanning, and manual QA when needed. See the linked docs below for detailed templates, checklists, and role descriptions.

Docs index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

How to review this change
- Confirm the overview matches the linked documents and the team’s practices.
- Update any links or filenames if your repo structure differs.
- Suggest clarifications for any onboarding language or missing templates.

(If you prefer a top-level docs/README.md filename instead, rename accordingly.)
