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

## QA / Test Engineer

### Role Summary
QA/Test Engineers design and execute test strategies, ensure quality criteria are met, and advocate for test automation and continuous integration. They are the primary advocates for product quality and user acceptance.

### Responsibilities
- Design and implement manual and automated test suites (unit, integration, end-to-end)
- Perform exploratory testing and identify edge cases
- Report, triage, and track defects with clear reproduction steps
- Participate in release and go/no-go decisions
- Review and improve test coverage and CI/CD processes
- Validate acceptance criteria before handoff to production

### Goals
- Ensure software meets quality standards before release
- Enable fast feedback loops through automation
- Reduce production incidents and customer-facing defects

### Interactions
- **Developers**: Review test results, debug failures, and collaborate on quality improvements
- **Project Manager**: Communicate test status, blockers, and release readiness
- **Product Manager**: Validate feature acceptance criteria and usability
- **DevOps/SRE**: Collaborate on test environment setup and deployment validation

### Typical Communication
- Test reports and defect logs
- Sprint planning and QA status updates
- Release readiness assessments

---

## UX / UI Designer

### Role Summary
UX/UI Designers own the design experience and usability of the product. They create wireframes, mockups, design systems, and specifications that guide implementation and ensure a consistent, intuitive user experience.

### Responsibilities
- Create wireframes, mockups, and high-fidelity design assets
- Develop and maintain design systems and component libraries
- Conduct user research and usability testing
- Incorporate user feedback and iterate on designs
- Review implementation against design specifications
- Advocate for user needs and accessibility standards

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Ensure design consistency across the product
- Reduce user friction and support burden

### Interactions
- **Product Manager**: Align on requirements, user needs, and feature priorities
- **Developers**: Hand off designs, review implementations, and iterate on details
- **QA**: Validate designed experiences meet acceptance criteria
- **Project Manager**: Communicate design timelines and dependencies

### Typical Communication
- Design specifications and component libraries
- Design review sessions and feedback
- Accessibility and usability guidelines

---

## DevOps / SRE

### Role Summary
DevOps Engineers and Site Reliability Engineers (SREs) manage infrastructure, automate deployment pipelines, monitor system health, and lead incident response. They ensure the platform is reliable, scalable, and secure.

### Responsibilities
- Build, maintain, and optimize CI/CD pipelines
- Manage infrastructure and cloud resources
- Monitor production systems and set up alerting
- Lead incident response and post-incident reviews
- Document runbooks and operational procedures
- Implement security and compliance controls

### Goals
- Minimize downtime and production incidents
- Enable fast, safe deployments
- Maintain system performance and scalability

### Interactions
- **Developers**: Support deployment, debug production issues, and validate environment readiness
- **QA**: Provide test environments and deployment coordination
- **Project Manager**: Communicate production health, incident status, and escalations
- **Technical Writer**: Document operational procedures and runbooks

### Typical Communication
- Deployment notifications and release coordination
- Incident alerts and post-incident reports
- Infrastructure and monitoring documentation

---

## Technical Writer

### Role Summary
Technical Writers prepare, review, and maintain technical and user-facing documentation. They translate complex concepts into clear, accessible, and well-organized content for multiple audiences.

### Responsibilities
- Document features, APIs, and user guides
- Create and maintain release notes and changelog entries
- Write and update process documentation (like these guides)
- Review documentation for clarity, accuracy, and consistency
- Maintain FAQs and troubleshooting guides
- Ensure accessibility and usability of all written materials

### Goals
- Reduce support burden through clear self-service documentation
- Onboard users and developers efficiently
- Maintain a single source of truth for processes and procedures

### Interactions
- **Developers**: Gather implementation details, APIs, and technical specifications
- **Product Manager**: Understand feature context, user scenarios, and key messages
- **QA**: Review documentation for accuracy and completeness
- **DevOps/SRE**: Document operational procedures and deployment steps
- **Customer Support**: Update FAQs and troubleshooting guides based on user feedback

### Typical Communication
- Documentation reviews and feedback
- Content plans and documentation roadmaps
- Collaboration on guides and templates

---

## Customer Support / Success Lead

### Role Summary
Customer Support and Success Leads advocate for end-users, triage feedback, and represent the user voice in process improvements. They are the bridge between customers and the product team.

### Responsibilities
- Triage and respond to customer inquiries and issues
- Document user pain points and feature requests
- Communicate key trends and patterns to the product team
- Update FAQs and create self-service resources
- Participate in user research and feedback sessions
- Escalate critical issues to the appropriate teams

### Goals
- Maximize customer satisfaction and retention
- Reduce support volume through self-service resources
- Surface user needs and priorities for product improvements

### Interactions
- **Project Manager**: Report on user impact, communicate issue urgency, and coordinate escalations
- **Product Manager**: Share customer feedback, feature requests, and usage patterns
- **Developers**: Escalate complex technical issues and collaborate on root cause analysis
- **Technical Writer**: Update FAQs and help documentation based on support trends
- **QA**: Report edge cases and scenarios not covered by testing

### Typical Communication
- Support tickets and escalation reports
- Customer feedback and feature request summaries
- User trend analysis and business impact assessments

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running projects, refer to this document to clarify ownership, communication patterns, and collaboration points.
