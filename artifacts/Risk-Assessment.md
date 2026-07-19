---
layout: artifact
title: AI Risk Assessment
audience: Executive Leadership, AI Governance Committee, Business and Technology Owners, GRC, Legal, Privacy, Security
classification: Public
assessment_period: 12 months
data_status: Illustrative
---

## **Purpose**  
Assess the risks associated with the proposed use case and determine whether it may proceed under defined controls and risk tolerance.

## **Assessment Information**  

**Organization:** Enterprise Company  
**Use Case:** Enterprise AI Assistant for Policy and Procedure Development  
**Jurisdiction:** United States  
**Decision State:** Deferred

## **Business Objective**

Support authorized personnel with drafting, revising, summarizing, and formatting internal policies, standards, procedures, and governance documents.

## **Scope**  
Applies to the proposed enterprise AI assistant used by authorized personnel for internal policy and procedure development in the United States.

## **Use Case**

The AI assistant:

- supports document development only;

- does not approve controlled documents;

- does not determine legal or regulatory compliance;

- does not replace policy owners or subject-matter experts;

- does not process consumer data;

- does not make employment, eligibility, or other consequential decisions.

All output remains draft and non-authoritative until formally reviewed and approved.

## **Assessment Observation**

Enterprise Company identified unapproved use of a public AI service involving nonpublic policy content.

The activity was investigated, the use case was added to the AI inventory, and the organization initiated a governed enterprise AI process for policy development.

No confirmed exposure of restricted or personal data was identified.

## **Risk Summary**

| **ID** | **Risk Scenario**                                                                                                                                                                                                                                                                 | **Risk Treatment Objective**                                                                                                                                                                                         | **Likelihood** | **Impact** | **Inherent Risk** | **Mapped Controls**        |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|------------|-------------------|------------------------|
| AI-01  | An employee uses an unapproved public AI service to process nonpublic policy content, resulting in unauthorized disclosure, loss of information control, and potential legal, security, privacy, or reputational harm.                                                            | Ensure AI use is authorized, inventoried, approved, and monitored.                                                                                                                                               | Likely         | Major      | High              | AI-C01, AI-C02, AI-C05 |
| AI-02  | Authorized personnel rely on defective AI-generated content during policy or procedure development, causing inaccurate requirements to enter controlled documents and create operational, legal, or compliance consequences.                                                      | Ensure AI-generated content is independently reviewed, validated against authoritative sources, and approved before use in controlled documents.                                                                 | Possible       | Moderate   | Medium            | AI-C03, AI-C05         |
| AI-03  | AI-generated revisions modify approved control language or intent without adequate comparison and owner review, resulting in weakened controls, audit findings, or regulatory exposure.                                                                                           | Ensure AI-generated revisions are compared, change-controlled, and approved by the control or document owner before adoption.                                                                                    | Possible       | Major      | High              | AI-C04, AI-C05         |
| AI-04  | Personnel outside the controlled document-development lifecycle rely on AI-generated summaries, explanations, or guidance as authoritative in day-to-day decisions without formal review or validation, leading to incorrect governance decisions or inconsistent implementation. | Ensure AI-generated summaries, explanations, and guidance used outside the controlled document-development lifecycle are identified as non-authoritative and validated against approved sources before reliance. | Possible       | Moderate   | Medium            | AI-C03, AI-C05         |
| AI-05  | AI-generated content is circulated, approved, or published outside the established policy lifecycle, resulting in unauthorized versions, incomplete approval evidence, unclear accountability, or recordkeeping failures.                                                         | Ensure AI-generated content follows established ownership, approval, versioning, publication, and retention requirements.                                                                                        | Possible       | Major      | High              | AI-C01, AI-C04, AI-C05 |

## **Assessment Methodology**

Likelihood estimates how often the scenario could occur during the 12-month assessment period. Impact estimates the severity of the most likely material consequence across relevant business impact dimensions. Inherent risk is assessed without credit for the planned or required controls. Ratings reflect the typical or most likely scenario based on the observed issue, available evidence, and the defined use-case boundary. Likelihood, impact, and overall risk ratings are assigned using the criteria and calculation method in the Governance Reference.

## **Risk Rating Rationale**

- **AI-01:**  Likely because unapproved AI use has already been observed; Major because disclosure could create material legal, security, privacy, and reputational consequences.

