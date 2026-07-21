# Third-Party AI Contract & Onboarding Requirements

## Executive Summary

Third-Party AI Due Diligence determines whether sufficient evidence exists to support provider suitability, while Third-Party AI Risk Assessment identifies provider-originated risks requiring enterprise governance.

Before a third-party AI relationship becomes operational, Megastar Mortgage must ensure that approved governance requirements are reflected in the contractual arrangement and that all required onboarding conditions have been satisfied.

The Third-Party AI Contract & Onboarding Requirements establish the governance conditions that must be addressed before an external AI product, service, model, platform, application programming interface, or managed service may support the Megastar Intelligent Processor (MIP).

This artifact does not draft or negotiate legal agreements, perform procurement sourcing, repeat due diligence, reassess provider risks, or approve residual-risk acceptance. It defines the governance requirements that Legal & Compliance, Procurement, Privacy, Security, Technology, Risk, and business stakeholders must confirm before onboarding and approved use.

---

## Purpose

The purpose of this document is to establish a standardized approach for defining, reviewing, and approving third-party AI contractual and onboarding requirements.

This artifact enables Megastar Mortgage to:

- translate due-diligence conditions and provider-originated risks into contractual and onboarding requirements;
- define the minimum governance obligations applicable to the provider relationship;
- confirm that permitted and prohibited uses are documented;
- establish privacy, data-governance, security, transparency, assurance, incident, change, resilience, and exit obligations;
- identify requirements that must be completed before operational use;
- distinguish mandatory requirements from conditional or risk-based requirements;
- record exceptions, unresolved conditions, and escalation needs;
- determine whether the relationship is ready for onboarding;
- update the Enterprise Third-Party AI Register with approved contractual and onboarding outcomes; and
- establish the formal handoff into Third-Party AI Oversight.

Completion of this activity confirms whether the third-party AI relationship may proceed into operational use and under what conditions.

---

## Contract and Onboarding Process

Every third-party AI relationship approved to proceed beyond risk assessment follows a consistent contract and onboarding governance process.

```mermaid
flowchart LR

A[Third-Party AI Due Diligence]
--> B[Third-Party AI Risk Assessment]
--> C[Contract Requirements Defined]
--> D[Contractual Coverage Confirmed]
--> E[Onboarding Conditions Reviewed]
--> F[Readiness Decision]
--> G[Enterprise Third-Party AI Register Updated]
--> H[Third-Party AI Oversight]
```

Contractual readiness and onboarding readiness are related but distinct.

A contract may be executed while onboarding conditions remain incomplete. Operational use shall not begin until the applicable onboarding decision has been approved.

---

## Governance Principles

Megastar Mortgage establishes Third-Party AI Contract & Onboarding Requirements according to the following principles:

- Third-party AI use shall not begin until mandatory governance requirements have been addressed.
- Contractual obligations shall reflect the intended use, provider dependency, due-diligence outcome, linked risks, and applicable legal or regulatory obligations.
- Governance requirements shall be proportionate to the relationship’s operational significance and data exposure.
- Due-diligence conditions requiring contractual protection shall remain traceable to the relevant contract requirement.
- Provider-originated risks requiring contractual treatment shall remain traceable to the Enterprise AI Risk Register.
- Contractual provisions shall support governance but shall not transfer Megastar Mortgage’s accountability for the AI system.
- Contract execution shall not, by itself, establish onboarding readiness.
- Conditional onboarding shall include specific, approved, time-bound, and monitored conditions.
- Contractual or onboarding exceptions shall be approved through established decision rights.
- Material limitations shall be documented rather than treated as implicitly accepted.
- Operational use shall remain restricted to approved purposes, users, data, systems, and environments.
- Contract and onboarding records shall remain traceable throughout oversight, renewal, change, incident, and exit activities.

---

## Contract Requirement Sources

Third-party AI contractual and onboarding requirements are derived from approved governance information, including:

- Third-Party AI Identification;
- Enterprise Third-Party AI Register;
- Third-Party AI Due Diligence;
- Third-Party AI Risk Assessment;
- Enterprise AI Risk Register;
- approved AI Risk Response Strategies;
- Enterprise AI Control Register;
- internal policies and standards;
- privacy and data-governance requirements;
- security requirements;
- legal and regulatory obligations;
- procurement requirements;
- business-continuity requirements;
- assurance requirements;
- incident-management requirements;
- change-management requirements; and
- exit and transition requirements.

