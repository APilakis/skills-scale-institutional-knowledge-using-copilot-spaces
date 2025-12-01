# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Related**: This documentation addresses the enhancements outlined in [Issue #4: Adding more personas and roles to the project management processes](https://github.com/APilakis/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).

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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance Lead oversees all testing activities, ensuring that deliverables meet acceptance criteria and quality standards. They work closely with Product Owners and Developers to define test strategies and validate product quality before release.

### Responsibilities
- Define and maintain comprehensive test strategies and test plans
- Oversee testing activities (unit, integration, end-to-end, performance)
- Ensure deliverables meet acceptance criteria before release
- Collaborate with Developers on testability and code quality
- Review and approve test coverage and quality metrics
- Coordinate with Release Manager on release readiness

### Goals
- Ensure high product quality and minimal defect leakage
- Establish consistent testing standards across teams
- Reduce time from bug discovery to resolution

### Typical Communication
- Weekly quality sync with Product Owner and Development Lead
- Test status reports and quality metrics dashboards
- Defect triage meetings and release readiness reviews

### Interactions with Existing Roles
| Role | Interaction |
|------|-------------|
| **Developers** | Collaborates on test coverage, reviews testing approaches, participates in bug triage |
| **Product Managers** | Validates acceptance criteria, reports on quality metrics, ensures feature meets requirements |
| **Project Managers** | Reports on testing progress, identifies testing-related risks, participates in release planning |

---

## Release Manager

### Role Summary
The Release Manager coordinates releases across teams, manages deployment timelines, and ensures smooth transitions from development to production. They collaborate with Operations and QA to deliver reliable, predictable releases.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate release activities across multiple teams
- Manage deployment timelines and release windows
- Ensure release readiness criteria are met before deployment
- Oversee rollback procedures and incident coordination during releases
- Maintain release documentation and communication

### Goals
- Deliver reliable, predictable releases
- Minimize deployment-related incidents and downtime
- Ensure clear communication around release status and changes

### Typical Communication
- Release planning meetings with cross-functional teams
- Deployment status updates and go/no-go decisions
- Post-release reviews and incident debriefs

### Interactions with Existing Roles
| Role | Interaction |
|------|-------------|
| **Developers** | Coordinates deployment activities, communicates release timelines, ensures code freeze compliance |
| **Product Managers** | Aligns release content with roadmap, communicates feature availability |
| **Project Managers** | Synchronizes release schedules with project milestones, escalates release risks |
| **Quality Assurance Lead** | Validates release readiness, coordinates final testing before deployment |

---

## Risk Champion

### Role Summary
The Risk Champion monitors project risks, leads mitigation activities, and interfaces with all role categories for escalation. They proactively identify potential issues and work to prevent problems before they impact delivery.

### Responsibilities
- Maintain and update the project risk register
- Identify, assess, and prioritize project risks
- Lead risk mitigation planning and execution
- Facilitate risk review sessions with the team
- Escalate critical risks to appropriate stakeholders
- Track risk trends and report on risk status

### Goals
- Minimize project disruption from unmanaged risks
- Foster a proactive risk-aware culture
- Ensure timely escalation and resolution of critical risks

### Typical Communication
- Weekly risk review sessions with Project Manager
- Risk status updates in stakeholder briefings
- Ad-hoc escalation communications for critical risks

### Interactions with Existing Roles
| Role | Interaction |
|------|-------------|
| **Developers** | Identifies technical risks, collaborates on mitigation strategies, reviews technical debt impacts |
| **Product Managers** | Assesses scope and prioritization risks, aligns risk mitigation with product goals |
| **Project Managers** | Partners on risk register maintenance, escalates timeline and resource risks |

---

## Stakeholder Liaison

### Role Summary
The Stakeholder Liaison maintains active communication with external and internal stakeholders, ensuring alignment of requirements, feedback, and resolutions. They serve as the primary bridge between project teams and stakeholders.

### Responsibilities
- Manage stakeholder communication and expectations
- Gather and synthesize stakeholder feedback
- Ensure alignment of requirements and project deliverables
- Facilitate stakeholder meetings and updates
- Resolve stakeholder concerns and escalate issues as needed
- Maintain stakeholder documentation and contact information

### Goals
- Ensure stakeholder satisfaction and engagement
- Minimize miscommunication and expectation gaps
- Provide timely, accurate information to stakeholders

### Typical Communication
- Regular stakeholder briefings and status updates
- Feedback collection sessions and surveys
- Escalation and resolution communications

### Interactions with Existing Roles
| Role | Interaction |
|------|-------------|
| **Developers** | Translates technical updates for stakeholders, gathers feedback on technical decisions |
| **Product Managers** | Aligns stakeholder needs with product priorities, communicates roadmap changes |
| **Project Managers** | Coordinates stakeholder communication schedules, escalates stakeholder concerns |

---

## Agile Coach

### Role Summary
The Agile Coach facilitates Agile practices, supports continuous improvement, and mentors project teams across all roles. They help teams adopt and improve Agile methodologies to deliver value more effectively.

### Responsibilities
- Facilitate Agile ceremonies (standups, retrospectives, planning sessions)
- Coach teams on Agile principles and best practices
- Identify and address team impediments and process inefficiencies
- Support continuous improvement initiatives
- Mentor team members and leaders on Agile transformation
- Track and report on team health and Agile maturity

