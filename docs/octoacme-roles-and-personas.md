# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

---

## UX / Product Designer

### Role Summary
UX / Product Designers shape end-to-end user experience, interaction patterns, and visual direction so delivered solutions are usable, accessible, and aligned to product outcomes.

### Responsibilities
- Lead discovery activities during project initiation to clarify user problems and constraints
- Translate requirements into user flows, wireframes, prototypes, and design specifications during planning
- Partner with Developers during execution to ensure implementation matches intended UX and accessibility goals
- Support release readiness with usability checks, design QA, and known trade-off documentation
- Contribute to retrospectives and continuous improvement with design-system and workflow feedback

### Goals
- Improve user satisfaction, task success, and accessibility outcomes
- Reduce UX rework by validating assumptions early
- Keep experience consistency across releases

### Typical Communication
- Design reviews, prototype walkthroughs, and async design comments
- Requirement clarification with Product Managers and Developers
- Stakeholder demos focused on user journeys and usability outcomes

### Expected Artifacts / Outputs
- Personas, journey maps, user flows, wireframes, and prototypes
- UI specifications, accessibility notes, and design QA feedback
- Usability findings and prioritized UX improvements

### Decision Rights / Approval Boundaries
- Owns interaction and visual design recommendations within agreed product scope
- Approves design readiness before implementation begins
- Escalates unresolved usability or accessibility risks to Product Managers and Project Managers for trade-off decisions

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Clarifies UX intent, reviews implementation fidelity, and resolves design constraints during execution and release
- **Product Managers:** Aligns design direction to problem statements, success metrics, and backlog priorities
- **Project Managers:** Coordinates design milestones, dependencies, and risk visibility across planning and delivery

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects define and guide the technical approach so solutions are scalable, maintainable, secure, and feasible within delivery constraints.

### Responsibilities
- Shape solution architecture and technical options during initiation and planning
- Break down high-risk work, set engineering standards, and guide estimation
- Support execution with design reviews, dependency management, and unblock decisions
- Validate operational and architectural readiness before release
- Drive post-release technical improvements and debt reduction priorities

### Goals
- Deliver resilient architecture that supports current and future roadmap needs
- Reduce technical risk and unplanned rework
- Improve delivery predictability through clear technical direction

### Typical Communication
- Architecture reviews, RFCs, and technical decision logs
- Engineering syncs with Developers and cross-functional leads
- Risk and dependency updates for Product Managers and Project Managers

### Expected Artifacts / Outputs
- Architecture diagrams, technical design docs, and standards/guidelines
- Build-vs-buy assessments and technical risk assessments
- Technical decision records and rollout/rollback considerations

### Decision Rights / Approval Boundaries
- Recommends and approves technical design patterns and engineering standards
- Approves technical readiness for major milestones and release gates
- Escalates scope or timeline impacts from technical constraints to Product Managers and Project Managers

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Provides implementation guidance, resolves technical blockers, and reviews design quality
- **Product Managers:** Aligns solution choices with product priorities, trade-offs, and long-term value
- **Project Managers:** Aligns technical dependencies, sequencing, and risk mitigation with project plans

---

## QA / Test Lead

### Role Summary
QA / Test Leads define and coordinate quality strategy to ensure features meet functional, non-functional, and release-quality expectations.

### Responsibilities
- Define test strategy, scope, and quality criteria during planning
- Collaborate with Developers to integrate automated and manual testing throughout execution
- Track defect trends, test coverage, and quality risk before release
- Coordinate go/no-go quality input and post-release validation activities
- Lead quality-focused retrospectives and process improvements

### Goals
- Prevent critical defects from reaching production
- Improve confidence in release readiness
- Shorten defect feedback loops and rework cycles

### Typical Communication
- Test plan reviews and QA status updates
- Defect triage meetings and risk escalations
- Release readiness check-ins with product and project leadership

### Expected Artifacts / Outputs
- Test strategy, test plans, and test case coverage summaries
- Defect reports, quality dashboards, and release quality assessments
- Post-release quality findings and improvement recommendations