- **AI-02:**  Possible because generative output can be inaccurate or incomplete; Moderate because the typical scenario could introduce incorrect requirements into controlled documents, requiring corrective action and potentially creating operational or compliance consequences.

- **AI-03:**  Possible because AI-generated revisions can alter approved language; Major because changed control intent can create control failure, audit findings, or regulatory exposure.

- **AI-04:**  Possible because personnel may rely on AI-generated summaries or explanations outside the formal document-development process; Moderate because incorrect guidance could cause inconsistent governance decisions or implementation and require corrective action.

- **AI-05:**  Possible because generated content may be circulated outside the policy lifecycle; Major because unauthorized publication can create inconsistent requirements, weak accountability, and recordkeeping failures.

## **Human Impact Review**

The assistant does not directly make decisions about individuals.

Indirect harm could occur if inaccurate, misleading, difficult-to-use, or unauthorized content enters approved policies and affects employees or other stakeholders.

Required safeguards include:

- accountable human ownership;

- independent review and validation;

- review for usability and unintended impact where relevant;

- formal approval before publication.

## **Human Impact Rating:** Medium

Human-impact findings inform the impact assessment for **AI-02**, **AI-04**, and **AI-05** and must be reassessed before approval.

## **Required Controls**

Enterprise Company requires:

- use of an approved enterprise AI platform;

- registration of the use case in the AI inventory;

- access limited to authorized personnel;

- restrictions on entering sensitive information;

- clear labeling of AI-generated content as draft;

- validation against authoritative sources;

- policy-owner and subject-matter review;

- documented change control;

- retention of approval and publication evidence;

- user training;

- monitoring for misuse and material change.

## **Control Contribution to Risk Treatment**

- **AI-C01:**  Reduces likelihood by establishing authorized-use rules, accountability, and governance requirements.

- **AI-C02:**  Reduces likelihood by requiring inventory, ownership, assessment, and approval before use.

- **AI-C03:**  Reduces likelihood and impact by requiring qualified human review and validation before approval or publication.

- **AI-C04:**  Reduces likelihood and impact by protecting approved control intent through comparison, change control, versioning, approval, and retention.

- **AI-C05:**  Reduces impact by enabling timely detection, corrective action, and escalation for misuse, control failure, exceptions, incidents, and material change.

## **Risk Determination**

**Overall Inherent Risk:** High

**Current Risk:** High. Required controls have not been fully implemented and validated

**Target Residual Risk:** Medium following control implementation and validation

**Risk Response:** Mitigate

**Risk Owner:** Business Owner for Policy and Procedure Development

**Risk Oversight:** GRC

**Approval Authority:** Executive Leadership

**Decision State:** Deferred

## **Decision Basis**

The use case is deferred because the identified governance controls have not yet been fully implemented and validated.

The use case may be reconsidered for approval once **AI-C01** through **AI-C05** are operating as intended, target residual risk is confirmed as Medium, and the defined risk tolerance and control performance targets are met.

## **Conditions for Approval**

- Implement and validate **AI-C01** through **AI-C05**.

- Confirm human review and validation before approval or publication.

- Confirm document change control, monitoring, exception, and escalation processes are operating.

- Complete the risk and human-impact reassessment.

- Confirm target residual risk is Medium and all defined risk tolerance and control performance targets are met.

## **Review Triggers**

Reassessment is required if there is a material change to:

- the business purpose;

- AI platform or integrations;

- data processed;

- user population;

- level of automation;

- decision authority;

- applicable legal requirements;

- use involving consumer data or consequential decisions.

## **Related Artifacts**

- [AI Governance Policy](Policy.md)
- [AI Governance Operating Model](Operating-Model.md)
- [Governance Workflow](Workflow.md)
- [Exceptions and Escalation Process](Exceptions-and-Escalation.md)
- [Control Crosswalk](Control-and-Framework-Crosswalk.md)

## **References**  

See: [References](References.md)

---  

**Tom Kowalski**  
Senior GRC & Cybersecurity Advisor  
*AI Governance, Enterprise Risk, Information Security*

LinkedIn: <https://www.linkedin.com/in/kowalskitom1>

© 2026 Tom Kowalski. All rights reserved.

*Enterprise Company is a fictional organization created solely for portfolio demonstration purposes. This document contains original work and does not represent any client, employer, or commercial implementation.*
