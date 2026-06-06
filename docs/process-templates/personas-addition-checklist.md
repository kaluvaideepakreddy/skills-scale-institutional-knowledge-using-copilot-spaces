# Personas / Roles Addition Checklist

Purpose:
A lightweight checklist and template for adding a new persona/role to the OctoAcme process docs. Use this to ensure consistent entries and reduce ambiguity about responsibilities and handoffs.

Checklist
- [ ] Draft persona entry with:
  - Role summary (1 sentence)
  - 4–8 responsibilities (bulleted)
  - Hand-offs/interactions with existing roles
  - Typical communication channels and artifacts
- [ ] Confirm acceptance criteria and success measures for the role (how will we know the role is functioning)
- [ ] Review draft with at least one Product Manager and one Project Manager
- [ ] Review implementation implications with Engineering (e.g., instrumentation, tooling, access)
- [ ] Add entry to docs/octoacme-roles-and-personas.md in the recommended format
- [ ] Link the change to the originating issue and add any follow-up tasks to the project board
- [ ] Gather any onboarding artifacts (templates, runbooks, checklists) and link them from the persona entry

Template (copy into issue body when proposing a new persona)
- Proposed persona name:
- Role summary:
- Responsibilities:
  - 
- Interactions / handoffs (with existing roles):
  - 
- Acceptance criteria for role success:
  - 
- Stakeholders to review:
  - Product:
  - Project:
  - Engineering:
  - QA:
  - Security (if applicable):

Acceptance Criteria for this update (to be used in PR and the linked issue)
- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content has been reviewed with stakeholders (PM and Project Manager at minimum)
- New template/checklist added under docs/process-templates/

How to use after merge
- When a team decides to add a role, create an issue using the template above, complete the checklist, and reference the docs entry. If the role requires tooling or access changes, create follow-up issues and link them.
