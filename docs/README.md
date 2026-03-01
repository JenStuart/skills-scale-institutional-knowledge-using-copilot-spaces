# OctoAcme Project Management — Documentation Hub

Welcome to the OctoAcme project management docs. This README is the entry point for new team members and stakeholders who want to understand how we deliver software — consistently, collaboratively, and with a focus on customer value.

---

## Our Approach

OctoAcme uses a structured yet flexible delivery model that scales across small features and large cross-functional initiatives. Every project follows a clear lifecycle, maintains shared ownership, and continuously improves based on data and retrospectives.

### Five Core Principles

| Principle | What it means in practice |
|---|---|
| **Customer-first delivery** | Prioritize customer value and usability in every decision |
| **Iterative releases** | Deliver small, testable increments rather than big-bang releases |
| **Clear ownership** | Every project has a named Project Manager (PM) and Product Lead |
| **Data-informed decisions** | Measure impact and iterate based on evidence, not assumptions |
| **Psychological safety** | Encourage candid feedback, learning from failures, and open communication |

---

## Project Lifecycle

Projects move through five phases. Each phase has defined goals, deliverables, and a decision gate before moving forward.

| Phase | Key activities | Primary owners |
|---|---|---|
| **Initiation** | Define problem statement, identify stakeholders, set success metrics, go/no-go decision | PM, Product Manager |
| **Planning** | Kickoff, prioritized backlog, release plan, Definition of Done, risk register | PM, Developers, QA |
| **Execution** | Build, test, review, iterate in sprints; daily standups; blocker escalation | Developers, QA, PM |
| **Release** | Staging smoke tests, production deploy, post-deploy verification, stakeholder announcement | PM, Developers |
| **Closure** | Retrospective, capture learnings, action items, project sign-off | Whole team |

---

## Core Roles

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and cross-team communication |
| **Product Manager (PdM)** | Defines outcomes, prioritizes the backlog, measures success |
| **Developers** | Implement features, write tests, participate in code and design reviews |
| **QA / Testing** | Validate quality and acceptance criteria, run smoke tests before release |
| **Stakeholders** | Provide inputs, approvals, and strategic direction |

---

## Communication Cadence

| Touchpoint | Frequency | Participants |
|---|---|---|
| Daily standup | Daily (15 min) | Delivery team |
| PM + PdM sync | Weekly | PM, Product Manager |
| Stakeholder update | Monthly (or milestone-based) | PM, stakeholders |
| Sprint demo / review | End of each sprint | Full team + stakeholders |
| Retrospective | After each sprint, release, or incident | Whole team |
| Ad-hoc escalations | As needed | PM → Product Lead → Sponsor |

For incident and weekly status communication templates, see [Risk Management & Communication](./octoacme-risks-and-communication.md).

---

## Quality Assurance & Testing

- **Unit tests** for all new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before every release
- **Security scanning** in CI on every pull request
- **Manual QA** for feature acceptance when automated coverage is insufficient
- Pull requests are kept small (≤ 400 lines where possible), include linked acceptance criteria, and require at least one approval before merging

---

## Key Artifacts

- **Project One-pager** — problem statement, goals, and success metrics
- **Roadmap & Release Plan** — milestones and delivery timeline
- **Sprint / Iteration Backlog** — prioritized, estimated work items with acceptance criteria
- **Definition of Done (DoD)** — shared quality bar for completing any work item
- **Risk Register** — ID, impact, likelihood, owner, mitigation, and status
- **Retrospective notes** — learnings and action items with owners and due dates

---

## Process Documentation

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level summary of OctoAcme's PM approach, principles, and artifacts |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each project role |
| [Project Initiation](./octoacme-project-initiation.md) | How to validate, authorize, and kick off new work |
| [Project Planning](./octoacme-project-planning.md) | Backlog creation, estimation, release planning, and Definition of Done |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day workflows, PR conventions, metrics, and blocker escalation |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, pre-release checklist, rollback playbook, and release notes |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, stakeholder communication, escalation paths |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, tracking action items, and building an improvement culture |

---

> **New here?** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then explore the phase-specific guides that are most relevant to your current project stage.
