# AI Change Management Framework

## Executive Summary

AI systems continue to evolve after approval. Models are retrained, data sources change, providers release new versions, prompts and rules are updated, controls are redesigned, and business teams expand how AI is used.

The AI Change Management Framework establishes how Megastar Mortgage governs material changes involving the Megastar Intelligent Processor (MIP) and other governed AI systems.

It defines the operating model, lifecycle, roles, decision rights, change classifications, governance consultation, implementation controls, verification expectations, emergency-change boundary, and cross-capability handoffs required to manage AI changes consistently.

This framework does not document individual change requests, conduct detailed impact assessments, approve specific changes, define test cases, or perform post-implementation reviews. Those activities are governed through later artifacts within this capability.

---

## Purpose

The purpose of this framework is to establish a consistent and auditable governance model for AI-related change.

It enables Megastar Mortgage to:

- identify changes requiring AI governance review;
- record each governed change in an authoritative register;
- assess materiality before implementation;
- involve the appropriate governance capabilities;
- assign accountable ownership;
- route approval to the correct authority;
- distinguish implementation from successful validation;
- govern emergency changes without removing accountability;
- update affected governance records; and
- close changes only after required verification and review.

---

## Framework Scope

This framework applies to proposed, approved, emergency, implemented, reversed, provider-initiated, and retirement changes involving:

- AI models or model versions;
- externally supplied AI services;
- prompts, rules, thresholds, or configurations;
- training, validation, operational, or monitoring data;
- data sources and data flows;
- automation levels;
- human-oversight requirements;
- controls;
- monitoring indicators or thresholds;
- business processes;
- approved-use boundaries;
- users or affected populations;
- system integrations;
- infrastructure or deployment environments;
- providers or subprocessors;
- privacy, security, legal, regulatory, or contractual obligations;
- fallback or continuity arrangements; and
- suspension, replacement, or retirement.

Routine administrative changes may remain within enterprise change processes where documented criteria confirm that no material AI governance impact exists.

---

## Framework Boundary

### AI Change Management owns

- the AI change lifecycle;
- governed change registration;
- change classification;
- materiality and impact review;
- governance consultation;
- approval routing;
- implementation governance;
- change evidence;
- verification and validation requirements;
- emergency-change governance;
- post-implementation review;
- change closure; and
- related governance-record updates.

### AI Change Management does not own

- software-development methodology;
- technical release execution;
- cybersecurity change control;
- privacy review;
- risk assessment;
- control design;
- assurance testing;
- provider relationship decisions;
- incident investigation;
- residual-risk acceptance; or
- management review.

Those activities remain with their established owners.

---

## Governance Objectives

The framework is designed to ensure that every material AI change is:

- identified before implementation where practicable;
- recorded in the Enterprise AI Change Register;
- assessed proportionately;
- assigned to an accountable Change Owner;
- reviewed by relevant governance functions;
- approved by an authorized decision-maker;
- implemented according to defined conditions;
- supported by rollback or contingency arrangements;
- verified against approved acceptance criteria;
- reviewed for unintended consequences;
- reflected in authoritative governance records; and
- formally closed.

---

## Change Management Principles

Megastar Mortgage governs AI changes according to the following principles:

- Material AI changes shall be assessed before implementation.
- Change materiality shall consider governance impact, not only technical complexity.
- Every governed change shall have one accountable Change Owner.
- Provider-initiated changes remain subject to organizational review.
- Approval authority shall be proportionate to impact and risk.
- Implementation shall remain within the approved scope and conditions.
- Unapproved material deviations shall be escalated.
- Deployment completion shall not be treated as successful validation.
- Verification shall confirm correct implementation.
- Validation shall confirm that intended outcomes were achieved without unacceptable unintended effects.
- Emergency status shall not be used to avoid normal governance for convenience.
- Rollback or contingency arrangements shall be defined where practicable.
- Material changes shall trigger reassessment where existing governance conclusions may no longer remain valid.
- Change history, decisions, evidence, and approvals shall remain traceable.
- Closure shall require required verification and governance-record updates.

---

## Change Management Lifecycle

```mermaid
flowchart LR

A[Change Need Identified]
--> B[Change Registered]
--> C[Materiality and Impact Assessed]
--> D[Governance Consultation]
--> E[Approval Decision]
--> F[Implementation Planning]
--> G[Controlled Implementation]
--> H[Verification and Validation]
--> I[Post-Implementation Review]
--> J[Closure and Record Updates]
```

Emergency changes follow an accelerated path but remain subject to authorization, evidence, retrospective assessment, verification, and review.

---

## Lifecycle Stages

### 1. Change Identification

A business, technical, provider, incident, risk, control, assurance, monitoring, legal, privacy, security, or regulatory need creates a proposed change.

### 2. Change Registration

The proposed change receives a unique Change ID and is entered into the Enterprise AI Change Register.

### 3. Materiality and Impact Assessment