This artifact consolidates applicable governance requirements without replacing the source activity that established them.

---

## Requirement Classification

Each requirement is classified according to its governance significance.

| Requirement Classification | Meaning |
|---|---|
| Mandatory Before Contract Execution | Must be resolved before the agreement is executed. |
| Mandatory Before Onboarding | Must be resolved before the product or service becomes operational. |
| Conditional Post-Onboarding | May be completed after limited or conditional onboarding under approved restrictions and oversight. |
| Ongoing Contractual Obligation | Must be maintained throughout the provider relationship. |
| Renewal Requirement | Must be reviewed or refreshed before continuation or renewal. |
| Exit Requirement | Must be available or completed when the relationship is terminated or transitioned. |
| Not Applicable | Does not apply to the relationship, with documented rationale. |

A requirement may have more than one classification where it applies at different lifecycle stages.

---

## Contract Requirement Domains

### 1. Governance and Accountability

Contractual requirements may address:

- provider accountability for the contracted AI product or service;
- named provider governance contacts;
- responsibilities of Megastar Mortgage and the provider;
- cooperation with AI governance reviews;
- compliance with agreed governance standards;
- maintenance of appropriate AI governance policies;
- provider responsibility for subcontracted services;
- obligation to provide accurate and current governance information;
- escalation contacts;
- governance decision rights;
- record-retention responsibilities; and
- cooperation with regulatory, audit, assurance, incident, and change-management activities.

---

### 2. Permitted and Prohibited Use

Contractual requirements shall define:

- approved business purposes;
- authorized users and functions;
- approved systems and environments;
- permitted data categories;
- prohibited data categories;
- prohibited use cases;
- geographic or jurisdictional restrictions;
- customer-facing or decision-making restrictions;
- restrictions on autonomous action;
- human-oversight expectations;
- restrictions on model training or fine-tuning;
- restrictions on secondary use;
- limitations on onward disclosure; and
- consequences of unauthorized or prohibited use.

Operational use shall remain within the approved scope recorded in the Enterprise Third-Party AI Register.

---

### 3. Privacy and Data Governance

Requirements may address:

- data ownership;
- authorized processing purpose;
- lawful and permitted data use;
- data minimization;
- confidentiality;
- secondary-use restrictions;
- provider use of customer data for training;
- retention periods;
- deletion requirements;
- deletion certification;
- data return;
- data residency;
- cross-border transfers;
- subprocessor access;
- data-subject rights support;
- data lineage and provenance;
- data-quality responsibilities;
- de-identification or anonymization;
- auditability of data use;
- handling of personal, confidential, and sensitive information; and
- survival of data obligations after termination.

---

### 4. Security and Access Control

Requirements may address:

- identity and access management;
- least-privilege access;
- privileged-access controls;
- authentication requirements;
- encryption in transit and at rest;
- logging and audit trails;
- vulnerability management;
- secure development;
- security testing;
- credential and secret management;
- tenant isolation;
- environment segregation;
- network-security requirements;
- access-review requirements;
- breach notification;
- evidence preservation;
- remediation obligations; and
- security cooperation during investigation and recovery.

---

### 5. Product, Model, and Service Transparency

Requirements may address provider obligations to supply and maintain:

- product or service documentation;
- intended-use documentation;
- prohibited-use information;
- model or service limitations;
- performance information;
- validation information;
- robustness information;
- fairness information where relevant;
- explainability support;
- model or service dependencies;
- release notes;
- version information;
- customer responsibilities;
- known limitations;
- material changes;
- incident-related disclosures; and
- documentation necessary for governance, audit, assurance, and regulatory review.

---

### 6. Model and Service Performance

Requirements may address:

- service-performance commitments;
- model-performance expectations;
- accuracy or error-rate commitments where appropriate;
- reliability requirements;
- service availability;
- response times;
- capacity and scalability;
- quality thresholds;
- performance-reporting obligations;
- failure-handling responsibilities;
- issue-resolution timelines;
- degradation notification;
- drift-related notification where applicable;
- service credits or remedies; and
- escalation for persistent underperformance.

