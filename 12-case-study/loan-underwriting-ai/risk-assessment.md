# Loan Underwriting AI — Risk Assessment

| Risk | Inherent risk | Key controls | Residual target |
|---|---|---|---|
| Historical bias creates disparate outcomes | High | Data review, fairness testing, feature challenge, ongoing monitoring | Moderate |
| Model recommendation cannot be meaningfully explained | High | Explainability requirements, reason-code testing, human review | Moderate |
| Underwriters over-trust the model | High | Training, mandatory review criteria, override rights, override analytics | Moderate |
| Input-data drift reduces performance | High | Drift monitoring, thresholds, reassessment triggers | Low/Moderate |
| Unapproved model change reaches production | High | Versioning, change control, validation, deployment approval | Low |
| Incorrect output harms applicant | High | Confidence thresholds, human review, appeal/escalation process | Moderate |
