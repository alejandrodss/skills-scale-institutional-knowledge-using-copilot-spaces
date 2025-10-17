# OctoAcme Project Management Processes

This folder contains OctoAcme program process documents and templates used to initiate, plan, execute, release, and iterate on cross-functional projects. The processes emphasize clear ownership, iterative delivery, measurable outcomes, and continuous improvement so teams can reduce risk, onboard faster, and operate with a single source of truth.

Summary (key workflows)
- Lifecycle: Initiation (one-pager and stakeholder alignment) → Planning (kickoff, prioritized backlog, estimates, Definition of Done) → Execution (work tracked on the project board, small PRs, CI gating) → Release (pre-release checks, smoke tests, rollback plan) → Close & Retrospective (action items and follow-up).
- Work tracking: Kanban-style project board with Backlog → Ready → In Progress → In Review → QA → Done. Backlog and PR templates include acceptance criteria, estimates, owners, and links to documentation.

Personas & roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications, and cross-team coordination.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, author tests, and participate in reviews.
- QA/Testing: validate acceptance criteria and support release verification.
- Stakeholders: provide inputs, approvals, and business context.

Communication & quality assurance
- Team rhythm: daily standups (15 min), weekly delivery sync, sprint demos/reviews, and regular PM+PdM syncs; monthly stakeholder updates and ad-hoc escalation paths.
- PR workflow: small PRs, include issue link and acceptance criteria, pass CI (tests + lint), require approval before merge.
- QA: unit and integration tests, E2E smoke tests for critical flows, security scanning in CI, and manual QA for acceptance when needed.
- Risk & incidents: maintain a Risk Register (ID, impact, likelihood, owner, mitigation), follow escalation paths (team → PM → Product Lead → Sponsor), and use incident communication templates and blameless retrospectives.

How to use these docs
- Keep the Project One-pager, risk register, and release notes updated in the project repo.
- Add process-specific docs into `.copilot/` for Copilot Spaces to use as context.