Performance terms shall reflect the intended use and shall not imply that provider commitments replace Megastar Mortgage’s own validation and oversight.

---

### 7. Audit, Assurance, and Evidence Rights

Requirements may address:

- right to request governance evidence;
- right to receive independent assurance reports;
- right to review relevant certifications and attestations;
- right to inspect relevant controls or records;
- right to perform or commission assurance activities;
- right to receive remediation information;
- right to review material exceptions;
- provider cooperation with internal audit;
- provider cooperation with regulators;
- evidence-retention periods;
- evidence-access restrictions;
- notification of qualified or expired assurance reports; and
- escalation where sufficient assurance information is unavailable.

Audit and assurance rights shall be proportionate to the relationship and applicable legal constraints.

---

### 8. Incident Notification and Cooperation

Requirements may address:

- incident definition;
- notification triggers;
- notification timelines;
- severity-based escalation;
- initial and ongoing notification content;
- containment and recovery cooperation;
- evidence preservation;
- investigation support;
- regulatory-notification support;
- customer and stakeholder communication support;
- root-cause information;
- corrective-action obligations;
- post-incident review;
- historical incident disclosure;
- notification of subprocessor incidents; and
- continued updates until resolution.

Detailed incident investigation remains within AI Incident Management.

---

### 9. Material Change Notification

Requirements may address advance or prompt notification of:

- model changes;
- model substitutions;
- service changes;
- feature changes;
- hosting changes;
- data-processing changes;
- security changes;
- ownership or control changes;
- subprocessor changes;
- jurisdiction changes;
- licensing changes;
- policy changes;
- discontinued functionality;
- changes to assurance status;
- material performance changes;
- material incidents;
- regulatory actions; and
- changes affecting contractual compliance.

Material changes may trigger reassessment through AI Change Management and other relevant governance capabilities.

---

### 10. Subprocessors and Fourth Parties

Requirements may address:

- disclosure of material subprocessors;
- prior approval or notification;
- geographic location;
- services performed;
- data and system access;
- contractual flow-down;
- security and privacy obligations;
- provider oversight;
- incident notification;
- change notification;
- audit rights;
- replacement rights;
- objection rights;
- concentration concerns; and
- accountability for fourth-party performance.

---

### 11. Resilience and Business Continuity

Requirements may address:

- availability commitments;
- recovery objectives;
- disaster recovery;
- backup arrangements;
- continuity planning;
- resilience testing;
- capacity management;
- outage notification;
- recovery communication;
- dependency resilience;
- service restoration;
- geographic redundancy;
- continuity support during provider distress;
- financial-stability notification;
- transition support during prolonged disruption; and
- access to necessary data and records during an outage.

---

### 12. Regulatory and Legal Cooperation

Requirements may address:

- compliance with applicable laws and regulations;
- cooperation with regulatory inquiries;
- provision of required documentation;
- preservation of records;
- support for regulatory assessments;
- notification of regulatory action;
- notification of material litigation;
- licensing and intellectual-property obligations;
- legal hold support;
- jurisdictional requirements;
- audit and inspection rights;
- confidentiality exceptions required by law; and
- assistance with customer or regulatory notifications.

---

### 13. Intellectual Property and Licensing

Requirements may address:

- ownership of inputs and outputs;
- ownership of custom configurations;
- ownership of fine-tuned models;
- rights to prompts and workflows;
- training-data rights;
- licensing restrictions;
- infringement responsibilities;
- use of generated content;
- indemnification;
- open-source dependencies;
- portability rights;
- continued-use rights during transition; and
- survival of intellectual-property obligations after termination.

---

### 14. Exit and Transition

Requirements may address:

- termination rights;
- suspension rights;
- termination for governance failure;
- transition assistance;
- replacement-provider cooperation;
- data export;
- data return;
- data deletion;
- deletion certification;
- portability of configurations, prompts, records, and documentation;
- access revocation;
- integration removal;
- operational continuity;
- evidence retention;
- unresolved incident or corrective-action obligations;
- post-termination cooperation;
- exit timelines;
- exit charges; and
- obligations that survive termination.

---

