# OctoAcme Project Management Docs

Welcome — this folder collects OctoAcme's project management guidance, templates, and checklists used to run cross-functional projects. These documents are intended to centralize working practices, reduce single-person dependencies, and speed onboarding by making process knowledge discoverable and versioned.

Summary of Project Management Processes
OctoAcme follows a lightweight, iterative lifecycle focused on delivering customer value in small, testable increments. Projects begin with a Project One-pager to align on problem, goals, and success metrics, pass a decision gate for planning, and are then broken into a prioritized backlog with clear acceptance criteria and a Definition of Done. Planning produces a release and milestone plan and captures initial risks and dependencies.

Execution emphasizes visibility and repeatability: teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done), enforce small, well-scoped PRs, and require CI, tests, and at least one review before merging. Releases follow a checklist-driven approach (pre-release CI & security scans, smoke tests in staging, rollback plans, and post-deploy verification). Risk management and communication are cadence-driven — daily standups, weekly delivery syncs, PM–PdM alignment, demos, and stakeholder updates — with escalation paths for blockers and security incidents. Retrospectives and tracked action items close the improvement loop.

Roles and Responsibilities
Core personas include Product Managers (define outcomes and prioritize), Project Managers (coordinate delivery, risks, and communications), Developers (implement and test), QA (validate acceptance), and Stakeholders (inputs and approvals). Templates and checklists in this folder help to make ownership explicit and handoffs repeatable.

Documentation Index
- Project Management Overview: docs/octoacme-project-management-overview.md
- Project Initiation Guide: docs/octoacme-project-initiation.md
- Project Planning: docs/octoacme-project-planning.md
- Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Risks & Communication: docs/octoacme-risks-and-communication.md
- Release & Deployment Guide: docs/octoacme-release-and-deployment.md
- Retrospectives & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: docs/octoacme-roles-and-personas.md

How to use and contribute
- Keep the Project One-pager and the project README updated in the project repo as the single source of truth.
- To propose updates to any process doc, use the issue template "Add Content to Project Management Process Docs" in .github/ISSUE_TEMPLATE/.
- Recommended practice: when a doc change is merged, add a short CHANGELOG entry at the top of the affected doc (date, author, summary).

Acceptance checklist
- [ ] README aligns with the process docs in this folder
- [ ] README provides clear entry points for contributors and maintainers
- [ ] README links to all existing docs in docs/
