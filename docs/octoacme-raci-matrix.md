# OctoAcme — RACI Matrix

## Purpose
Provide a ready-to-use accountability reference for the most common project management decisions, approvals, and handoffs.

## How to use this document
- Copy the table into a project charter, kickoff note, or release plan.
- Replace role names with named people for the current project.
- Review the matrix during kickoff and whenever scope, staffing, or risk changes.
- Pair this matrix with the [Roles and Personas](octoacme-roles-and-personas.md) and [Handoff Checklist](octoacme-handoff-checklist.md).

## RACI Legend
- **R — Responsible:** completes the work.
- **A — Accountable:** owns the final decision or outcome.
- **C — Consulted:** gives input before the decision is finalized.
- **I — Informed:** kept up to date on the outcome.

## Core Project Activities

| Activity | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Project charter / one-pager | Project Manager | Product Manager | Stakeholders / Sponsors, Engineering Manager | Delivery team |
| Success metrics definition | Product Manager | Product Manager | Customer Support / Success, Stakeholders / Sponsors | Project Manager, Delivery team |
| Delivery timeline and milestone plan | Project Manager | Project Manager | Product Manager, Engineering Manager, DevOps / Platform Engineer | Stakeholders / Sponsors, Delivery team |
| Backlog prioritization | Product Manager | Product Manager | Project Manager, Engineering Manager, UX / UI Designer | Delivery team, Stakeholders / Sponsors |
| UX and acceptance criteria readiness | UX / UI Designer | Product Manager | Developers, QA / Testing | Project Manager |
| Test strategy and release sign-off evidence | QA / Testing | QA / Testing | Developers, Product Manager, DevOps / Platform Engineer | Project Manager, Stakeholders / Sponsors |
| Security review for sensitive changes | Security Engineer | Security Engineer | Developers, DevOps / Platform Engineer, Engineering Manager | Project Manager, Product Manager |
| Deployment execution and rollback readiness | DevOps / Platform Engineer | DevOps / Platform Engineer | Developers, QA / Testing, Project Manager | Product Manager, Customer Support / Success |
| Customer communication for launch or incident | Customer Support / Success Representative | Product Manager | Project Manager, Stakeholders / Sponsors | Delivery team |
| Retrospective action items | Project Manager | Project Manager | Product Manager, Engineering Manager, Delivery team | Stakeholders / Sponsors |

## Decision Checkpoints

| Trigger | Required owner action | Typical approvers / consulted roles |
|---|---|---|
| Scope increases after planning sign-off | Update plan, timeline, and risk register before accepting work | Product Manager, Project Manager, Engineering Manager |
| Release date changes | Publish updated timeline and impact summary within the same working day | Project Manager, Product Manager, Stakeholders / Sponsors |
| High-severity defect near release | Pause go/no-go decision until defect owner and mitigation are named | QA / Testing, Developers, Project Manager |
| Security-sensitive change | Confirm security review outcome before merge or deployment | Security Engineer, Developers, DevOps / Platform Engineer |
| Customer-facing incident | Name an incident lead and communications owner immediately | Project Manager, DevOps / Platform Engineer, Customer Support / Success |

## Meeting Ownership Guide
- **Kickoff:** PM owns agenda, PdM owns problem statement, Engineering Manager confirms staffing assumptions.
- **Planning / estimation:** PM facilitates, PdM confirms priority, Developers and QA confirm delivery/test assumptions.
- **Release readiness:** PM confirms checklist completion, QA confirms quality status, DevOps confirms deployment readiness.
- **Stakeholder update:** PM reports status and risks, PdM reports outcomes and trade-offs, Sponsor confirms key decisions if needed.