## Onboarding Requirements

Contractual coverage alone does not establish onboarding readiness.

Before operational use begins, Megastar Mortgage confirms that applicable onboarding conditions have been satisfied.

Onboarding requirements may include:

- provider relationship recorded in the Enterprise Third-Party AI Register;
- related AI system recorded in the Enterprise AI System Inventory;
- due diligence completed and approved;
- provider-originated risks entered into the Enterprise AI Risk Register;
- required risk analysis, prioritization, and response decisions completed;
- required control objectives and controls established;
- contractual requirements approved;
- agreement executed;
- permitted and prohibited uses communicated;
- security integration approved;
- privacy and data-processing requirements approved;
- access roles defined;
- provider and internal contacts established;
- service configuration reviewed;
- logging and evidence requirements established;
- incident escalation routes established;
- change-notification process established;
- oversight frequency defined;
- required training completed;
- exit and transition requirements established;
- conditional onboarding requirements documented; and
- onboarding approval recorded.

---

## Conditional Onboarding

Conditional onboarding may be permitted only where:

- remaining requirements do not create unacceptable exposure;
- the permitted scope is clearly restricted;
- the relevant risk and governance authorities approve the condition;
- compensating measures exist where required;
- the condition has an accountable owner;
- the condition has a target completion date;
- enhanced oversight is established where appropriate;
- escalation triggers are defined;
- production or sensitive-data use is restricted where necessary; and
- failure to satisfy the condition results in suspension, restriction, or reassessment.

Conditional onboarding does not constitute residual-risk acceptance.

---

## Contractual and Onboarding Exceptions

Where a mandatory requirement cannot be satisfied, the exception shall document:

- the requirement not met;
- the reason it cannot be met;
- the related due-diligence concern;
- the related provider-originated risk;
- the affected AI system and intended use;
- proposed compensating measures;
- duration of the exception;
- required oversight;
- accountable owner;
- approval authority;
- expiry date;
- reassessment trigger; and
- consequence if the exception is not resolved.

Exceptions shall be approved according to established governance decision rights.

An exception shall not be treated as an informal waiver or implied acceptance.

---

## Onboarding Readiness Outcomes

The contract and onboarding review results in one of the following outcomes.

| Readiness Outcome | Meaning |
|---|---|
| Ready for Onboarding | Mandatory contractual and onboarding requirements have been satisfied and approved use may begin. |
| Conditionally Ready | Limited or restricted onboarding may proceed subject to documented and approved conditions. |
| Not Ready | One or more mandatory governance requirements remain unsatisfied and operational use shall not begin. |
| Deferred | The onboarding decision has been postponed pending additional information, organizational decision, contract negotiation, risk treatment, or provider action. |
| Rejected | The relationship shall not proceed under the proposed use or current contractual arrangement. |

A readiness outcome does not replace procurement approval or any separately required legal authorization.

---

## Enterprise Third-Party AI Register Enrichment

Approved Contract & Onboarding outcomes update the following fields within the Enterprise Third-Party AI Register:

| Register Field | Information Added |
|---|---|
| Contract Reference | Reference to the executed or governing agreement. |
| Contract Status | Current contractual lifecycle status. |
| Contract Effective Date | Date contractual obligations begin. |
| Contract Expiry Date | Date contractual obligations expire or require renewal. |
| Permitted and Prohibited Uses Defined | Whether approved-use boundaries are documented. |
| Data Ownership and Use Terms Defined | Whether data rights and restrictions are established. |
| Data Residency Terms Defined | Whether residency requirements are established where applicable. |
| Data Retention and Deletion Terms Defined | Whether lifecycle obligations are established. |
| Security Obligations Defined | Whether security requirements are contractually addressed. |
| Subprocessor Notification or Approval Rights Defined | Whether dependency-governance rights are established. |
| Audit and Assurance Rights Defined | Whether evidence and review rights are established. |
| Incident Notification Obligations Defined | Whether provider notification requirements are established. |
| Material Change Notification Defined | Whether provider change obligations are established. |
| Service-Level Commitments Defined | Whether operational-performance requirements are established. |
| Business Continuity Obligations Defined | Whether resilience requirements are established. |
| Regulatory Cooperation Obligations Defined | Whether regulatory-support requirements are established. |
| Exit Assistance Defined | Whether exit-support obligations are established. |
| Data Portability Requirements Defined | Whether transition and portability obligations are established. |
| Onboarding Conditions Established | Whether onboarding conditions have been documented. |
| Onboarding Conditions Satisfied | Current condition-satisfaction status. |
| Onboarding Approval Status | Approved, Conditional, Rejected, or Pending. |
| Approved Use Date | Date authorized operational use may begin. |
| Onboarding Approval Reference | Reference to the authoritative onboarding decision. |

