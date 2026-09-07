# OctoAcme Project Management Process Docs

Welcome to the OctoAcme Project Management documentation suite. These guides provide standardized processes, templates, and best practices for running cross-functional projects that deliver product features, services, and integrations.

## Our Approach

OctoAcme projects are built on these core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

For a full overview, see [OctoAcme Project Management Overview](octoacme-project-management-overview.md).

## OctoAcme Project Management Process Overview

OctoAcme follows a structured, iterative project lifecycle centered on customer value and data-informed decisions. The process spans five key phases: **Initiation** (problem validation and stakeholder alignment), **Planning** (scope definition and backlog creation), **Execution** (build, test, and iterate), **Release** (deploy with verification), and **Close & Retrospective** (capture learnings). This lifecycle is grounded in clear ownership—each project has a dedicated Project Manager (PM) and Product Manager (PdM)—and emphasizes psychological safety, incremental delivery, and measurable outcomes. Success is defined upfront through a lightweight Project One-pager that articulates the problem statement, SMART goals, success metrics, and key stakeholders.

OctoAcme operates with well-defined personas: **Developers** implement features and maintain quality through code reviews and testing; **Product Managers** define the vision, prioritize the backlog, and validate solutions through data; and **Project Managers** coordinate delivery, manage risks, and facilitate cross-team communication. Communication follows a predictable cadence—daily standups (15 min), weekly PM + PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Escalation is structured across three levels: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Decision gates between phases ensure that only well-validated work moves forward (e.g., success metrics must be clear and stakeholder buy-in confirmed before entering planning).

During execution, teams use a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done) and follow lean pull request practices: small PRs (≤400 lines), automated CI/linting, and at least one approval before merge. Quality assurance is built in from the start with unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning. Risk management is proactive—risks are identified during planning and ongoing execution, assessed by impact and likelihood, captured in a Risk Register with mitigation plans, and reviewed weekly. Dependencies are marked on the project board and escalated during syncs. Post-release, teams run smoke tests and post-deploy verifications; if issues arise, incident response and rollback procedures are triggered.

Every sprint, release, or milestone concludes with a structured retrospective (45–75 min) that captures what went well, areas for improvement, and 2–3 prioritized action items with clear owners and due dates. These action items feed back into the project backlog or become process improvements tracked in future syncs. Throughout the project, a single source of truth (README or release doc) maintains status, and weekly status templates ensure transparency on progress, next steps, risks, blockers, and decisions needed. This emphasis on reflection, transparent communication, and iterative refinement creates a culture where teams continuously learn and improve their delivery capabilities.

## Process Documentation

### Project Initiation
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a lightweight plan

### Planning & Preparation
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog

### Execution & Delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress toward milestones

### Release & Deployment
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production

### Risk & Communication
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

### Learning & Improvement
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Reference
- [OctoAcme Personas](octoacme-roles-and-personas.md) — Define typical roles and responsibilities used across OctoAcme projects

## Getting Started

1. **New to OctoAcme?** Start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow [Project Initiation Guide](octoacme-project-initiation.md)
3. **Looking for specific guidance?** Use the links above organized by project phase
