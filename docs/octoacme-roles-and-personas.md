# OctoAcme Roles and Personas

This document defines the delivery roles used in OctoAcme project documentation. Use it with the [RACI Matrix](octoacme-raci-matrix.md) and [Handoff Checklist](octoacme-handoff-checklist.md) when a team needs clearer ownership, sign-offs, or cross-functional coordination.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Key Interactions
- Align with Product Managers on acceptance criteria and scope trade-offs
- Partner with Project Managers on estimates, blockers, and delivery risks
- Coordinate with QA, UX, DevOps, and Security before release-critical changes ship

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Key Interactions
- Confirm priorities and release goals with Stakeholders and Sponsors
- Work with UX on user journeys and definition of done for experience quality
- Partner with Customer Support / Success and Stakeholders to validate outcomes after release

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Key Interactions
- Run delivery planning with Developers, QA, and Engineering Managers
- Escalate timeline and dependency risks to Product Managers and Sponsors early
- Use the handoff checklist to confirm readiness before each phase transition

---

## QA / Testing

### Role Summary
QA and Testing partners protect release quality by validating acceptance criteria, test coverage, and regression risk before changes reach customers.

### Responsibilities
- Define the test approach for each milestone or release
- Validate acceptance criteria, regressions, and release readiness
- Raise defects with clear reproduction steps and severity
- Confirm that sign-off evidence is captured before launch

### Goals
- Find issues early enough to avoid release delays
- Maintain confidence in critical user flows
- Keep quality expectations visible across the team

### Typical Communication
- Test plans linked from backlog items or release docs
- Defect triage in standups or dedicated QA review sessions
- Release go/no-go input shared with PM, PdM, and Developers

### Key Interactions
- Review acceptance criteria with Product Managers before implementation starts
- Coordinate with Developers on fixes, risk areas, and test data needs
- Partner with DevOps and Customer Support / Success during release verification and post-release monitoring

---

## Engineering Managers

### Role Summary
Engineering Managers align team capacity, technical execution health, and staffing plans so delivery commitments remain realistic and sustainable.

### Responsibilities
- Review capacity, staffing, and delivery risk during planning
- Coach engineers and help remove execution blockers
- Escalate staffing or technical debt concerns that threaten delivery
- Support cross-team coordination when shared systems are involved

### Goals
- Keep delivery plans achievable for the team
- Protect engineering quality and sustainable pace
- Reduce execution risk caused by staffing or ownership gaps

### Typical Communication
- Weekly delivery and staffing reviews with PM and PdM
- One-on-ones and team health check-ins with engineers
- Escalation discussions for dependency or capacity risk

### Key Interactions
- Align commitments with Project Managers before timelines are finalized
- Work with Product Managers on scope trade-offs when capacity changes
- Support Developers, DevOps, and Security when technical risk needs leadership attention

---

## UX / UI Designers

### Role Summary
UX and UI Designers ensure the team builds usable, accessible, and coherent experiences that match customer needs and product intent.

### Responsibilities
- Create user flows, wireframes, prototypes, and interaction guidance
- Validate usability and accessibility requirements
- Provide design assets and clarify intended behaviors for implementation
- Participate in review cycles for high-impact user journeys

### Goals
- Reduce ambiguity in user experience decisions
- Improve usability, accessibility, and consistency
- Catch experience issues before engineering rework is required

### Typical Communication
- Design reviews during planning and feature discovery
- Annotated mocks or prototypes linked in backlog items
- Implementation check-ins with Developers and QA

### Key Interactions
- Partner with Product Managers to translate requirements into user journeys
- Support Developers with implementation detail and edge-case behavior
- Coordinate with QA on usability and accessibility checks before release

---

## DevOps / Platform Engineers

### Role Summary
DevOps and Platform Engineers maintain deployment safety, environment readiness, observability, and the reliability of the delivery pipeline.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Prepare environments, rollout plans, and rollback steps
- Ensure monitoring, alerting, and operational runbooks are in place
- Identify infrastructure or operational risks early in planning

### Goals
- Keep deployments safe, repeatable, and observable
- Reduce release friction caused by environment instability
- Improve recovery time when incidents occur

### Typical Communication
- Release planning and readiness reviews
- Pipeline updates, runbooks, and deployment notes
- Incident channels and post-release monitoring summaries

### Key Interactions
- Coordinate with Developers on build, environment, and runtime requirements
- Confirm release timing and rollback ownership with Project Managers
- Work with Security and Customer Support / Success on incident response readiness

---

## Security Engineers

### Role Summary
Security Engineers integrate security review, threat awareness, and control validation into the delivery lifecycle.

### Responsibilities
- Review architecture or feature changes for security risk
- Support threat modeling and control selection
- Triage vulnerabilities and advise on remediation priorities
- Confirm security-sensitive releases meet required checks

### Goals
- Reduce avoidable security risk before release
- Make security review predictable and early
- Improve response quality for security defects or incidents

### Typical Communication
- Security review notes linked from backlog items or design docs
- Vulnerability triage with Developers and Engineering Managers
- Release gate input for high-risk or sensitive changes

### Key Interactions
- Partner with Developers during implementation of sensitive features
- Work with Project Managers to surface security risks in planning and escalation
- Coordinate with DevOps during incident readiness and post-release monitoring

---

## Customer Support / Success Representatives

### Role Summary
Customer Support and Success representatives bring customer-impact insight into planning, launch readiness, and post-release follow-up.

### Responsibilities
- Share common support pain points and customer feedback themes
- Review launch communications and support readiness materials
- Escalate field issues quickly after release
- Help teams understand customer-facing impact during incidents

### Goals
- Reduce surprise for support teams during launches
- Improve customer communication quality and timing
- Shorten time to identify real-world issues after release

### Typical Communication
- Support-readiness reviews before release
- Post-release summaries of ticket trends and customer feedback
- Stakeholder updates when customer impact changes

### Key Interactions
- Inform Product Managers about recurring customer pain points
- Coordinate with Project Managers on launch communication timing
- Partner with Developers and QA to reproduce customer-reported issues

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide strategic direction, funding, approvals, and business context for major project decisions.

### Responsibilities
- Approve objectives, budgets, or major scope changes when required
- Provide business context, constraints, and success criteria
- Review milestone progress and unblock high-impact escalations
- Support prioritization when trade-offs affect business commitments

### Goals
- Ensure work aligns with business priorities and customer commitments
- Maintain visibility into delivery health and major risks
- Enable fast decisions when escalations are needed

### Typical Communication
- Monthly status reviews and milestone readouts
- Decision logs for scope, priority, or timeline changes
- Escalation updates when risks affect delivery commitments

### Key Interactions
- Align with Product Managers on objectives and success metrics
- Rely on Project Managers for timeline, status, and risk visibility
- Participate in go/no-go decisions when release risk or scope changes are material

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Use the [RACI Matrix](octoacme-raci-matrix.md) when ownership or sign-off is unclear.
- Use the [Handoff Checklist](octoacme-handoff-checklist.md) before moving work between planning, execution, release, and support.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