### Decision Rights / Approval Boundaries
- Defines testing scope and quality entry/exit criteria
- Recommends release hold when critical quality criteria are not met
- Escalates unresolved quality risks to Product Managers and Project Managers for final business trade-off decisions

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Aligns on testability, automation approach, and defect resolution priorities
- **Product Managers:** Confirms acceptance quality expectations and user-impact severity of defects
- **Project Managers:** Coordinates testing timelines, defect risk tracking, and release readiness communications

---

## Security / Privacy Partner

### Role Summary
Security / Privacy Partners guide secure and privacy-aware delivery practices so products meet policy, compliance, and risk expectations across the lifecycle.

### Responsibilities
- Identify security and privacy requirements during initiation and planning
- Support threat modeling, data classification, and control definition
- Partner during execution on secure design reviews, vulnerability handling, and privacy-by-design implementation
- Review release readiness for security/privacy controls and incident response preparedness
- Contribute to risk reviews and continuous improvement of secure delivery practices

### Goals
- Reduce exploitable vulnerabilities and privacy risk exposure
- Ensure compliance with applicable security and privacy obligations
- Improve team capability to address security/privacy early

### Typical Communication
- Security and privacy review sessions
- Risk register updates and mitigation tracking
- Incident and escalation communication with delivery leadership

### Expected Artifacts / Outputs
- Threat models, privacy impact notes, and control recommendations
- Security/privacy risk assessments and remediation tracking
- Release security sign-off input and incident lessons learned

### Decision Rights / Approval Boundaries
- Defines required security/privacy controls and review expectations
- Can require remediation or documented exception for high-risk findings
- Escalates unresolved high-risk issues to Product Managers and Project Managers for formal acceptance decisions

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Advises on secure implementation patterns, code/data handling, and remediation priorities
- **Product Managers:** Aligns risk treatment with customer impact, compliance needs, and product priorities
- **Project Managers:** Integrates security/privacy checkpoints, dependencies, and escalations into delivery plans

---

## DevOps / Site Reliability / Operations

### Role Summary
DevOps / SRE / Operations roles enable reliable build, deployment, runtime operations, and service resilience across delivery and production environments.

### Responsibilities
- Define environment, deployment, and observability needs during planning
- Support execution with CI/CD reliability, infrastructure readiness, and operational automation
- Validate release readiness, rollback plans, and production support coverage
- Monitor production health, incidents, and service-level objectives after release
- Drive operational improvements through post-incident and retrospective actions

### Goals
- Increase deployment reliability and operational stability
- Reduce mean time to detect and recover from incidents
- Improve confidence in release and rollback processes

### Typical Communication
- Release readiness and change-management coordination
- Incident channels, post-incident reviews, and reliability updates
- Infrastructure and performance planning discussions

### Expected Artifacts / Outputs
- Deployment pipelines, runbooks, and operational checklists
- Monitoring dashboards, alert definitions, and incident reports
- Capacity/reliability assessments and recovery test outcomes

### Decision Rights / Approval Boundaries
- Owns operational standards for deployment, monitoring, and incident response
- Can block or delay release when operational readiness criteria are not met
- Escalates capacity, reliability, or environment risks to Product Managers and Project Managers

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Collaborates on build/deploy automation, observability, and production support handoffs
- **Product Managers:** Aligns release windows and reliability trade-offs with customer impact
- **Project Managers:** Coordinates environment dependencies, operational milestones, and risk communication

---

## Customer Support / Service Operations Representative

### Role Summary
Customer Support / Service Operations Representatives bring customer-facing operational insight into planning and delivery and help ensure smooth release adoption.

### Responsibilities
- Provide customer issue trends and support constraints during initiation and planning
- Validate support readiness materials during execution
- Coordinate launch communications, escalation paths, and support playbooks for release
- Capture customer feedback and recurring incidents after release
- Feed service insights into risk reviews and continuous improvement planning

### Goals
- Improve customer experience during and after change rollout
- Reduce support escalation volume and resolution time
- Strengthen product decisions with real customer signals

### Typical Communication
- Support-readiness checkpoints and launch briefings
- Incident/escalation updates and customer-impact summaries
- Feedback loops with product and delivery teams

