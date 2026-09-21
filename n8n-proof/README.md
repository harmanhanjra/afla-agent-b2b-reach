# Production n8n Automation Proof of Work

Two portfolio-grade n8n automations focused on revenue and operations use cases.

## 1. AI Lead Qualification Pipeline
Webhook intake → deterministic validation/scoring → routing → CRM-ready payload → response.

## 2. Document / Order Intake Pipeline
Webhook document/order payload → field normalization → deterministic validation → confidence gate → human-review or ERP-ready output.

### Verification
The workflows are designed so their core path runs without paid credentials. External AI/CRM/ERP integrations are isolated behind replaceable nodes so secrets are never committed.

### Status
Implementation and reproducible validation fixtures are being added in this directory.
