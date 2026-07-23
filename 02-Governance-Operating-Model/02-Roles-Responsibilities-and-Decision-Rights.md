# Roles, Responsibilities and Decision Rights

> **Artifact Type:** Governance Standard  
> **Capability:** Governance Operating Model  
> **Reference Organization:** Megastar Mortgage  
> **Reference AI System:** Megastar Intelligent Processor (MIP)  
> **Authoritative Record:** No  
> **Document Owner:** AI Governance Lead  
> **Version:** 2.0  
> **Status:** Published Reference Implementation  
> **Review Cycle:** Annual  

---

# Purpose

This document defines the standing governance responsibilities and formal decision authority used to govern MIP.

It establishes:

- what each governance function is expected to do;
- which functions own operational, technical, risk, control, privacy, security, legal, compliance, third-party, and assurance responsibilities;
- which roles or forums may approve, reject, accept, escalate, suspend, or retire governance matters;
- how responsibility, accountability, coordination, challenge, and assurance remain separated.

This document does not assign activity-level RACI designations. Those assignments are maintained in the [AI Governance RACI Matrix](03-AI-Governance-RACI-Matrix.md).

---

# Responsibility Model

## Executive Sponsor

The Executive Sponsor:

- provides executive sponsorship for the AI governance program;
- supports strategic alignment and resource prioritization;
- receives material escalations;
- sponsors management review;
- supports resolution where delegated authority is exceeded;
- remains accountable for enterprise-level governance sponsorship, not day-to-day operation.

## Mortgage Operations

Mortgage Operations:

- owns the business process supported by MIP;
- defines intended business use and operational requirements;
- remains accountable for AI-enabled business outcomes;
- confirms that MIP remains appropriate for the supported process;
- owns business-process controls;
- assigns business risk owners;
- sponsors remediation affecting mortgage operations;
- determines whether operational use should continue within delegated authority.

## Mortgage Processing Team

The Mortgage Processing Team:

- uses MIP within approved workflows;
- follows documented operating procedures;
- reviews and processes documents within assigned responsibilities;
- reports exceptions, defects, and operational concerns;
- preserves required evidence;
- supports incident, monitoring, and change activities where operational input is required.

## AI Governance Lead

The AI Governance Lead:

- coordinates the enterprise AI governance process;
- maintains governance consistency across capabilities;
- facilitates governance reviews and decision preparation;
- maintains repository and process standards;
- supports evidence traceability;
- coordinates governance forums;
- monitors completion of governance obligations;
- escalates unresolved or overdue matters;
- does not automatically own business, technical, risk, privacy, security, legal, or assurance decisions.

## AI Platform Team

The AI Platform Team:

- operates and maintains MIP;
- manages platform reliability, availability, integration, and technical support;
- implements approved technical controls;
- maintains technical evidence;
- supports incidents, monitoring, and changes;
- coordinates with Data & AI Engineering on system and model changes;
- does not independently approve material business use or residual risk.

## Data & AI Engineering

Data & AI Engineering:

- develops, configures, tests, and maintains AI capabilities;
- manages models, rules, data pipelines, and technical configurations;
- documents technical changes;
- supports validation and retraining;
- investigates technical root causes;
- implements approved technical remediation;
- provides evidence for assurance and monitoring.

## Human-in-the-Loop Specialists

Human-in-the-Loop Specialists:

- review MIP outputs where human validation is required;
- correct, reject, or escalate inaccurate or uncertain outputs;
- process low-confidence and exception scenarios;
- follow approved override procedures;
- preserve review evidence;
- escalate patterns indicating possible drift, bias, control failure, or process weakness.

## Quality Assurance

Quality Assurance:

- performs operational quality review;
- applies approved sampling and validation methods;
- identifies processing defects and adverse trends;
- distinguishes system errors from user errors where evidence supports that conclusion;
- supports root-cause analysis;
- escalates material quality concerns;
- remains separate from Internal Audit and independent assurance.

## Risk Management

Risk Management:

- establishes or applies enterprise risk methodology;
- facilitates and challenges AI risk assessment;
- supports risk aggregation and prioritization;
- reviews risk treatment and residual-risk rationale;
- monitors material risk exposure;
- escalates risks exceeding tolerance or delegated authority;
- does not automatically own business risk or accept residual risk on behalf of the business owner.

## Privacy Office

The Privacy Office:

- interprets privacy requirements;
- evaluates personal-data processing;
- reviews lawful-use, minimization, retention, access, and data-subject implications;
- identifies privacy risks and required conditions;
- approves privacy-specific exceptions within delegated authority;
- escalates matters that cannot be lawfully waived.

## Information Security

Information Security:

- defines and reviews security requirements;
- evaluates access control, resilience, vulnerability, logging, and threat exposure;
- approves security-specific exceptions within delegated authority;
- supports incident response;
- challenges technical security evidence;
- escalates material security concerns.

## Legal & Compliance

Legal & Compliance:

- interprets legal, regulatory, contractual, and policy requirements;
- advises on obligations affecting MIP;
- reviews material legal and compliance impacts;
- determines whether a requirement is internally waivable;
- supports regulatory and contractual response;
- does not transfer legal accountability to AI Governance.

## Procurement / Third-Party Management

Procurement / Third-Party Management:

- coordinates provider onboarding;
- supports commercial and contractual due diligence;
- maintains provider-governance evidence;
- supports ongoing provider oversight;
- tracks contractual obligations;
- supports exit and transition planning;
- works with Privacy, Security, Legal & Compliance, Risk Management, and business ownership.

## Internal Audit

Internal Audit:

- provides independent assurance over governance and control effectiveness;
- evaluates whether governance operates as intended;
- reports findings to appropriate oversight bodies;
- preserves independence from operational ownership;
- does not design controls, implement remediation, or accept management risk.

