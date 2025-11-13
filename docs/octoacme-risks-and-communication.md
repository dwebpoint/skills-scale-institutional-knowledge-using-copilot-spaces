# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs:
  - **Engineering:** Developers, DevOps Engineers, QA
  - **Product & Design:** Product Managers, UX Designers
  - **Data & Analytics:** Data Analysts
  - **Security & Compliance:** Security Leads
  - **Business:** Sponsors/Executive Stakeholders, Sales, Support
- Tailor communication frequency and format to stakeholder needs (e.g., weekly updates for engineering, milestone reviews for executives)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Technical/Delivery Issues:** Developer -> PM -> Product Lead -> Sponsor/Executive Stakeholder
- **Security Incidents:** Any team member -> Security Lead -> Security on-call -> Sponsor (if business-critical)
- **Infrastructure/Deployment Issues:** Developer/QA -> DevOps Engineer -> PM -> Sponsor (if impacting release)
- **Data/Analytics Issues:** Data Analyst -> Product Manager -> Product Lead
- **UX/Design Concerns:** UX Designer -> Product Manager -> Product Lead

### Escalation Guidelines
- Escalate when: impact is high, resolution time exceeds SLA, or cross-team coordination is needed
- Include context: issue description, impact assessment, attempted solutions, and recommended next steps
- For security incidents, follow the security incident runbook and notify Security Lead immediately
