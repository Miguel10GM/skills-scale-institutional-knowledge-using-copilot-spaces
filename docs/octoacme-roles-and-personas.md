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

## Product Owner

### Role Summary
Product Owners act as the primary voice of the customer and stakeholder needs. They define, refine, and prioritize requirements while ensuring the team understands the business value of their work.

### Responsibilities
- Define and communicate product requirements and user stories
- Prioritize backlog items based on business value and stakeholder feedback
- Clarify acceptance criteria and definition of done
- Gather and incorporate feedback from stakeholders and end users
- Make scope and trade-off decisions in collaboration with the team
- Validate that delivered work meets stakeholder expectations

### Goals
- Ensure the team builds the right product
- Maximize stakeholder satisfaction and business value
- Reduce rework due to unclear requirements
- Enable efficient decision-making through clear prioritization

### Typical Communication
- Sprint planning and backlog refinement sessions
- User story discussions and requirement clarifications
- Stakeholder updates and feedback sessions
- Collaboration with PM, Developers, and QA on requirements

### Interaction Map
- **Works with Developers**: Clarifies requirements, accepts completed work, provides feedback
- **Works with Project Manager**: Aligns priorities with project timeline and resource constraints
- **Works with Quality Assurance Analyst**: Defines acceptance criteria and validates test coverage
- **Works with Risk Manager**: Communicates impact of scope changes and prioritizes risk mitigation efforts
- **Works with Deployment Engineer**: Coordinates feature rollout and beta testing schedules
- **Works with Stakeholders**: Gathers requirements and communicates delivery status

---

## Risk Manager

### Role Summary
Risk Managers proactively identify, assess, and mitigate project risks. They maintain risk visibility across the team and enable timely escalation and resolution of threats to project success.

### Responsibilities
- Identify and document potential project risks (technical, schedule, resource, external)
- Assess risk probability and impact using standardized frameworks
- Develop mitigation and contingency plans for high-priority risks
- Track risk status and ownership throughout the project lifecycle
- Facilitate risk review meetings and escalation protocols
- Communicate risk status to project leadership and stakeholders
- Conduct post-project risk retrospectives to inform future planning

### Goals
- Minimize unplanned disruptions to project delivery
- Ensure risks are visible and actively managed
- Build organizational risk management capability
- Enable confident decision-making despite uncertainty

### Typical Communication
- Risk register maintenance and updates
- Risk review meetings (weekly or bi-weekly)
- Escalation notifications to Project Manager and leadership
- Retrospective documentation and lessons learned

### Interaction Map
- **Works with Project Manager**: Reports on risk status, escalates critical risks, coordinates response plans
- **Works with Developers**: Identifies technical risks, gathers input on feasibility and dependencies
- **Works with Product Owner**: Communicates impact of risks on scope and schedule
- **Works with Quality Assurance Analyst**: Identifies quality and testing risks
- **Works with Deployment Engineer**: Manages deployment and rollback risks
- **Works with all team members**: Solicits risk inputs during planning and execution phases

---

## Quality Assurance Analyst

### Role Summary
Quality Assurance Analysts ensure that delivered software meets quality standards, acceptance criteria, and user expectations. They develop comprehensive test strategies and drive quality improvements throughout the development lifecycle.

### Responsibilities
- Develop test strategies and test plans aligned with requirements
- Create and maintain test cases covering functional, non-functional, and edge cases
- Execute manual and automated testing activities
- Document defects, track resolution, and verify fixes
- Participate in acceptance criteria definition and refinement
- Perform exploratory testing to identify unanticipated issues
- Report on quality metrics and testing coverage
- Advocate for quality standards and continuous improvement

### Goals
- Catch defects early and minimize production issues
- Ensure features meet acceptance criteria and user expectations
- Reduce rework and support costs through proactive testing
- Build confidence in release quality

### Typical Communication
- Sprint planning and acceptance criteria discussions
- Defect reports and quality status updates
- Test case documentation and test execution logs
- Release readiness assessments and sign-off

### Interaction Map
- **Works with Developers**: Reviews code for testability, verifies fixes, provides feedback on edge cases
- **Works with Product Owner**: Clarifies acceptance criteria, validates requirement understanding, confirms acceptance
- **Works with Project Manager**: Reports on testing status and quality blockers
- **Works with Deployment Engineer**: Performs release testing and validates deployment success
- **Works with Risk Manager**: Identifies quality-related risks and test coverage gaps

---

## Deployment Engineer

### Role Summary
Deployment Engineers manage the release, deployment, and operational aspects of software delivery. They ensure smooth transitions from development to production while maintaining system stability and supporting incident response.

### Responsibilities
- Design and maintain deployment pipelines and release procedures
- Coordinate release schedules and communication across teams
- Execute production deployments and monitor for issues
- Manage rollback procedures and incident response protocols
- Maintain environment consistency (dev, staging, production)
- Document deployment procedures and runbooks
- Collaborate on performance optimization and infrastructure improvements
- Support production issue diagnosis and resolution

### Goals
- Enable frequent, reliable deployments with minimal risk
- Minimize deployment-related incidents and downtime
- Maintain system stability and performance in production
- Reduce mean time to recovery (MTTR) for production issues

### Typical Communication
- Release planning and deployment scheduling meetings
- Deployment runbooks and procedures documentation
- Incident reports and post-mortem documentation
- Infrastructure and performance updates

### Interaction Map
- **Works with Developers**: Coordinates build artifacts, shares deployment feedback, supports troubleshooting
- **Works with Quality Assurance Analyst**: Performs release testing, validates deployment success
- **Works with Project Manager**: Communicates deployment readiness and schedule impact
- **Works with Product Owner**: Coordinates feature rollout and beta testing schedules
- **Works with Risk Manager**: Manages deployment risks and tests rollback procedures

---

## Cross-Functional Collaboration Matrix

| Role | Primary Dependencies | Key Touchpoints |
|------|----------------------|-----------------|
| **Developer** | Product Owner, QA, Project Manager | Requirements clarity, code review, testing feedback |
| **Product Manager** | Product Owner, Project Manager, Stakeholders | Roadmap, prioritization, metrics |
| **Project Manager** | All roles | Planning, status, risks, escalations |
| **Product Owner** | Developers, QA, Stakeholders | Requirements, acceptance, prioritization |
| **Risk Manager** | All roles | Risk identification, mitigation, escalation |
| **QA Analyst** | Developers, Product Owner, Deployment Engineer | Requirements, testing, deployment |
| **Deployment Engineer** | Developers, QA, Risk Manager | Build artifacts, release procedures, incidents |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the interaction maps to understand cross-functional dependencies and communication patterns.
- Use the collaboration matrix to identify stakeholders for decision-making and issue resolution.
