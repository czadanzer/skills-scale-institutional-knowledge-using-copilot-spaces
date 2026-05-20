# OctoAcme — Cross-Functional Team Collaboration

## Purpose
Ensure clear role definition and accountability when establishing cross-functional project teams. Provides guidance for team leads and project managers to structure teams effectively.

## Pre-Project Setup

### Role Identification & Assignment
- [ ] Identify all required roles and personas for the project scope
- [ ] Reference `octoacme-roles-and-personas.md` to clarify role definitions
- [ ] Map specific team members to roles based on expertise and availability
- [ ] Clarify primary and secondary responsibilities for each assigned role
- [ ] Document decision-making authority and escalation paths for each role
- [ ] Create a RACI matrix (Responsible, Accountable, Consulted, Informed) if cross-team dependencies exist

### Communication & Collaboration Setup
- [ ] Establish role-specific communication channels (Slack, Teams, email lists)
- [ ] Define synchronous meeting cadence per role (standups, design reviews, etc.)
- [ ] Schedule team kickoff meeting to align on project goals and roles
- [ ] Document interaction protocols between roles (e.g., design review process, security sign-off)
- [ ] Identify dependencies between roles and flag potential bottlenecks

## Role Onboarding

### Onboarding Checklist
- [ ] Share relevant persona definitions from `octoacme-roles-and-personas.md` with team members
- [ ] Clarify how each assigned role contributes to project success
- [ ] Review role-specific acceptance criteria and quality standards
- [ ] Confirm each team member understands their responsibilities and goals
- [ ] Establish role-specific communication channels and meeting cadence
- [ ] Identify and discuss dependencies with other roles
- [ ] Document questions or ambiguities and escalate to Project Lead

### Alignment Session
- [ ] Schedule a 30–45 min sync with each role or role group
- [ ] Walk through their responsibilities and how they interact with other roles
- [ ] Clarify decision-making authority (who can approve, who must be consulted)
- [ ] Set expectations for response times and collaboration patterns

## During Execution

### Regular Role Check-ins
- [ ] Review role responsibilities during sprint planning and retrospectives
- [ ] Monitor for role confusion or ownership gaps—escalate immediately
- [ ] Capture role-specific insights in retrospectives (e.g., "How effective were our design reviews?")
- [ ] Adjust role responsibilities or communication patterns if needed

### Cross-Role Collaboration
- [ ] Use persona definitions to frame design/code/security reviews
- [ ] Ensure all stakeholder roles are represented in key decisions
- [ ] Document role-specific feedback and escalations in centralized risk register
- [ ] Hold cross-functional sync if dependencies or blockers emerge

### Issue Escalation
- [ ] Ambiguity about role ownership → Escalate to PM immediately
- [ ] Role conflicts or overlaps → Document and raise in weekly PM sync
- [ ] Resource constraints impacting role delivery → Escalate to Project Lead
- [ ] Cross-team dependency delays → Escalate to Project Manager for coordination

## After Project Completion

### Retrospective & Learning Capture
- [ ] Conduct role-focused retrospective questions:
  - Did the defined roles match reality?
  - Were there ownership gaps or overlaps?
  - Did cross-role communication work as planned?
  - What would you change about role structure for next project?
- [ ] Document any role adjustments or new interactions discovered
- [ ] Capture lessons learned about team structure effectiveness

### Feedback & Improvement
- [ ] Collect feedback from each role on collaboration and clarity
- [ ] Update persona definitions if responsibilities evolved significantly
- [ ] Feed improvements back into project management documentation
- [ ] Share learnings with other project teams for consistency

## Role Clarity Assessment Checklist

Use this checklist to evaluate whether role clarity is sufficient:

- [ ] **Understanding**: Do all team members understand their role and responsibilities?
- [ ] **Authority**: Are decision-making authorities clear for each role?
- [ ] **Interactions**: Are communication protocols established for role-to-role interaction?
- [ ] **Contribution**: Can each role articulate how they contribute to project goals?
- [ ] **Coverage**: Are there any gaps or overlaps in role coverage for key activities?
- [ ] **Escalation**: Does everyone know who to escalate to when issues arise?
- [ ] **Delivery**: Is each role clear on success criteria and quality standards for their work?

## Common Cross-Functional Interaction Patterns

### Design & Development Review
- **Participants**: UX Designer, Developer, Product Manager
- **Cadence**: During feature implementation, as needed
- **Output**: Design approval, feasibility feedback, handoff documentation

### Security Review
- **Participants**: Security Lead, Developer, Project Manager
- **Cadence**: During design phase and code review
- **Output**: Threat model sign-off, security checklist completion

### Metrics & Success Validation
- **Participants**: Data Analyst, Product Manager, Project Manager
- **Cadence**: Pre-release, post-release, and milestone reviews
- **Output**: Metric dashboards, success validation reports

### Customer Feedback Loop
- **Participants**: Customer Support, Product Manager, Developer
- **Cadence**: Weekly or after support escalations
- **Output**: Customer issue summaries, feature feedback, quality insights

### Release Coordination
- **Participants**: Project Manager, Developer, QA, Customer Support, Product Manager
- **Cadence**: Pre-release checklist and launch day coordination
- **Output**: Release notes, launch checklist sign-off, post-release verification

## Template: Cross-Functional Team Charter

Use this template to document team structure at project kickoff:

```
## Project: [Project Name]

### Core Team Roles
- **Product Manager**: [Name]
- **Project Manager**: [Name]
- **Lead Developer**: [Name]
- **UX Designer**: [Name]
- **Security Lead**: [Name]
- **Data Analyst**: [Name]
- **Customer Support**: [Name]

### Key Dependencies & Handoffs
1. [Describe dependency between roles]
2. [Describe dependency between roles]

### Communication Cadence
- Daily Standups: [Team members + time]
- Weekly Sync: [Team members + time]
- Design Reviews: [Frequency + participants]
- Security Reviews: [Frequency + participants]

### Escalation Paths
- Day-to-day questions → [Role]
- Scope/Priority changes → Product Manager
- Technical risks → Lead Developer
- Security risks → Security Lead
- Timeline/deadline risks → Project Manager

### Success Criteria for Role Effectiveness
- [ ] All roles report clear understanding of responsibilities
- [ ] Cross-role meetings run efficiently with clear outcomes
- [ ] Role-specific deliverables meet quality standards
- [ ] Escalations are handled within [X] hours
```
