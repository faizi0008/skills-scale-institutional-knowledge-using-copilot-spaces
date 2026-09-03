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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality strategies, validate acceptance criteria, and ensure products meet reliability and usability standards before release. They are essential to maintaining product quality throughout the delivery lifecycle.

### Responsibilities
- Develop comprehensive test plans aligned with product features and acceptance criteria
- Lead and execute testing activities (manual, automated, integration, performance, security)
- Validate acceptance criteria before marking work as done
- Identify, document, and track defects with clear reproduction steps and severity levels
- Ensure CI/CD test coverage meets team standards and identify gaps
- Participate in release readiness reviews and gate decisions
- Collaborate with developers on testability and test-driven development practices
- Maintain quality metrics dashboards and trend reporting

### Goals
- Prevent defects from reaching production through proactive testing
- Enable fast, confident releases through robust, comprehensive test coverage
- Maintain transparent quality metrics and data-driven quality reporting
- Build a culture of shared quality ownership across the team

### Typical Communication
- Daily standups and sprint planning (quality perspective)
- QA review gates during PR and release processes
- Defect reports with actionable severity and reproduction guidance
- Quality metrics dashboards and trend analysis in weekly syncs
- Collaboration with developers on test strategy and acceptance criteria refinement

### Key Interactions
- **With Developers:** Review code for testability, collaborate on unit test coverage, validate acceptance criteria
- **With Product Managers:** Align on quality expectations, interpret acceptance criteria, surface quality trade-offs
- **With Project Managers:** Report on quality blockers, provide input on release readiness decisions
- **With Technical Product Owners:** Clarify non-functional requirements (performance, reliability, security)

---

## Technical Product Owner

### Role Summary
Technical Product Owners bridge engineering and product leadership by clarifying technical feasibility, guiding architectural decisions, and ensuring solutions scale reliably. They ensure long-term technical health while delivering customer value.

### Responsibilities
- Assess technical feasibility of product requirements and propose alternatives when needed
- Guide architecture and design decisions with long-term maintainability and scalability in mind
- Support developers in understanding and implementing non-functional requirements (performance, security, scalability, reliability)
- Collaborate with Product Managers on trade-offs between scope, quality, and technical debt
- Advocate for engineering quality, refactoring needs, and infrastructure investments
- Review and approve technical designs and architectural decisions
- Identify and escalate technical risks and dependencies early in planning
- Support capacity planning and velocity management based on technical complexity

### Goals
- Ensure products are built with technical excellence and long-term sustainability
- Reduce future technical debt through informed decisions and early intervention
- Enable sustainable delivery pace and predictable team velocity
- Foster knowledge sharing and continuous technical improvement across the team

### Typical Communication
- Technical design reviews and architecture discussions
- Weekly PM + Engineering alignment sessions (trade-offs, feasibility)
- Acceptance criteria refinement for technical acceptance and non-functional requirements
- Risk registers and dependency mapping with technical context
- Code review for architectural alignment and best practices

### Key Interactions
- **With Developers:** Provide technical guidance, review designs, support problem-solving
- **With Product Managers:** Advise on feasibility, scope trade-offs, and complexity implications
- **With Project Managers:** Identify technical risks and dependencies affecting schedules
- **With QA/Testing Leads:** Clarify non-functional requirements and testing strategies

---

## Scrum Master / Delivery Facilitator

### Role Summary
Delivery Facilitators enable agile teams by running ceremonies, removing process blockers, and fostering a high-performing, self-organizing culture. They are coaches and enablers focused on maximizing team effectiveness and predictability.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, retrospectives, and backlog refinement sessions
- Identify, escalate, and help remove process impediments and blockers affecting team progress
- Coach team members on agile practices, sprint discipline, and sustainable pace
- Maintain and communicate project velocity metrics, burndown charts, and health dashboards
- Coordinate dependencies across teams and facilitate cross-team communication
- Support continuous improvement initiatives based on retrospective feedback
- Help the team maintain psychological safety and foster a learning culture
- Track and report on sprint health, capacity, and risks to Project Manager

### Goals
- Maximize team velocity and predictability in delivery
- Build psychological safety and a continuous learning culture within the team
- Reduce time spent in unproductive meetings or unblocked/dependent work
- Strengthen team cohesion and self-organization capabilities

### Typical Communication
- Daily standup facilitation and blocker resolution
- Weekly sprint retrospectives and planning sessions
- Velocity and burndown metrics dashboards
- Escalation of process blockers to Project Manager
- One-on-one coaching with team members as needed

### Key Interactions
- **With Developers:** Remove blockers, facilitate ceremonies, coach on practices
- **With Project Managers:** Escalate schedule risks, report on team health and capacity
- **With Product Managers:** Facilitate backlog refinement and prioritization sessions
- **With all roles:** Foster collaboration and psychological safety

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business direction, secure resources, and maintain executive alignment on project outcomes and priorities. They are key decision-makers and enablers at the organizational level.

### Responsibilities
- Approve project charter, success metrics, and business case
- Provide business context, strategic alignment, and competitive landscape insight
- Remove organizational blockers and secure necessary resources (budget, headcount, access)
- Review and approve major release decisions and go/no-go gates
- Serve as escalation point for business-impacting issues and decisions
- Communicate project status, outcomes, and impact to broader leadership
- Represent business priorities in trade-off discussions
- Review project outcomes against success metrics and provide feedback

### Goals
- Ensure projects deliver measurable business value and strategic alignment
- Maintain alignment across competing organizational priorities and initiatives
- Enable rapid escalation resolution and resource provisioning when needed
- Facilitate stakeholder feedback and course correction

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Release approval gates and go/no-go decision meetings
- Ad-hoc escalation and decision requests
- Executive briefings on project status and impact
- Post-release retrospectives and outcome validation

### Key Interactions
- **With Project Managers:** Approve plans, provide strategic direction, receive status updates
- **With Product Managers:** Align on business priorities, approve success metrics
- **With Delivery Team (via PM/PdM):** Make or delegate approval decisions, remove blockers
- **With Executive Leadership:** Communicate outcomes and impact

---

## Cross-Role Collaboration Map

| Interaction | Primary Context | Key Outcome |
|---|---|---|
| **Developer ↔ QA Lead** | Code review, acceptance criteria validation, test strategy | High quality, testable code |
| **Developer ↔ Tech Product Owner** | Technical design, architecture decisions, non-functional requirements | Scalable, maintainable solutions |
| **Product Manager ↔ Tech Product Owner** | Trade-off analysis, scope vs. complexity, feasibility | Realistic roadmaps and commitments |
| **QA Lead ↔ Tech Product Owner** | Performance/security/reliability requirements, test strategy | Comprehensive quality coverage |
| **Delivery Facilitator ↔ Project Manager** | Risk escalation, velocity tracking, blocker resolution | Predictable delivery, team health |
| **Project Manager ↔ Stakeholder** | Approvals, status updates, escalations, resource decisions | Strategic alignment, unblocked execution |
| **All Roles ↔ Delivery Facilitator** | Agile ceremonies, process improvement, continuous learning | High-performing, cohesive team |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the cross-role collaboration map when designing workflows or identifying communication gaps.
- Apply these personas consistently across all OctoAcme process documentation for coherent onboarding and training.