### Expected Artifacts / Outputs
- Support playbooks, known-issue logs, and FAQ/update drafts
- Customer-impact summaries and escalation reports
- Post-release support trend analysis and improvement suggestions

### Decision Rights / Approval Boundaries
- Recommends support-readiness criteria and customer communication content
- Can request release communication or rollout adjustments based on support risk
- Escalates high-impact customer concerns to Product Managers and Project Managers for final prioritization and scheduling decisions

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Shares reproducible issue patterns and helps prioritize support-driven fixes
- **Product Managers:** Provides customer pain-point evidence to inform backlog and release decisions
- **Project Managers:** Coordinates support readiness tasks, stakeholder updates, and escalation timing

---

## Business Analyst / Requirements Analyst

### Role Summary
Business Analysts / Requirements Analysts convert business needs into clear, testable, and traceable requirements that support planning, delivery, and validation.

### Responsibilities
- Elicit and structure stakeholder needs during project initiation
- Refine requirements, acceptance criteria, and process impacts during planning
- Maintain requirement traceability through execution and change requests
- Support release readiness by validating requirement coverage and business acceptance
- Contribute requirement-quality and process insights to retrospectives

### Goals
- Improve requirement clarity and reduce ambiguity-driven rework
- Ensure delivered scope maps to intended business outcomes
- Maintain shared understanding across technical and non-technical stakeholders

### Typical Communication
- Requirement workshops, backlog refinement, and walkthroughs
- Change impact discussions and scope clarification
- Business acceptance and stakeholder alignment sessions

### Expected Artifacts / Outputs
- Requirement documents, user stories, and acceptance criteria
- Process maps, traceability matrices, and change impact assessments
- Business acceptance summaries and open-question logs

### Decision Rights / Approval Boundaries
- Owns requirement clarity, traceability, and documentation quality
- Recommends requirement acceptance readiness for implementation
- Escalates conflicting requirements or unresolved scope decisions to Product Managers and Project Managers

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Clarifies detailed requirements, edge cases, and acceptance criteria interpretation
- **Product Managers:** Aligns requirement priorities and success criteria with product goals
- **Project Managers:** Supports scope governance, dependency tracking, and decision-log updates

---

## Data / Analytics Partner

### Role Summary
Data / Analytics Partners define and operationalize measurement so teams can make evidence-based decisions before, during, and after release.

### Responsibilities
- Define baseline metrics and measurement plans during initiation and planning
- Partner during execution to instrument events, validate data quality, and track experiment readiness
- Support release with KPI monitoring plans and adoption/performance dashboards
- Analyze post-release outcomes, risks, and anomalies
- Drive continuous improvement through metric-driven recommendations

### Goals
- Improve decision quality with trustworthy, timely insights
- Connect delivery outcomes to customer and business impact
- Reduce blind spots in risk, performance, and adoption trends

### Typical Communication
- Metric definition workshops and dashboard reviews
- Experiment and outcome readouts
- Stakeholder updates on KPI movement and insight-driven recommendations

### Expected Artifacts / Outputs
- Measurement plans, KPI definitions, and instrumentation requirements
- Dashboards, experiment analyses, and data quality checks
- Outcome reports and prioritized optimization opportunities

### Decision Rights / Approval Boundaries
- Owns metric definitions, tracking integrity expectations, and reporting standards
- Recommends experiment interpretation and performance/risk signals
- Escalates critical data quality or KPI risk concerns to Product Managers and Project Managers for prioritization and corrective action

### Interactions with Developers, Product Managers, and Project Managers
- **Developers:** Aligns instrumentation requirements, data validation, and telemetry implementation
- **Product Managers:** Links metrics to product hypotheses, roadmap decisions, and value outcomes
- **Project Managers:** Incorporates measurement milestones, reporting cadence, and risk escalation into project tracking

---

## Shared Collaboration and Accountability Notes
- Role assignments may vary by project size, team composition, and delivery model.
- A single person may cover multiple personas when capacity or scope requires it.
- Key decisions and deliverables should be validated with appropriate stakeholders before final approval.
- Shared accountability across roles supports initiation, planning, execution, release, risk management, stakeholder communication, and continuous improvement outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
