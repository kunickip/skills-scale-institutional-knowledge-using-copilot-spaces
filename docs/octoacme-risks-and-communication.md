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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, security)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Coordinate with Technical Writer for external communications and release announcements
- Ensure Support Engineers are briefed before customer-facing releases

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
- **Standard escalation**: Team-level -> PM -> Product Lead -> Sponsor
- **Security incidents**: Follow the security incident runbook and notify Security Lead immediately
- **Post-release issues**: Support Engineers triage and escalate to Release Manager or development team as needed
- **Usability concerns**: UX Designer escalates critical usability issues that impact user experience
- **Documentation gaps**: Technical Writer flags critical documentation needs to PM for prioritization
