# Start Here — How to Use This Repository

This repository is designed to be **used**, not just read.

It is an independent implementation toolkit for organizations, practitioners, students, architects, risk teams, and governance teams that want to understand how an Artificial Intelligence Management System (AIMS) can be operationalized in practice.

> This repository does not reproduce ISO/IEC 42001:2023 and does not guarantee certification or conformity. Use the official standard for authoritative requirements.

## Choose your path

### 1. I am new to ISO/IEC 42001
Read the repository in this order:

1. `README.md` — understand the operating model.
2. `IMPLEMENTATION-MAP.md` — see how the artifacts fit together.
3. `01-context-and-scope/` — decide what your AIMS covers.
4. `02-leadership-and-governance/` — establish policy, ownership, and decision rights.
5. `03-ai-inventory/` — identify and register AI systems.
6. `04-risk-management/` and `05-ai-impact-assessment/` — assess risk and impact.
7. `06-data-governance/` through `09-monitoring/` — implement lifecycle controls.
8. `10-audit-and-assurance/` — gather evidence, review, and improve.
9. `12-case-study/` — see a worked example.

### 2. I need to govern one AI use case
Use this minimum workflow:

**Intake → Inventory → Impact assessment → Risk assessment → Control selection → Validation → Approval → Monitoring**

Recommended artifacts:

- `03-ai-inventory/ai-use-case-intake.md`
- `03-ai-inventory/ai-system-register.csv`
- `05-ai-impact-assessment/ai-impact-assessment.md`
- `04-risk-management/ai-risk-assessment-template.md`
- `11-controls/control-implementation-matrix.csv`
- `07-ai-lifecycle/validation-checklist.md`
- `07-ai-lifecycle/deployment-approval.md`
- `09-monitoring/model-monitoring-framework.md`

### 3. I am building an enterprise AIMS
Follow `90-DAY-IMPLEMENTATION-ROADMAP.md` and use `IMPLEMENTATION-MAP.md` as the operating index.

### 4. I am preparing for internal audit or assurance
Start with:

- `10-audit-and-assurance/evidence-register.csv`
- `10-audit-and-assurance/internal-audit-checklist.md`
- `10-audit-and-assurance/nonconformity-register.csv`
- `10-audit-and-assurance/management-review-template.md`
- `11-controls/control-implementation-matrix.csv`

The objective is not to accumulate documents. The objective is to demonstrate that governance controls are **designed, implemented, operating, reviewed, and improved**.

### 5. I am evaluating a third-party AI product
Start with:

- `08-third-party-ai/vendor-ai-assessment.md`
- `08-third-party-ai/ai-contract-checklist.md`
- `05-ai-impact-assessment/ai-impact-assessment.md`
- `06-data-governance/privacy-assessment.md`
- `11-controls/control-implementation-matrix.csv`

Vendor assurance does not remove the deploying organization's responsibility to understand the actual use case, affected parties, risks, controls, and monitoring needs.

## The eight questions to ask for every AI system

1. Who is affected?
2. What harm could occur?
3. What data is being used?
4. Is there bias?
5. Is the decision explainable?
6. Is human review required?
7. Who signs off?
8. What monitoring happens after deployment?

These questions are an original implementation heuristic used throughout this repository.

## Artifact labels used in this repository

| Label | Meaning | What you should do |
|---|---|---|
| **Template** | Blank or partially structured artifact | Copy and tailor it to your organization/use case |
| **Register** | Ongoing system of record | Assign an owner and keep it current |
| **Checklist** | Review or gate aid | Complete it at the relevant lifecycle point |
| **Methodology** | Defined decision/scoring approach | Adapt and approve it before operational use |
| **Guidance** | Explanatory implementation material | Use it to understand or design your approach |
| **Example** | Illustrative populated content | Learn from it; do not treat it as your evidence |
| **Evidence** | Record showing an activity/control occurred | Retain according to your governance requirements |

## What “good” looks like

A useful AIMS should let you answer, with evidence:

- What AI systems do we use?
- Why are we using them?
- Who owns each one?
- What people or processes can they affect?
- What risks and opportunities have we identified?
- What controls were chosen and why?
- Who approved deployment and residual risk?
- What do we monitor in production?
- What happens when the system, model, data, vendor, or context changes?
- What evidence shows the process is operating?
- What did management review and improve?

## Before using this in a real organization

Adapt the framework to your organization's size, sector, jurisdictions, risk appetite, existing management systems, policies, technology architecture, model-risk practices, privacy obligations, security requirements, and procurement processes.

For certification or formal conformity work, obtain ISO/IEC 42001:2023 from ISO or an authorized standards body and use qualified assurance/certification support where appropriate.
