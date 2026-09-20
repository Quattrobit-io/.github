<div align="center">

# Quattrobit

**Independent software company building and operating its own software products.**

[Octron](https://www.octron.ai) · [Release updates](https://www.octron.ai/updates) · [Contact](mailto:hello@quattrobit.io) · [Security](https://github.com/Quattrobit-io/.github/blob/main/SECURITY.md)

</div>

Quattrobit's current product, Octron, coordinates AI agents on computers the user controls. The host remains responsible for execution and workspace state; Octron services provide account identity, authorization, discovery, and product access.

Octron is in active development.

## Architecture at a glance

| Surface | Responsibility |
| --- | --- |
| Octron Host | local agent execution, sessions, tools, and workspace state |
| Octron Mobile | remote control, approvals, files, terminals, browser access, and health |
| Octron Core | accounts, entitlements, enrollment, discovery, and revocation |
| Octron Protocol | versioned contracts shared across every runtime |

Source visibility is part of the trust model, but repository access alone is not a security guarantee. Claims about data flow, credentials, and transport must be supported by current code, tests, and deployment configuration.