The organization evaluates the potential effect on approved use, risk, controls, stakeholders, data, providers, human oversight, obligations, monitoring, and lifecycle status.

### 4. Governance Consultation

Relevant capabilities and specialist functions review the proposed change.

### 5. Approval Decision

An authorized decision-maker approves, conditionally approves, defers, rejects, or withdraws the change.

### 6. Implementation Planning

The implementation plan establishes scope, sequencing, evidence, testing, responsibilities, dependencies, rollback, and communication requirements.

### 7. Controlled Implementation

The change is implemented within the approved scope and conditions.

### 8. Verification and Validation

The organization confirms that the change was implemented correctly and achieved its intended outcome.

### 9. Post-Implementation Review

The organization evaluates sustained performance, unintended consequences, incidents, control operation, and further action.

### 10. Closure

The change is closed after required evidence, verification, review, and governance-record updates are complete.

---

## Change Categories

| Category | Typical Examples |
|---|---|
| Model | New model, retraining, fine-tuning, calibration, version upgrade |
| Prompt or Rule | System prompt, business rule, routing logic, confidence threshold |
| Data | New data source, schema, document type, transformation, retention rule |
| Human Oversight | Review requirement, override authority, escalation path, staffing model |
| Control | New, changed, automated, retired, or frequency-adjusted control |
| Provider | Provider release, migration, subprocessor change, replacement |
| Integration or Infrastructure | API, platform, architecture, deployment environment, dependency |
| Business Process | Workflow, user group, operating procedure, approved-use expansion |
| Monitoring | Metric, KRI, KPI, threshold, source, alert, reporting frequency |
| Policy or Regulatory | Policy, legal requirement, regulatory obligation, contractual condition |
| Remediation | Incident, assurance, risk, control, privacy, security, or provider action |
| Retirement | Suspension, decommissioning, archival, replacement, provider exit |

Each governed change shall have one primary category.

---

## Change Classifications

| Classification | Meaning |
|---|---|
| Standard | Repeatable, low-impact change meeting approved pre-authorization criteria. |
| Normal | Change requiring documented assessment and approval before implementation. |
| Major | Material or high-impact change requiring expanded assessment, testing, assurance, or committee approval. |
| Emergency | Urgent change required to contain harm, restore service, address critical exposure, or meet an immediate obligation. |
| Provider-Initiated | Change initiated externally and requiring organizational impact review. |
| Retirement | Controlled suspension, replacement, decommissioning, or termination. |

Classification determines the depth of assessment, approval, evidence, testing, and review.

---

## Materiality

A change is material where it may affect one or more of the following:

- approved purpose or use;
- affected stakeholders;
- impact classification;
- risk exposure;
- residual risk;
- control design or operation;
- model behaviour;
- data use or data quality;
- privacy or security;
- human oversight;
- transparency or explainability;
- provider dependency;
- legal, regulatory, or contractual obligations;
- reliability or resilience;
- monitoring requirements;
- incident likelihood;
- business continuity; or
- lifecycle status.

Detailed materiality criteria belong to the AI Change Request & Impact Assessment artifact.

---

## Governance Roles

| Role | Primary Responsibility |
|---|---|
| Change Owner | Owns the change from registration through closure. |
| AI System Owner | Provides business accountability for the affected AI system. |
| Technical Owner | Owns technical planning and implementation. |
| Business Process Owner | Owns operational readiness and business impact. |
| AI Governance Lead | Coordinates governance review and maintains framework consistency. |
| Risk Owner | Reviews risk implications. |
| Control Owner | Reviews control impact. |
| Third-Party Relationship Owner | Coordinates provider-related change review. |
| Privacy | Reviews privacy implications. |
| Security | Reviews security implications. |
| Legal & Compliance | Reviews legal, regulatory, policy, and contractual implications. |
| Assurance Function | Provides independent validation where required. |
| Approval Authority | Approves, rejects, defers, or conditions the change. |
| Verification Owner | Confirms implementation and validation results. |

One person may perform multiple roles where appropriate, but accountability and segregation-of-duties expectations shall remain clear.

---

## Accountability Model

Every governed change shall have:

- one Change Owner;
- one affected AI System Owner;
- one current Change ID;
- a defined approval authority;
- a defined implementation owner;
- a defined verification owner;
- documented acceptance criteria;
- a current register status; and
- a closure authority.

A material change shall not proceed without accountable ownership.

---

## Decision Rights

The framework governs decisions including:

- whether the change requires formal AI governance;
- how the change is classified;
- whether the change is material;
- which governance functions must review it;
- whether the change may proceed;
- which conditions must be satisfied before implementation;
- whether implementation should stop or roll back;
- whether restricted operation is appropriate;
- whether independent validation is required;
- whether the change is ready for closure.

It does not determine:

- final residual-risk acceptance;
- provider continuation or exit;
- formal control-effectiveness conclusions;
- enterprise risk reprioritization; or
- management-review outcomes.

---

## Approval Levels