### Goals
- Improve team velocity and delivery predictability
- Foster a culture of continuous improvement
- Ensure consistent application of Agile practices across teams

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and improvement tracking
- One-on-one coaching sessions with team members

### Interactions with Existing Roles
| Role | Interaction |
|------|-------------|
| **Developers** | Coaches on Agile practices, facilitates collaboration, helps remove impediments |
| **Product Managers** | Supports backlog refinement practices, coaches on prioritization techniques |
| **Project Managers** | Aligns on Agile processes, supports planning and tracking improvements |

---

## Role Interaction Matrix

This matrix summarizes how all roles interact with each other to ensure effective collaboration:

| Role | Developers | Product Managers | Project Managers | QA Lead | Release Manager | Risk Champion | Stakeholder Liaison | Agile Coach |
|------|------------|------------------|------------------|---------|-----------------|---------------|---------------------|-------------|
| **Developers** | — | Requirements, priorities | Tasks, timeline | Testing, bugs | Deployment | Technical risks | Tech updates | Agile practices |
| **Product Managers** | Features, acceptance | — | Roadmap, scope | Quality gates | Release content | Scope risks | Stakeholder needs | Backlog practices |
| **Project Managers** | Scheduling, resources | Milestones | — | Testing schedule | Release timeline | Risk escalation | Stakeholder updates | Process improvement |
| **QA Lead** | Test coverage | Acceptance criteria | Testing progress | — | Release readiness | Quality risks | Quality metrics | Testing practices |
| **Release Manager** | Deployment coordination | Release scope | Release schedule | Final testing | — | Deployment risks | Release comms | Release practices |
| **Risk Champion** | Tech risk identification | Scope risk assessment | Risk register | Quality risk review | Deployment risk | — | Stakeholder risk comms | Risk practices |
| **Stakeholder Liaison** | Technical translation | Requirements alignment | Status reporting | Quality reporting | Release announcements | Risk communication | — | Communication practices |
| **Agile Coach** | Team coaching | Product practices | Process alignment | QA practices | Release practices | Risk practices | Communication coaching | — |

---

## RACI Table: Key Project Activities

The RACI table below clarifies responsibilities across all roles for key project activities:

| Activity | Developers | Product Managers | Project Managers | QA Lead | Release Manager | Risk Champion | Stakeholder Liaison | Agile Coach |
|----------|------------|------------------|------------------|---------|-----------------|---------------|---------------------|-------------|
| Define Requirements | C | A | R | C | I | I | C | I |
| Sprint Planning | R | A | R | C | I | C | I | C |
| Feature Development | R/A | C | I | C | I | C | I | I |
| Code Review | R/A | I | I | C | I | I | I | I |
| Test Planning | C | C | I | R/A | C | I | I | I |
| Test Execution | C | I | I | R/A | I | I | I | I |
| Release Planning | C | C | R | C | R/A | C | C | I |
| Deployment | R | I | I | C | R/A | C | I | I |
| Risk Assessment | C | C | R | C | C | R/A | I | I |
| Stakeholder Communication | I | C | C | I | C | I | R/A | I |
| Retrospectives | R | C | C | C | C | C | I | R/A |
| Process Improvement | C | C | C | C | C | C | I | R/A |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the outcome)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

---

## Role Onboarding Checklist

Use this checklist when onboarding team members to any role. Customize based on specific role requirements.

### General Onboarding (All Roles)
- [ ] Review OctoAcme Project Management Overview
- [ ] Read role-specific documentation and responsibilities
- [ ] Meet with Project Manager for project context
- [ ] Access project communication channels (Slack, Teams, etc.)
- [ ] Review current project status and backlog
- [ ] Attend first team standup/meeting

### Role-Specific Onboarding

#### Developers
- [ ] Set up development environment
- [ ] Review codebase architecture and conventions
- [ ] Complete first code review
- [ ] Pair with senior developer on initial task

#### Product Managers
- [ ] Review product roadmap and strategy
- [ ] Meet with key stakeholders
- [ ] Understand current prioritization criteria
- [ ] Review customer feedback and metrics

#### Project Managers
- [ ] Review project charter and timeline
- [ ] Access project management tools (GitHub Projects, etc.)
- [ ] Review risk register and current risks
- [ ] Meet with all team leads

#### Quality Assurance Lead
- [ ] Review test strategy and coverage
- [ ] Access testing tools and environments
- [ ] Review current defect backlog
- [ ] Meet with development and product leads

#### Release Manager
- [ ] Review release procedures and checklists
- [ ] Access deployment pipelines and tools
- [ ] Review release calendar and upcoming releases
- [ ] Meet with QA Lead and Operations

#### Risk Champion
- [ ] Review risk register and mitigation plans
- [ ] Understand escalation paths
- [ ] Meet with Project Manager and key stakeholders
- [ ] Schedule first risk review session

#### Stakeholder Liaison
- [ ] Review stakeholder map and contacts
- [ ] Understand communication cadence
- [ ] Review recent stakeholder feedback
- [ ] Schedule introductory stakeholder meetings

#### Agile Coach
- [ ] Review team's current Agile practices
- [ ] Attend team ceremonies as observer
- [ ] Meet with team leads and members
- [ ] Identify initial improvement opportunities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
