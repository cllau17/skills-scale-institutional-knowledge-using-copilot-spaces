# OctoAcme — Cross-Functional Roles Checklist & Templates

## Purpose
Provide practical checklists and templates to help teams clarify accountability, coordinate across roles, and ensure all responsibilities are covered throughout a project lifecycle.

---

## Project Kickoff Role Assignment Checklist

Use this checklist when starting a new project to confirm that all key roles are assigned and understood.

- [ ] Project Manager identified and briefed
- [ ] Product Manager identified and roadmap shared
- [ ] Team Leads assigned per functional area (engineering, design, etc.)
- [ ] Developers assigned to the project
- [ ] QA Analyst assigned and acceptance criteria reviewed
- [ ] Change Manager identified (for projects with significant change impact)
- [ ] Communications Lead identified and communication plan initiated
- [ ] Stakeholder Liaison identified and stakeholder map created
- [ ] Agile Coach engaged (for teams new to Agile or undergoing process change)
- [ ] All role owners have reviewed the [Roles & Personas doc](octoacme-roles-and-personas.md)

---

## RACI Template

Use this template to document responsibility for key project activities. Fill in one row per activity.

| Activity | Project Manager | Product Manager | Developer | QA Analyst | Change Manager | Communications Lead | Stakeholder Liaison | Agile Coach |
|----------|----------------|----------------|-----------|------------|----------------|--------------------|--------------------|-------------|
| Project Charter | R | C | I | I | I | I | C | I |
| Backlog Prioritization | C | R | C | C | I | I | C | C |
| Sprint Planning | R | C | R | C | I | I | I | C |
| Change Request Review | C | C | I | I | R | C | C | I |
| Stakeholder Updates | C | C | I | I | C | R | R | I |
| Test Plan Creation | I | C | C | R | I | I | I | I |
| Release Readiness Review | R | C | C | R | C | C | I | I |
| Retrospective Facilitation | C | I | I | I | I | I | I | R |
| Communication Plan | C | C | I | I | C | R | C | I |

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## Communication Plan Template

Use this template to define how communications will be managed for a project.

| Audience | Message Type | Frequency | Channel | Owner |
|----------|-------------|-----------|---------|-------|
| Project Team | Status Update | Twice-weekly | Standup / Slack | Project Manager |
| Stakeholders | Progress Report | Weekly | Email / Wiki | Communications Lead |
| Executive Sponsors | Executive Summary | Monthly | Email / Slide deck | Communications Lead |
| End Users | Release Announcement | Per release | Email / In-app | Communications Lead |
| Stakeholder Groups | Feedback Collection | Per milestone | Survey / Meeting | Stakeholder Liaison |

**Template fields:**
- **Audience**: Who receives this communication?
- **Message Type**: What kind of information is being shared?
- **Frequency**: How often is this communication sent?
- **Channel**: Where/how is it delivered?
- **Owner**: Who is responsible for creating and sending it?

---

## Change Request Template

Use this template when submitting a change request to the Change Manager.

- **Change ID**: _(auto-assigned or sequential, e.g., CR-001)_
- **Date Submitted**:
- **Submitted By**:
- **Change Description**: _(What is changing, and why?)_
- **Affected Areas**: _(Scope, timeline, resources, or process)_
- **Impact Assessment**: _(High / Medium / Low — describe the impact)_
- **Proposed Implementation Date**:
- **Rollback Plan**: _(How to reverse the change if needed)_
- **Approvals Required**:
  - [ ] Project Manager
  - [ ] Product Manager
  - [ ] Change Manager
  - [ ] Affected Team Lead(s)
- **Status**: _(Pending / Approved / Rejected / Implemented)_

---

## QA Readiness Checklist

Use this checklist before releasing any deliverable to production.

- [ ] All acceptance criteria reviewed and testable
- [ ] Test plan created and shared with the team
- [ ] Test cases written and reviewed
- [ ] All critical and high-priority defects resolved or deferred with justification
- [ ] Regression test suite executed with no new critical failures
- [ ] QA Analyst has signed off on release readiness
- [ ] Release readiness report shared with Project Manager and stakeholders
- [ ] Rollback procedure confirmed with the deployment team

---

## Agile Ceremony Checklist

Use this checklist to ensure Agile ceremonies are running effectively. The Agile Coach can use this as a health check.

### Sprint Planning
- [ ] Backlog is refined and prioritized
- [ ] Team capacity confirmed
- [ ] Sprint goal defined
- [ ] Stories have acceptance criteria

### Sprint Review / Demo
- [ ] Working software demoed (no slides substituting for a demo)
- [ ] Stakeholder feedback gathered
- [ ] Incomplete items returned to backlog

### Retrospective
- [ ] Team has a safe space to share openly
- [ ] What went well: documented
- [ ] What could improve: documented
- [ ] Action items assigned with owners and due dates
- [ ] Previous action items reviewed

### Backlog Refinement
- [ ] New stories groomed and estimated
- [ ] Dependencies identified
- [ ] Acceptance criteria written for top-priority items

---

## Collaboration Touchpoints Reference

This table summarizes key collaboration touchpoints across the expanded set of roles.

| Role | Works Closely With | On What Topics |
|------|--------------------|----------------|
| Change Manager | Project Manager, Team Leads, Communications Lead | Change impact assessment, scheduling, and communications |
| Communications Lead | Project Manager, Stakeholder Liaison, Change Manager | Status updates, change announcements, stakeholder messaging |
| Stakeholder Liaison | Communications Lead, Product Manager, Project Manager | Requirements, feedback, escalations |
| QA Analyst | Developers, Product Manager, Project Manager | Acceptance criteria, defect resolution, release sign-off |
| Agile Coach | Project Manager, Team Leads, Developers, Product Manager | Process improvement, ceremony facilitation, Agile adoption |
