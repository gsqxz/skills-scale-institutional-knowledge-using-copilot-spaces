# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management documentation! This folder contains everything you need to understand how we plan, execute, and deliver projects. Whether you're a new team member or looking to refresh your knowledge, this is your starting point.

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. Our methodology spans five distinct phases — **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective** — ensuring that every project begins with a validated business case, progresses with transparency, and concludes with organizational learning.

Projects begin at **Initiation**, where we establish the business need through a lightweight one-pager that captures the problem statement, success metrics, and stakeholder alignment. Work then moves to **Planning**, where scope is broken into shippable increments with a prioritized backlog and clear acceptance criteria. During **Execution**, delivery teams run twice-weekly standups, conduct PR reviews, and rely on continuous integration to keep quality high. The **Release** phase uses staged deployments with rollback plans and smoke tests to minimize risk. Finally, the **Close & Retrospective** phase captures learnings and feeds them back into process improvement for future projects.

---

## Roles & Personas

OctoAcme defines clear roles to prevent ambiguity and ensure accountability at every level:

| Role | Responsibility |
|---|---|
| **Product Manager** | Owns the product vision, prioritizes the backlog, and measures outcomes through success metrics |
| **Project Manager** | Coordinates delivery activities, manages risks and dependencies, and maintains stakeholder communication |
| **Developers** | Implement features to acceptance criteria while maintaining high test coverage and code quality |
| **QA/Testing** | Validates quality and ensures acceptance criteria are met before release |

Each project has a named **Project Manager** and **Product Lead** to provide clear ownership throughout the lifecycle.

---

## Communication Cadence

Keeping everyone aligned is critical. OctoAcme maintains the following communication rhythm:

- **Twice-weekly standups** — delivery teams sync on progress, blockers, and next steps
- **Weekly PM + Product Manager sync** — alignment on priorities, risks, and roadmap
- **Monthly stakeholder updates** — broad updates on project status and outcomes
- **Ad-hoc escalations** — as needed for blockers or incidents

Escalation follows a clear path: **Team → Project Manager → Product Lead → Sponsor**, ensuring issues surface quickly and reach the right decision-makers without delay.

---

## Quality Assurance Practices

Quality is built into every stage of delivery:

- **Small pull requests** (≤ 400 lines) to keep reviews focused and manageable
- **At least one approval** required before any PR is merged
- **Automated testing and linting** run on every commit via CI/CD
- **Security scanning** as part of the pre-release checklist
- **Smoke tests** verify critical flows after each deployment

Before a release, all acceptance criteria must be met, CI/CD must pass including security scans, release notes must be drafted, and a rollback plan must be documented.

---

## Risk Management

Risk management is proactive at OctoAcme:

1. **Identify** risks during planning and throughout execution
2. **Assess** impact (High/Med/Low) and likelihood (High/Med/Low)
3. **Mitigate** through documented action plans and contingency options
4. **Monitor** status at weekly syncs and update the Risk Register accordingly

---

## Continuous Improvement

After every sprint or milestone, teams hold a **retrospective** to capture:

- What went well
- What could be improved
- Actionable next steps with clear owners and due dates

This commitment to measurement, iterative refinement, and psychological safety creates a culture where teams continuously optimize delivery while maintaining high standards of quality and stakeholder trust.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation](./octoacme-project-initiation.md) | How to kick off a project with a one-pager and stakeholder alignment |
| [Project Planning](./octoacme-project-planning.md) | Scope, backlog, milestones, and acceptance criteria |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Standups, PR reviews, CI/CD, and sprint tracking |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk Register, escalation paths, and communication templates |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | How we capture learnings and drive process improvement |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities for each role on a delivery team |

---

> **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to get a high-level picture, then explore the phase-specific documents as you need them. Welcome to the team! 🎉
