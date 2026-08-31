# Risk Framework

> *Portfolio framework informed by enterprise AI program-management experience.*

## Risk Categories Tracked

| Category | Example Question |
|---|---|
| Data | Does this use case touch personal, customer, or regulated data? |
| Decision impact | Could an incorrect output cause financial, legal, or reputational harm? |
| Autonomy | Does a human review outputs before they're acted on? |
| Vendor / model | Is the underlying model or vendor within approved use? |
| Security | Does this use case introduce new data access or system integration? |
| Adoption risk | Could inconsistent or low adoption undermine the business case? |

## Risk Register Format

| Use Case | Risk Category | Likelihood | Impact | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|
| *(example)* AI Support Triage Assistant | Decision impact | Medium | Medium | Human review of all escalations before closure | Program Office | Open |

## Exception Handling

Any approved use case that later shows signs of risk drift — an unplanned expansion in data scope, a change in autonomy level, or a spike in incorrect outputs — is automatically returned to Governance for re-review rather than being flagged only at the next scheduled audit. This keeps risk review responsive to how a use case actually behaves in production, not just how it was designed on paper.
