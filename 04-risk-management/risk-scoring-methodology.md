# AI Risk Scoring Methodology

## Scoring dimensions
Score each dimension from 1 (low) to 5 (very high):

- Severity of potential harm
- Likelihood of harm
- Scale / number of affected parties
- Reversibility of outcome
- Degree of automation
- Data sensitivity
- Explainability challenge
- Third-party dependency

## Example inherent-risk method
`Inherent Risk = Severity × Likelihood`

Additional dimensions can be used as escalation triggers rather than mathematically blended.

## Suggested bands
- 1–4: Low
- 5–9: Moderate
- 10–16: High
- 17–25: Critical

## Control effectiveness
Rate control design and operating effectiveness separately.

## Residual risk
Residual risk must be explicitly accepted by a named accountable owner when above organizational tolerance.

## Escalation triggers
Regardless of numeric score, escalate when the use case:
- materially affects individuals' rights or access to essential services;
- makes or strongly influences adverse decisions;
- uses sensitive data;
- operates without meaningful human review;
- has unresolved fairness or explainability concerns;
- depends on an opaque third-party model for a critical process.