---

# Shared Governance Expectations

All governance participants are expected to:

- perform assigned responsibilities within delegated authority;
- preserve complete and accurate evidence;
- participate in required reviews;
- escalate material issues promptly;
- support controlled handoffs;
- avoid duplicating authoritative records;
- maintain confidentiality and data-handling obligations;
- support continual improvement without diluting accountability.

Shared participation does not mean shared accountability.

---

# Decision-Rights Principles

Decision rights follow these rules:

- the function accountable for the underlying business, technical, privacy, security, legal, or governance matter retains the related approval authority;
- each decision must have a clearly identified decision authority;
- consultation does not transfer accountability;
- AI Governance coordinates and records decisions but does not automatically own them;
- Risk Management challenges risk decisions but does not automatically accept business risk;
- legal and regulatory obligations cannot be waived through an internal governance exception;
- material decisions must be documented in an authoritative decision record;
- decisions exceeding delegated authority must be escalated.

---

# Governance Decision Authority

| Governance Decision | Decision Authority |
|---|---|
| Accept a proposed AI initiative into the governance lifecycle | Executive Sponsor or delegated governance authority |
| Approve the intended business use of MIP | Mortgage Operations |
| Approve material business-process changes supported by MIP | Mortgage Operations |
| Approve material technical implementation or platform change | AI Platform Team or designated technical authority |
| Approve production deployment of a material change | Mortgage Operations and designated technical authority, after required governance reviews |
| Approve enterprise AI governance policy or standard | Designated policy owner or governance committee |
| Approve repository and process documentation changes | AI Governance Lead within delegated authority |
| Accept residual business risk | Accountable Risk Owner within delegated authority |
| Escalate residual risk above delegated authority | Appropriate executive or governance forum |
| Approve privacy-specific exceptions | Privacy Office within delegated authority |
| Approve security-specific exceptions | Information Security within delegated authority |
| Approve a governance-process exception | Owner of the requirement being modified |
| Determine whether a legal or regulatory obligation may be modified | Legal & Compliance |
| Approve third-party onboarding | Business Owner and Procurement / Third-Party Management, subject to required specialist reviews |
| Approve significant corrective or remediation actions | Accountable management owner |
| Approve closure of assurance findings | Accountable management owner, subject to assurance validation where required |
| Approve continued operation after a material incident | Mortgage Operations and relevant specialist authorities |
| Approve MIP retirement | Mortgage Operations with Executive Sponsor and required technical and governance input |

---

# Residual-Risk Acceptance

Residual risk is accepted by the accountable Risk Owner within delegated authority.

Risk Management:

- reviews methodology;
- provides independent challenge;
- confirms whether the assessment is sufficiently supported;
- escalates risk exceeding tolerance.

Risk Management does not automatically become the Risk Owner.

Residual-risk decisions must identify:

- the Risk Owner;
- the residual-risk level;
- the evidence considered;
- the acceptance period;
- any conditions;
- the review date;
- the escalation path.

---

# Governance Exceptions

A governance exception is a time-bound deviation from an internal governance requirement.

Exception authority belongs to the owner of the requirement being modified.

Examples include:

| Exception Type | Decision Authority |
|---|---|
| Privacy requirement | Privacy Office |
| Security requirement | Information Security |
| Business-control requirement | Accountable business or control owner |
| Governance-process requirement | AI Governance Lead or designated process owner |
| Policy requirement | Policy owner |
| Contractual requirement | Legal & Compliance and Procurement / Third-Party Management |
| Legal or regulatory obligation | Not internally waivable without Legal & Compliance determination |

Every approved exception must include:

- rationale;
- scope;
- compensating measures;
- owner;
- approval authority;
- start date;
- expiry date;
- review conditions;
- closure or renewal decision.

---

# Escalation Triggers

A matter must be escalated when:

- risk exceeds delegated tolerance;
- a stakeholder lacks authority to decide;
- there is material disagreement;
- a legal, privacy, security, or compliance concern remains unresolved;
- a control failure could materially affect customers or operations;
- a material incident occurs;
- a required action is overdue or ineffective;
- a provider fails to meet material obligations;
- continued use of MIP may no longer be appropriate.

Detailed escalation pathways and forum handling are defined in [Governance Forums and Escalation](04-Governance-Forums-and-Escalation.md).

---

# Responsibility and Authority Boundaries

This document owns:

- standing governance responsibilities;
- formal decision authority;
- residual-risk authority principles;
- exception-authority principles;
- escalation triggers.

This document does not own:

- activity-level RACI assignments;
- meeting cadence;
- forum terms of reference;
- lifecycle stage design;
- operational procedures;
- individual risk records;
- control implementation records;
- assurance findings;
- monitoring thresholds;
- incident or change registers.

Those matters are governed by the related capability artifacts.

---

# Related Artifacts

- [AI Governance Operating Model](01-AI-Governance-Operating-Model.md)
- [AI Governance RACI Matrix](03-AI-Governance-RACI-Matrix.md)
- [Governance Forums and Escalation](04-Governance-Forums-and-Escalation.md)
- [Governance Lifecycle](05-Governance-Lifecycle.md)
- [Performance and Reporting](06-Performance-and-Reporting.md)
- [AI Governance Stakeholder Model](../01-Foundations/03-AI-Governance-Stakeholder-Model.md)
- [Governance Glossary](../00-Governance-Glossary.md)

---

# Revision History

| Version | Date | Description |
|---|---|---|
| 1.0 | July 2026 | Initial release of the Roles and Responsibilities and Decision Rights artifacts. |
| 2.0 | July 2026 | Consolidated responsibilities and decision authority, corrected risk and exception ownership, and aligned terminology with the repository constitution. |