# PM Autopilot Agent

A generic design project for a human-in-the-loop program-operations assistant that identifies delivery risks, requests focused updates, tracks follow-up state, and produces auditable summaries from synthetic project data.

## Data and confidentiality notice

This repository must use only fictional scenarios and synthetic data. It must not contain employer, customer, employee, product, project, tenant, financial, security, credential, incident, or proprietary organizational information.

Real Jira URLs, project keys, issue IDs, usernames, email addresses, webhook URLs, tokens, prompts copied from workplace systems, screenshots, exports, and internal operating rules are prohibited.

See [PORTFOLIO_DATA_POLICY.md](PORTFOLIO_DATA_POLICY.md) before adding any artifact.

## Current status

This repository currently documents a concept under development. It does not yet contain a runnable application, package manifest, production integration, or validated deployment instructions.

## Intended capabilities

The planned generic demonstration may include:

- Reading synthetic work-item data
- Detecting stale, blocked, or at-risk items using transparent rules
- Assigning explainable reason codes
- Generating one focused follow-up question
- Maintaining follow-up state to prevent repeated notifications
- Escalating unresolved risks through configurable policies
- Producing weekly program-health summaries
- Recording decisions and actions for auditability

## Design principles

1. Human approval for consequential actions
2. Explainable rules and reason codes
3. Minimal, non-repetitive nudges
4. Synthetic data only
5. No embedded credentials or production endpoints
6. Clear separation between demonstration logic and real integrations
7. Testable failure handling and duplicate-notification controls

## Planned repository structure

```text
src/          Demonstration agent logic
tests/        Unit and scenario tests
docs/         Architecture, controls, and operating model
samples/      Synthetic inputs and outputs
config/       Safe example configuration without credentials
```

Installation and usage instructions will be added only after a working implementation exists.