| Approval Level | Typical Use |
|---|---|
| Operational | Standard and low-impact Normal changes within delegated authority |
| Functional Governance | Material changes requiring specialist review |
| Governance Committee | Major changes, cross-functional impact, restrictions, or unresolved conditions |
| Executive | Critical, strategic, potentially unacceptable, or enterprise-wide changes |

The detailed approval matrix belongs to the AI Change Approval & Implementation artifact.

---

## Emergency-Change Boundary

Emergency changes may use an accelerated route where delay would materially increase harm, disruption, security exposure, regulatory exposure, or service loss.

Emergency changes shall still require:

- an accountable owner;
- documented emergency justification;
- minimum impact review;
- authorized approval;
- implementation evidence;
- rollback or contingency arrangements where practicable;
- retrospective assessment;
- verification;
- post-implementation review; and
- register updates.

Emergency governance is defined in Artifact 06.

---

## Verification and Validation Boundary

Verification determines whether the approved change was implemented correctly.

Validation determines whether the change achieved its intended outcome without introducing unacceptable consequences.

Independent assurance may be required where:

- the change affects a key control;
- the change affects a High or Critical risk;
- the change materially alters approved use;
- the change follows a significant incident;
- the change affects a critical provider;
- regulatory or contractual obligations require independence; or
- the approval authority requires objective confidence.

Detailed methods belong to Artifact 05.

---

## Enterprise AI Change Register

The Enterprise AI Change Register is the authoritative living record for governed AI changes.

It maintains current information concerning:

- change identity;
- affected AI system;
- classification;
- ownership;
- materiality;
- impact assessment;
- approval;
- implementation;
- verification;
- emergency status;
- post-implementation review;
- cross-capability handoffs; and
- closure.

The detailed register structure is defined in Artifact 02.

---

## Cross-Capability Coordination

| Change Condition | Receiving Capability |
|---|---|
| New AI use, expanded scope, or changed classification | AI Inventory & Assessment |
| New or materially changed risk | AI Risk Management |
| New, changed, failed, or retired control | AI Controls |
| Independent testing or validation | AI Assurance |
| Provider release, migration, or dependency change | Third-Party AI Governance |
| New or changed monitoring requirement | Continuous Monitoring |
| Failed change or incident condition | AI Incident Management |
| Executive, exception, policy, or residual-risk decision | Governance Oversight & Continual Improvement |
| Regulatory or framework-mapping impact | Framework Alignment |

Each handoff shall be linked through authoritative record identifiers.

---

## Relationship to Enterprise Change Processes

AI Change Management complements, but does not replace:

- software-development lifecycle controls;
- IT service-management change control;
- cybersecurity change management;
- privacy assessment;
- release management;
- configuration management;
- business-process change management; or
- provider change processes.

The applicable enterprise process remains authoritative for its specialist activity. AI Change Management governs the AI-specific impact, consultation, approval, evidence, and record updates.

---

## Framework Outputs

The framework produces:

- a governed AI change lifecycle;
- accountable ownership;
- an authoritative change record;
- materiality and impact review;
- proportionate approval;
- controlled implementation;
- verification and validation;
- emergency-change accountability;
- post-implementation review;
- cross-capability handoffs;
- current governance records; and
- formal change closure.

---

## Framework Effectiveness Measures

The framework may be evaluated through measures such as:

- governed changes with assigned owners;
- changes assessed before implementation;
- changes approved before implementation;
- emergency changes retrospectively reviewed;
- implementations completed within approved scope;
- changes successfully verified;
- failed or rolled-back changes;
- changes linked to incidents;
- overdue post-implementation reviews; and
- governance-record updates completed.

Definitions, targets, and thresholds remain within Continuous Monitoring.

---

## Framework Review

The framework shall be reviewed when:

- a Major or failed change occurs;
- an emergency change reveals governance weakness;
- repeated changes cause incidents;
- provider changes bypass expected notification;
- approval authority is unclear;
- verification proves insufficient;
- regulatory obligations change;
- enterprise change processes change;
- governance records become inconsistent; or
- the framework no longer supports effective change governance.

---

## Framework Approval

Before approval, Megastar Mortgage confirms that:

- the scope is clear;
- the lifecycle is defined;
- classifications are established;
- materiality principles are defined;
- roles and decision rights are clear;
- approval levels are established;
- the Enterprise AI Change Register is authoritative;
- emergency-change accountability is defined;
- verification and implementation remain distinct;
- enterprise-process boundaries are clear;
- cross-capability handoffs are defined; and
- closure authority is established.

---

## Related Artifacts

- Enterprise AI Change Register
- AI Change Request & Impact Assessment
- AI Change Approval & Implementation
- AI Change Verification & Validation
- AI Emergency Change Management
- AI Post-Implementation Review
- AI Change Management Summary

---

## Document Control

| Field | Value |
|---|---|
| Document | AI Change Management Framework |
| Capability | AI Change Management |
| Capability Number | 10 |
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
| 1.0 | July 2026 | Initial release of the AI Change Management Framework. |