# Governance Framework

> *Portfolio framework informed by enterprise AI program-management experience. Illustrative example, not a disclosure of any employer's actual governance policy.*

## Principle

Governance should be proportional to risk and should never be the reason a low-risk idea takes months to try. It should also never be optional for a use case that touches sensitive data or makes a consequential decision about a person.

## Governance Dimensions

Every use case is assessed across four dimensions before it is scored for risk tier:

1. **Data sensitivity** — What data does the use case touch, and how sensitive is it?
2. **Decision consequence** — Does the output influence a decision that affects a person, a customer, or a financial outcome?
3. **Autonomy level** — Does a human review the output before it's acted on, or does the system act independently?
4. **Reversibility** — If the output is wrong, how easy is it to catch and undo?

## Responsible AI Principles Applied

- **Privacy** — data minimization and purpose limitation for any use case touching personal or customer data.
- **Security** — standard security review for any use case with new data access or new system integration.
- **Fairness** — review for disparate impact on any use case influencing decisions about people.
- **Transparency** — users are told when they are interacting with or relying on an AI-generated output.
- **Accountability** — every approved use case has a named business owner, not just a technical owner.

## Human Review Checkpoints

High-autonomy use cases (where the system acts without a human reviewing each output) require:

- A defined human review checkpoint before initial launch.
- A documented escalation path for the human reviewer.
- A periodic sampling review after launch to confirm quality holds as usage scales.

This pattern mirrors the acceptance-criteria and escalation-path structure used in agentic workflow design more broadly — a system is allowed more autonomy only once its checkpoints and escalation paths are proven, not assumed.

## Related

- [Risk Decision Tree](decision-tree.md)
- [Risk Framework](risk-framework.md)
