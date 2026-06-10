# Cross-Functional Roles Interaction Guide

## Purpose
This guide clarifies how OctoAcme's expanded set of roles interact throughout the project lifecycle. It helps teams understand ownership, communication touchpoints, and hand-off patterns to reduce ambiguity and improve collaboration.

---

## Project Phase Interactions

### Initiation Phase

| Role | Activities | Collaborates With |
|------|------------|-------------------|
| **Product Manager** | Define problem and success metrics | Project Manager, Stakeholders |
| **Project Manager** | Create one-pager, align stakeholders | Product Manager, all core roles |
| **Product Manager + PM** | Identify team composition | QA, Design, DevOps/SRE (as needed) |

---

### Planning Phase

| Role | Activities | Collaborates With |
|------|------------|-------------------|
| **Product Manager** | Finalize requirements and acceptance criteria | Developers, QA, Design |
| **UX/UI Designer** | Create design specs and wireframes | Product Manager, Developers, QA |
| **Project Manager** | Create backlog, estimate, plan sprints | Developers, QA, Tech Writer |
| **Developers** | Estimate story complexity, identify technical risks | Project Manager, DevOps/SRE |
| **QA** | Define test strategy and acceptance criteria | Developers, Product Manager, Project Manager |
| **Tech Writer** | Plan documentation scope | Developers, Product Manager |

---

### Execution Phase

| Role | Activities | Collaborates With |
|------|------------|-------------------|
| **Developers** | Implement features, write code | QA, Project Manager, Design (for specs) |
| **UX/UI Designer** | Review implementation against design specs | Developers, QA |
| **QA** | Execute tests, report defects, validate acceptance | Developers, Project Manager, Product Manager |
| **Tech Writer** | Document features and APIs | Developers, Product Manager, QA |
| **Project Manager** | Track progress, manage risks, facilitate standups | All roles (daily standup) |
| **Product Manager** | Monitor metrics, adjust backlog as needed | Project Manager, Developers |

---

### Release Phase

| Role | Activities | Collaborates With |
|------|------------|-------------------|
| **QA** | Final validation and go/no-go decision | Developers, Project Manager, DevOps/SRE |
| **Tech Writer** | Finalize release notes and user guides | Developers, Product Manager, Support |
| **DevOps/SRE** | Deploy to staging and production | Developers, QA, Project Manager |
| **Project Manager** | Coordinate release activities, communicate timeline | All roles, Stakeholders |
| **Customer Support** | Prepare support materials, FAQ updates | Tech Writer, Product Manager, Developers |

---

### Post-Release Phase

| Role | Activities | Collaborates With |
|------|------------|-------------------|
| **Customer Support** | Monitor customer feedback and issues | Product Manager, Developers, Tech Writer |
| **DevOps/SRE** | Monitor production health and performance | All roles (for incident response) |
| **Project Manager** | Facilitate retrospective, capture learnings | All roles |
| **Product Manager** | Measure success metrics and impact | Project Manager, Customer Support |
| **Tech Writer** | Update FAQs and troubleshooting guides | Customer Support, Developers |

---

## Critical Hand-off Points

### Design to Development
- **Owner**: UX/UI Designer (spec) → Developers (implementation)
- **Handoff Checklist**:
  - [ ] Design spec is complete and approved
  - [ ] Design system components are documented
  - [ ] Accessibility requirements are clear
  - [ ] QA has reviewed design for testability
- **Communication**: Design review session, component documentation

### Development to QA
- **Owner**: Developers (code) → QA (testing)
- **Handoff Checklist**:
  - [ ] Code is merged to staging branch
  - [ ] Acceptance criteria are documented in the PR
  - [ ] Tests are passing locally
  - [ ] Manual smoke tests are performed
- **Communication**: PR approval, QA ticket assignment

### QA to Release
- **Owner**: QA (validation) → DevOps/SRE (deployment)
- **Handoff Checklist**:
  - [ ] All acceptance criteria are met
  - [ ] No blockers or high-severity defects remain
  - [ ] Release notes are ready
  - [ ] Rollback plan is documented
- **Communication**: Release readiness report, go/no-go decision

### Release to Support
- **Owner**: DevOps/SRE (production) → Customer Support (user interaction)
- **Handoff Checklist**:
  - [ ] Release is live and stable
  - [ ] Monitoring and alerts are active
  - [ ] User-facing documentation is published
  - [ ] Support team is briefed on key changes
- **Communication**: Release announcement, support briefing

---

## Communication Responsibilities by Role

### Product Manager
- Weekly sync with Project Manager
- Stakeholder updates (monthly or milestone-based)
- Feedback loop with Customer Support (feature requests, trends)

### Project Manager
- Daily standups with delivery team
- Weekly sync with Product Manager
- Weekly risk and status reporting to stakeholders
- Ad-hoc escalation communication

### Developers
- Daily standups
- PR comments and code review feedback
- Technical design discussions with architects/leads

### QA / Test Engineer
- Test reports and defect logs (weekly or as needed)
- Release readiness assessments
- Participation in planning and retrospectives

### UX / UI Designer
- Design review sessions (weekly or per sprint)
- Design specifications and component documentation
- Feedback integration and iteration discussions

### DevOps / SRE
- Deployment coordination and notifications
- Production monitoring and incident alerts
- Release readiness validation

### Technical Writer
- Documentation reviews and publishing updates
- Collaboration on process guides and runbooks
- FAQ and troubleshooting content updates

### Customer Support / Success Lead
- User feedback summaries and trend reports
- Support tickets and escalation communication
- Collaboration on FAQ and help documentation updates

---

## Collaboration Best Practices

1. **Clarify Ownership**: At the start of each project, explicitly assign owners for key deliverables.
2. **Define Hand-offs**: Use the hand-off checklist to ensure nothing is missed between stages.
3. **Document Dependencies**: Flag cross-team dependencies early in planning.
4. **Over-Communicate in Standups**: Use daily standups to surface blockers and dependencies quickly.
5. **Use RACI When Needed**: For complex projects, define Responsible, Accountable, Consulted, Informed for each role on key activities.
6. **Review and Iterate**: Retrospectives should include discussion of collaboration effectiveness and needed process improvements.

---

## Related Documents
- `octoacme-roles-and-personas.md` — Detailed role descriptions
- `octoacme-project-management-overview.md` — Overall OctoAcme approach
- `octoacme-project-planning.md` — Planning workflow and artifacts
- `octoacme-execution-and-tracking.md` — Day-to-day execution patterns
