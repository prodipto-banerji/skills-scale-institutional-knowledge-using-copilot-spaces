# OctoAcme Cross-Functional Workflow Checklist

## Purpose
Ensure all roles are engaged and responsibilities are clear throughout the project lifecycle.

---

## Initiation Phase Checklist

### Product Manager
- [ ] Define problem statement and success metrics (Project One-pager)
- [ ] Identify key stakeholders and their needs
- [ ] Propose initial timeline and key milestones
- [ ] Share draft Project One-pager with Project Manager and sponsor

### Project Manager
- [ ] Schedule initiation kickoff meeting with all stakeholders
- [ ] Document stakeholder list and communication plan
- [ ] Identify initial resource and team composition needs
- [ ] Create initial risk register
- [ ] Secure sponsor approval to proceed to planning

### Relevant Contributors
- [ ] **Customer Support**: Provide any existing customer feedback or pain points
- [ ] **Business Analyst** (if applicable): Identify process or data requirements
- [ ] **Security/Compliance Lead**: Flag any regulatory or compliance considerations

---

## Planning Phase Checklist

### Business Analyst
- [ ] Conduct requirement workshops with stakeholders
- [ ] Document detailed use cases and business processes
- [ ] Create acceptance criteria template for backlog
- [ ] Define Definition of Done (DoD) with team

### Product Manager
- [ ] Prioritize backlog with BA support
- [ ] Write user stories with acceptance criteria
- [ ] Define success metrics and how they will be measured
- [ ] Approve BA's acceptance criteria template

### Project Manager
- [ ] Schedule planning kickoff with full delivery team
- [ ] Facilitate backlog estimation with Developers
- [ ] Create detailed project timeline and milestone map
- [ ] Identify cross-team dependencies
- [ ] Assign primary owner for each backlog item

### UX/UI Designer
- [ ] Review acceptance criteria for user experience impact
- [ ] Create wireframes or prototypes for key user journeys
- [ ] Define design system or component library requirements
- [ ] Schedule design review sessions with Product Manager

### Developers
- [ ] Participate in estimation and planning
- [ ] Identify technical constraints or risks
- [ ] Suggest design feasibility improvements
- [ ] Confirm Definition of Done aligns with practices

### DevOps/Infrastructure Engineer
- [ ] Estimate infrastructure and deployment work
- [ ] Propose CI/CD pipeline changes or improvements
- [ ] Identify staging environment requirements
- [ ] Plan for monitoring and observability setup

### Security/Compliance Lead
- [ ] Review project scope for security and compliance risks
- [ ] Define security requirements and acceptance criteria
- [ ] Create threat model if applicable
- [ ] Schedule security review sessions during execution

### QA/Testing
- [ ] Review acceptance criteria for testability
- [ ] Propose test strategy and test plan outline
- [ ] Identify test data and environment needs
- [ ] Define testing scope (unit, integration, E2E, performance)

---

## Execution Phase Checklist

### Daily Standups
- [ ] **Developers**: Report progress, blockers, and completion status
- [ ] **Project Manager**: Triage blockers and identify escalations
- [ ] **DevOps Engineer** (rotating): Report CI/CD and infrastructure status

### Weekly Sync (PM + Product Lead)
- [ ] **Product Manager** & **Project Manager**: Review progress against milestones
- [ ] **Product Manager** & **Project Manager**: Triage risks and dependency status
- [ ] **Project Manager** & **Security/Compliance Lead**: Review security risk register
- [ ] **Product Manager**: Share customer feedback from Support team

### Per-Story/Task Execution
- [ ] **Developers**: Self-assign and move task to "In Progress"
- [ ] **Developers**: Pair with UX/UI Designer if design spec needed
- [ ] **Developers**: Open PR with link to issue and acceptance criteria
- [ ] **Team**: Review PR; ensure tests and acceptance criteria met
- [ ] **QA/Testing**: Sign off when acceptance criteria verified
- [ ] **Developers**: Merge and mark as "Done"

### Ongoing During Execution
- [ ] **UX/UI Designer**: Conduct design reviews with stakeholders
- [ ] **Customer Support**: Provide feedback on features in development
- [ ] **Security/Compliance Lead**: Review code and design for security gaps
- [ ] **DevOps Engineer**: Monitor CI/CD pipeline and troubleshoot failures
- [ ] **Business Analyst**: Clarify requirements as questions arise
- [ ] **Project Manager**: Update risk register and escalate blockers

### Quality Gates
- [ ] **QA/Testing**: Create and execute test plan
- [ ] **Developers**: Fix defects identified during testing
- [ ] **Security/Compliance Lead**: Conduct security review
- [ ] **UX/UI Designer**: Validate UI matches design specs
- [ ] **Product Manager**: Confirm feature meets acceptance criteria

---

## Release Phase Checklist

### Pre-Release (1–2 weeks before)
- [ ] **DevOps Engineer**: Prepare deployment plan and runbook
- [ ] **DevOps Engineer**: Prepare rollback plan
- [ ] **Product Manager**: Prepare release notes and communications
- [ ] **Product Manager** & **Customer Support**: Prepare customer communication
- [ ] **Security/Compliance Lead**: Confirm security sign-off
- [ ] **QA/Testing**: Run smoke tests in staging environment
- [ ] **Project Manager**: Confirm all items marked as "Done" or planned holdovers

### Deployment Window
- [ ] **DevOps Engineer**: Execute deployment according to runbook
- [ ] **DevOps Engineer**: Run post-deploy verification checks
- [ ] **QA/Testing**: Execute smoke tests in production
- [ ] **Project Manager** & **DevOps Engineer**: Monitor for issues and stand by for rollback

### Post-Release (24–48 hours)
- [ ] **DevOps Engineer**: Monitor metrics and error rates
- [ ] **Customer Support**: Monitor for customer-reported issues
- [ ] **Developers**: Stand by for critical hotfixes
- [ ] **Product Manager**: Share release announcement with stakeholders
- [ ] **Product Manager** & **Customer Support**: Gather early customer feedback

---

## Retrospective Phase Checklist

### Before Retrospective (if needed)
- [ ] **Project Manager**: Gather feedback from all team members
- [ ] **Project Manager**: Identify blockers and key learnings
- [ ] **Product Manager**: Review success metrics achieved vs. targets

### Retrospective Meeting
- [ ] **All roles**: Participate and share what went well
- [ ] **All roles**: Identify what could be improved
- [ ] **All roles**: Propose action items with owners
- [ ] **Project Manager**: Document and prioritize 2–3 top action items

### Post-Retrospective
- [ ] **Project Manager**: Add action items to next project backlog or improvements backlog
- [ ] **All roles**: Review action items in weekly syncs
- [ ] **Project Manager**: Close out action items once completed

---

## Common Handoff Risks & Mitigation

| Risk | Cause | Mitigation |
|------|-------|-----------|
| Requirements unclear mid-execution | BA not involved in planning | Include BA in planning kickoff; have BA review acceptance criteria |
| Design not implementable | Developers not consulted in design | Schedule design feasibility review with Developers during planning |
| Deployment delayed | DevOps Engineer not included in planning | Include DevOps in planning to estimate infrastructure work |
| Security issues found late | Security/Compliance Lead not engaged early | Schedule security review during design; include in code review process |
| Customer needs not met | Customer Support feedback not gathered | Have CS provide feedback during planning and refinement |
| Scope creep | Unclear Definition of Done | Document DoD together; use acceptance criteria to gate feature completion |
| Missed dependencies | Cross-team interactions not mapped | Use role interaction matrix; escalate dependencies to PM weekly |
