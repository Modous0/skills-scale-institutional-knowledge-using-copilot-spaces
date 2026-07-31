# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains the official process guides that govern how OctoAcme plans, executes, and continuously improves its projects.

## About OctoAcme's Project Management Process

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Each new initiative begins with a lightweight Project One-pager that defines the problem statement, SMART objectives, success metrics, and key stakeholders. A formal decision gate ensures that work only advances into planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. Planning then translates that approved initiative into an actionable backlog — with prioritized items, T-shirt sizing or story point estimates, a defined Definition of Done, and a milestone map — so the entire delivery team starts with shared expectations and a clear scope.

Three distinct **personas** drive execution: the **Project Manager (PM)**, who coordinates schedules, risks, and cross-team communication; the **Product Manager (PdM)**, who owns the product vision, prioritizes the backlog, and measures outcomes; and **Developers**, who implement features, write tests, and participate in design and code reviews. Supporting roles include QA/Testing and Stakeholders. This clear ownership model — every project has a named PM and Product Lead — reduces ambiguity and prevents single-person dependency risk. Together, these roles operate against a predictable **communication cadence**: daily standups (15 min), weekly delivery syncs, bi-weekly PM–PdM alignment, monthly stakeholder updates, and ad-hoc escalations when blockers arise.

**Quality assurance and execution tracking** are embedded throughout delivery rather than treated as a final gate. Teams use GitHub Projects boards (Backlog → Ready → In Progress → In Review → QA → Done) to maintain visibility, and pull requests are kept small (≤ 400 lines where possible), linked to issues, and gated on CI passing (tests, linting, security scans) plus at least one peer approval. Velocity and burndown are tracked continuously, and risks are captured in a living Risk Register with impact, likelihood, owner, and mitigation plan — reviewed weekly and escalated through a three-level path (Team → PM/Product Lead → Sponsor) as needed.

After each sprint, release, or milestone, OctoAcme runs a **structured retrospective** (45–75 min) covering what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. Those action items flow directly back into the project backlog or issues, closing the continuous improvement loop. Releases themselves follow a standardized checklist — staging smoke tests, automated production pipelines, post-deploy verification, and stakeholder announcements — with a documented rollback plan ready for every deployment. Together, these practices create a repeatable, transparent, and continuously improving delivery system grounded in customer value and iterative progress.

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management methodology |
| [Project Initiation](octoacme-project-initiation.md) | Steps and artifacts for initiating a new project |
| [Project Planning](octoacme-project-planning.md) | Planning processes, timelines, and resource allocation |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Guidelines for executing work and tracking progress |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk management and stakeholder communication strategies |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release planning and deployment procedures |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective process and improvement practices |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of roles and responsibilities across projects |
