# Agent Incident Disclosure Ledger Kit

This repository accompanies the Substack article "The Agent Incident Disclosure Ledger."

Use it to prepare a disclosure packet before an AI agent incident or near miss occurs. The goal is structured transparency: enough public detail for customers and peers to defend themselves, enough private evidence for affected parties and assessors to verify impact, and enough internal traceability to improve controls.

## Start Here

- `checklists/disclosure-readiness.md` - readiness checklist.
- `templates/public-disclosure.md` - public disclosure template.
- `templates/private-evidence-packet.md` - private evidence packet template.
- `templates/customer-notification.md` - customer notification template.
- `schemas/agent-incident-disclosure.schema.json` - machine-readable disclosure schema.
- `agent/manifest.json` - agent-readable navigation.

## What Humans Can Do

- Prepare an incident-disclosure plan for coding agents, security agents, support agents, or background enterprise agents.
- Separate verified facts from analysis and community/media interpretation.
- Decide which evidence belongs in a public report and which belongs in a private assessor packet.

## What Agents Can Do

Agents may use this repo to draft disclosure packets, validate whether required evidence fields are present, and turn an incident timeline into a structured report. Agents must not invent facts, expose secrets, or publish reports without human approval.

## Intentionally Excluded

This kit does not include exploit details, live indicators, private traces, credentials, cookies, browser data, customer data, or raw incident logs.

Canonical article URL: https://ankitkumar3514.substack.com/p/the-agent-incident-disclosure-ledger

Public repo URL: https://github.com/ankitforce/agent-incident-disclosure-ledger-kit
