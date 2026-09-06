# 90-Day AIMS Implementation Roadmap

A practical adoption roadmap for using this repository as an **implementation accelerator**. The timeline is illustrative: organizational complexity, risk, regulatory obligations, existing controls, and certification objectives may require a different sequence or duration.

## Outcome after 90 days

The goal is to have a functioning baseline AIMS with:

- defined scope and governance;
- an AI inventory and intake process;
- an agreed risk/impact assessment method;
- lifecycle and third-party controls;
- monitoring and incident processes;
- evidence ownership;
- internal review and a prioritized improvement backlog.

It is **not** a promise of ISO/IEC 42001 certification in 90 days.

## Days 1–30 — Establish the management system

### Week 1: Scope and sponsorship

**Do**
- Identify executive sponsorship and AIMS ownership.
- Define organizational boundaries, AI activities, business units, products, locations, and interfaces that are in scope.
- Identify relevant interested parties and key obligations.

**Use**
- `01-context-and-scope/aims-scope-template.md`
- `01-context-and-scope/interested-parties-register.md`

**Evidence to retain**
- approved scope;
- sponsor/owner designation;
- interested-party review;
- decisions on exclusions or boundaries.

### Week 2: Governance and policy

**Do**
- Approve an AI policy.
- Establish governance decision rights and escalation routes.
- Define accountable business, system, technology, risk, privacy, security, and assurance roles.

**Use**
- `02-leadership-and-governance/ai-policy-template.md`
- `02-leadership-and-governance/ai-governance-charter.md`
- `02-leadership-and-governance/ai-raci-matrix.md`

**Evidence to retain**
- policy approval;
- governance terms of reference;
- RACI/role assignments;
- governance meeting decisions.

### Weeks 3–4: Inventory and baseline assessment

**Do**
- Build the first enterprise AI inventory.
- Establish a controlled intake route for new AI use cases.
- Identify high-priority systems for detailed review.
- Agree the initial risk-scoring methodology.

**Use**
- `03-ai-inventory/ai-system-register.csv`
- `03-ai-inventory/ai-use-case-intake.md`
- `04-risk-management/risk-scoring-methodology.md`
- `04-risk-management/ai-risk-register.csv`

**Milestone 30**
You can answer: **What AI do we have, who owns it, where is it used, and which systems need the most attention?**

---

## Days 31–60 — Operationalize controls

### Weeks 5–6: Risk and impact

**Do**
- Perform risk and impact assessments for prioritized systems.
- Identify affected parties, harmful outcomes, data risks, bias, transparency/explainability needs, and human oversight.
- Document risk treatment decisions and residual risk ownership.

**Use**
- `04-risk-management/ai-risk-assessment-template.md`
- `04-risk-management/risk-treatment-plan.md`
- `05-ai-impact-assessment/ai-impact-assessment.md`
- `05-ai-impact-assessment/affected-parties-assessment.md`
- `05-ai-impact-assessment/human-oversight-assessment.md`

### Week 7: Data, privacy, and bias

**Do**
- Define data quality expectations.
- Review privacy and data-use concerns.
- Identify relevant bias/fairness testing.

**Use**
- `06-data-governance/data-quality-checklist.md`
- `06-data-governance/privacy-assessment.md`
- `06-data-governance/bias-assessment.md`

### Week 8: Lifecycle and supplier governance

**Do**
- Establish design, validation, deployment, change, and retirement gates.
- Bring third-party AI into the same governance model.
- Map key risks to controls and required evidence.

**Use**
- `07-ai-lifecycle/`
- `08-third-party-ai/`
- `11-controls/control-implementation-matrix.csv`

**Milestone 60**
You can answer: **How do we decide whether an AI system may move into production, what controls are required, and who accepts residual risk?**

---

## Days 61–90 — Operate, evidence, and improve

### Weeks 9–10: Monitoring and incidents

**Do**
- Define production metrics, thresholds, review cadence, and escalation conditions.
- Establish AI-specific incident capture.
- Review overrides, complaints, harmful outcomes, drift, performance, and control failures as applicable.

**Use**
- `09-monitoring/model-monitoring-framework.md`
- `09-monitoring/ai-incident-register.csv`
- `09-monitoring/post-deployment-review.md`

### Week 11: Evidence and internal assurance

**Do**
- Assign evidence owners.
- Test whether key controls are actually operating.
- Record gaps and nonconformities.

**Use**
- `10-audit-and-assurance/evidence-register.csv`
- `10-audit-and-assurance/internal-audit-checklist.md`
- `10-audit-and-assurance/nonconformity-register.csv`

### Week 12–13: Management review and improvement backlog

**Do**
- Review AIMS performance with leadership.
- Confirm material risks, incidents, control gaps, audit findings, objectives, resources, and changes.
- Prioritize corrective actions and the next maturity cycle.

**Use**
- `10-audit-and-assurance/management-review-template.md`
- `04-risk-management/risk-treatment-plan.md`
- `11-controls/control-implementation-matrix.csv`

**Milestone 90**
You can answer: **Is our AIMS operating, what evidence proves it, what is not working, and what will we improve next?**

---

## Suggested ownership model

| Workstream | Typical accountable/lead role |
|---|---|
| Scope and AIMS governance | Executive sponsor / AIMS owner |
| AI inventory | AI governance lead / technology governance |
| Business impact | Business/use-case owner |
| AI/model risk | AI risk / model risk / independent validation |
| Data governance | Data owner / data governance |
| Privacy/legal | Privacy / legal / compliance |
| Cybersecurity | Information security |
| Supplier AI | Procurement / third-party risk + system owner |
| Lifecycle engineering | Technology / model / platform owner |
| Monitoring | System owner + risk/control owners |
| Assurance | Internal audit / independent assurance |

Actual accountability must be tailored to the organization.

## Maturity after Day 90

Move from baseline implementation to repeatable operation:

**Defined → Implemented → Evidenced → Tested → Measured → Improved**

Possible next-cycle improvements include automation of inventory/intake, control testing, centralized evidence collection, AI observability integration, vendor monitoring, metrics dashboards, regulatory mapping, training/competence records, and integration with existing risk, security, privacy, quality, or service-management systems.
