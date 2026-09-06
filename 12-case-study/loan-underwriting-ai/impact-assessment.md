# Loan Underwriting AI — Impact Assessment

## Who is affected?
Loan applicants, including applicants from groups that may experience different historical lending outcomes.

## What harm could occur?
An incorrect or unfair recommendation could contribute to denial, less favorable terms, delay, or customer frustration. At scale, systematic bias could create disparate outcomes.

## What data is being used?
For this fictional example: approved application information, financial attributes, and appropriately governed credit-history data. Any use, exclusion, retention, or analysis of sensitive or protected attributes must be determined under applicable law, policy, and the specific fairness-testing methodology; proxy effects should also be assessed.

## Is there bias?
Potentially. Historical outcomes can encode past disparities. A suitable fairness assessment should evaluate relevant outcome and error-rate disparities using data and methods that are lawful, appropriate, and governed for the jurisdiction and use case.

## Is the decision explainable?
The design should provide decision-support information that enables appropriate human understanding and review. Any customer-facing explanation or adverse-action requirement depends on the applicable jurisdiction and lending rules and is outside the scope of this fictional portfolio example.

## Is human review required?
In this fictional design, human review is required for designated adverse, high-risk, or low-confidence cases. This is a portfolio design choice, not a statement that ISO/IEC 42001 mandates this exact review rule.

## Who signs off?
Business owner, technology/model owner, independent validation, compliance/risk, and the designated governance authority.

## What monitoring happens after deployment?
Performance, drift, approval/decline distribution, group-level fairness metrics, override rates, complaints, appeals, and incidents.

## Overall classification
Classified as high impact for purposes of this fictional portfolio risk model because the system could materially influence access to financial services. This label is an internal example classification, not an ISO/IEC 42001 risk category.