Detailed clauses, negotiation records, legal analysis, and approvals remain within their authoritative contract and governance records.

---

## Contract and Onboarding Review

Before the readiness decision is approved, Megastar Mortgage confirms that:

- due diligence is complete and current;
- provider-originated risks have been transferred appropriately;
- applicable risk response decisions are available;
- contractual requirements are traceable to governance sources;
- mandatory contractual provisions have been addressed;
- required Legal & Compliance, Procurement, Privacy, Security, Technology, Risk, and business reviews are complete;
- mandatory onboarding conditions are satisfied;
- unresolved conditions and exceptions are documented;
- permitted and prohibited uses are clear;
- accountability and escalation paths are defined;
- oversight requirements are established;
- exit and transition obligations are addressed;
- the proposed readiness outcome is supported; and
- required Enterprise Third-Party AI Register updates are complete.

---

## Approval and Decision Rights

The onboarding decision shall be approved by the authority appropriate to the relationship’s criticality, risk, intended use, and organizational decision rights.

Approval may require participation from:

- Business Relationship Owner;
- AI Governance Lead;
- Procurement;
- Legal & Compliance;
- Privacy;
- Security;
- Technology;
- Enterprise Risk;
- model or system owner;
- executive sponsor; and
- designated governance committee.

No single function shall approve the relationship on behalf of all governance stakeholders where cross-functional approval is required.

---

## Contract and Onboarding Maintenance

Contractual and onboarding requirements shall be reviewed when:

- the intended use changes;
- the provider introduces a new model, service, or material feature;
- provider-originated risks change;
- contract renewal or renegotiation occurs;
- material subprocessors change;
- applicable legal or regulatory obligations change;
- security or privacy requirements change;
- a material provider incident occurs;
- service performance deteriorates;
- assurance documentation changes or expires;
- an onboarding condition becomes overdue;
- a material exception is requested;
- AI Change Management triggers reassessment;
- exit planning is initiated; or
- the current contract no longer supports appropriate governance.

Material changes shall be reflected in the Enterprise Third-Party AI Register.

---

## Why This Document Matters

Provider suitability and risk assessment do not, by themselves, establish enforceable governance obligations.

Without clear contractual and onboarding requirements, organizations may rely on external AI providers without adequate rights to information, assurance, incident notification, change notification, data protection, service continuity, regulatory cooperation, or exit support.

The Third-Party AI Contract & Onboarding Requirements convert governance expectations into enforceable relationship conditions and establish the final operational gate before approved third-party AI use begins.

This ensures that Megastar Mortgage does not onboard an external AI provider merely because the technology is available or a commercial agreement has been reached.

---

## Related Artifacts

This document supports:

- Third-Party AI Contract & Onboarding Requirements Template
- Enterprise Third-Party AI Register
- Third-Party AI Due Diligence
- Third-Party AI Risk Assessment
- Enterprise AI Risk Register
- Enterprise AI Control Register
- Third-Party AI Oversight
- Third-Party AI Exit & Transition Plan

---

## Document Control

| Field | Value |
|---|---|
| Document | Third-Party AI Contract & Onboarding Requirements |
| Capability | Third-Party AI Governance |
| Repository | Enterprise AI Governance Playbook |
| Reference Organization | Megastar Mortgage |
| Reference AI System | Megastar Intelligent Processor (MIP) |
| Document Owner | AI Governance Lead |
| Version | 1.0 |
| Review Cycle | Annual |
| Status | Published Reference |

---

## Revision History

| Version | Date | Description |
|---|---|---|
| 1.0 | July 2026 | Initial release of the Third-Party AI Contract & Onboarding Requirements artifact. |