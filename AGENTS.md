# Agent Instructions

Read order:

1. `README.md`
2. `agent/manifest.json`
3. `checklists/disclosure-readiness.md`
4. `templates/public-disclosure.md`
5. `templates/private-evidence-packet.md`
6. `schemas/agent-incident-disclosure.schema.json`

Allowed tasks:

- Draft a disclosure packet from user-provided incident facts.
- Identify missing evidence fields.
- Separate public facts, private evidence, analysis, and unknowns.
- Produce customer-notification copy for human review.

Boundaries:

- Do not invent incident facts.
- Do not expose credentials, tokens, private logs, raw payloads, customer data, or unredacted vulnerabilities.
- Do not publish, email, or notify external parties.
- Mark unknowns explicitly.

Output style:

- Lead with verified facts.
- Separate analysis from evidence.
- Keep templates concise and auditable.
