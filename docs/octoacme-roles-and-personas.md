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

## UX Designers

### Role Summary
UX Designers translate requirements into user-friendly interfaces and experiences. They collaborate with Product Managers, Developers, and stakeholders to ensure products are intuitive, accessible, and aligned with user needs.

### Responsibilities
- Design user interfaces, workflows, and interactions
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Ensure accessibility and usability standards are met
- Participate in design reviews and iterate based on feedback
- Collaborate on user stories and acceptance criteria from a UX perspective

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support adoption
- Validate designs with real user feedback
- Maintain design consistency across products

### Typical Communication
- Design reviews with Product and Engineering teams
- User research findings and usability test reports
- Design specs and interaction guidelines in Figma or similar tools
- Feedback on PRs related to UI implementation

### Example Interactions
- **With Product Manager:** "Based on user research, I recommend we simplify the checkout flow to reduce drop-off."
- **With Developers:** "Here's the Figma prototype for the dashboard. Let me know if any interactions need clarification."
- **With QA:** "Please test these accessibility features—screen reader support and keyboard navigation are critical."

---

## DevOps Engineers

### Role Summary
DevOps Engineers own infrastructure, CI/CD pipelines, and deployment automation. They enable teams to ship software reliably and efficiently while maintaining security and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud resources
- Implement monitoring, logging, and alerting systems
- Partner with Developers and QA on deployment processes
- Support incident response and system reliability
- Optimize build times and deployment workflows

### Goals
- Enable fast, reliable deployments with minimal downtime
- Maintain high availability and system reliability
- Automate repetitive operational tasks
- Improve observability and reduce mean time to recovery (MTTR)

### Typical Communication
- Infrastructure design docs and runbooks
- Post-incident reviews and deployment retrospectives
- Pipeline status updates and release readiness confirmations
- Collaboration in standups on deployment blockers

### Example Interactions
- **With Developers:** "I've updated the staging environment. The new pipeline will run tests automatically on every PR."
- **With Project Manager:** "We need 2 hours of downtime for the database migration. Saturday at 2 AM works best."
- **With Security Lead:** "I've added secret scanning to our CI pipeline per your recommendation."

---

## Security Leads

### Role Summary
Security Leads identify and mitigate security risks throughout the development lifecycle. They collaborate with teams to build secure systems and respond to security incidents.

### Responsibilities
- Conduct threat modeling and security assessments
- Review code and architecture for security vulnerabilities
- Define security requirements and best practices
- Lead incident response for security breaches
- Ensure compliance with security standards and regulations
- Provide security training and guidance to teams

### Goals
- Minimize security vulnerabilities and attack surface
- Ensure data protection and privacy compliance
- Enable teams to build secure software by default
- Respond quickly and effectively to security incidents

### Typical Communication
- Security assessments and threat model documentation
- Code review feedback on security issues
- Incident response coordination and post-mortems
- Security bulletins and advisory updates

### Example Interactions
- **With Developers:** "I found SQL injection risks in the user input handling. Please use parameterized queries."
- **With DevOps Engineer:** "Let's add dependency scanning to catch vulnerable libraries before deployment."
- **With Project Manager:** "We need to schedule a security review before the release. It will take about 4 hours."

---

## Data Analysts

### Role Summary
Data Analysts define analytics requirements, create reports and dashboards, and provide data-driven insights to inform product and business decisions.

### Responsibilities
- Define metrics and KPIs with Product Managers
- Build dashboards and reports for stakeholders
- Analyze user behavior and product usage patterns
- Validate hypotheses with A/B testing and experiments
- Provide data-driven recommendations for product improvements
- Ensure data quality and consistency

### Goals
- Enable data-driven decision making across the organization
- Measure product success and identify improvement opportunities
- Make data accessible and understandable to stakeholders
- Maintain accuracy and trust in analytics

### Typical Communication
- Analytics reports and dashboard links
- Experiment results and statistical analyses
- Data requirements and metric definitions
- Insights presentations to stakeholders

### Example Interactions
- **With Product Manager:** "The new feature increased user engagement by 15%. Here's the dashboard with the breakdown."
- **With Developers:** "We need to instrument these user actions for the analytics pipeline. Can you add the event tracking?"
- **With Executives:** "Based on the data, I recommend we prioritize mobile improvements—60% of our users are on mobile devices."

---

## Sponsors / Executive Stakeholders

### Role Summary
Sponsors and Executive Stakeholders provide strategic direction, approve major decisions, and ensure alignment with business objectives. They unblock issues that cannot be resolved at the team level.

### Responsibilities
- Approve project initiation and major scope changes
- Provide funding and resource allocation
- Set strategic priorities and business objectives
- Unblock escalated issues beyond PM/Product Lead authority
- Review milestone progress and business outcomes
- Champion projects across the organization

### Goals
- Ensure projects deliver strategic business value
- Optimize resource allocation across initiatives
- Remove organizational blockers
- Maintain visibility into project health and risks

### Typical Communication
- Executive briefings and milestone reviews
- Strategic decision meetings
- Escalation handling for critical issues
- High-level status updates and business impact reports

### Example Interactions
- **With Project Manager:** "Approved. Move forward with the initiative. Keep me posted on major milestones and any budget concerns."
- **With Product Manager:** "Given the competitive landscape, let's accelerate this feature. What additional resources do you need?"
- **During escalation:** "I'll talk to the VP of Engineering to prioritize the shared service dependency. This project is business-critical."

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

