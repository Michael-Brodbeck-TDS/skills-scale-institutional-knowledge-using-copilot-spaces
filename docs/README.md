# OctoAcme Project Management Documentation

Overview

OctoAcme runs projects with an iterative, outcomes-focused approach that begins with a lightweight initiation and moves through planning, execution, release, and retrospective phases. Work is organized on a project board with clear workflow columns (Backlog → Ready → In Progress → In Review → QA → Done) and a prioritized backlog of shippable increments. Planning turns approved initiatives into a release plan and sprint backlog with acceptance criteria, estimates, and a documented Definition of Done; teams use timeboxed sprint planning to pull work that meets capacity and DoD.

Responsibility and decision-making are explicit: each project names a Project Manager (PM) and a Product Manager (PdM), and includes developers, QA, and stakeholders with defined responsibilities. PMs coordinate delivery, schedules, risks, and communications; PdMs own outcomes, success metrics, and prioritization; developers implement and test; QA validates acceptance criteria. Persona guidance clarifies handoffs and accountability across the lifecycle.

Communication is regular and structured: short daily standups for progress and blockers, weekly delivery syncs and PM–PdM alignment meetings, and monthly stakeholder updates. The docs define escalation paths (team → PM → Product Lead → Sponsor) and provide templates for weekly status and incident communications. A simple risk register is maintained and reviewed regularly; cross-team dependencies are tracked on the project board and escalated during syncs.

Quality and release controls are integrated into the workflow. Pull requests should be small, include issue links and acceptance criteria, run CI (tests, lint, and security scans) before review, and require approvals before merging. Testing expectations include unit and integration tests and end-to-end smoke tests for critical flows; manual QA is applied when needed. Releases follow a checklist (staging smoke tests, automated production deploys where possible, post-deploy verification) and include rollback/incident playbooks and release notes templates to reduce operational risk.

---

Table of contents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

Key artifacts and quick links

- Project One-pager / Charter
- Prioritized backlog with acceptance criteria
- Sprint/iteration plans and Definition of Done
- Risk register and mitigation plans
- Release notes and deployment checklists
- Retrospective notes and action items

Communication cadence (quick reference)

- Daily: team standups
- Weekly: PM + PdM sync, delivery syncs, stakeholder updates
- Per sprint/milestone: planning, demos/reviews, retrospectives
- As needed: incident communication and escalations

Getting help

1. Open the relevant doc above.
2. Check the Execution Checklist or related guidance in that doc.
3. If unresolved, reach out to the Project Manager or Product Lead for the initiative.
