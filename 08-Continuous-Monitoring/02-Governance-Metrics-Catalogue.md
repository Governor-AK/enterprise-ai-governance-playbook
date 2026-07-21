# Governance Metrics Catalogue

## Executive Summary

The Continuous Monitoring Strategy establishes how Megastar Mortgage maintains ongoing visibility into the Megastar Intelligent Processor (MIP), its risks, controls, third-party dependencies, corrective actions, and governance obligations.

The Governance Metrics Catalogue converts that strategy into a standardized set of measurable governance information.

The catalogue defines each governance metric’s purpose, calculation, source, owner, frequency, quality requirements, reporting audience, interpretation, and relationship to applicable risks, controls, providers, obligations, and living governance records.

The catalogue is the authoritative reference for approved governance measures used across Continuous Monitoring. It prevents inconsistent definitions, duplicate reporting, unsupported calculations, and disconnected dashboard measures.

This artifact defines governance metrics. It does not determine KPI targets, KRI thresholds, dashboard layouts, monitoring findings, escalation decisions, risk ratings, control effectiveness, or management conclusions. Those are established through later artifacts and their owning governance capabilities.

---

## Purpose

The purpose of this document is to establish a standardized approach for defining, approving, maintaining, and using AI governance metrics.

The Governance Metrics Catalogue enables Megastar Mortgage to:

- establish a consistent inventory of approved governance measures;
- define the governance purpose of each metric;
- distinguish base measures from KPIs and KRIs;
- document metric formulas and calculation rules;
- identify authoritative data sources;
- assign metric, data, and reporting ownership;
- establish reporting frequency and review cadence;
- define data-quality and validation requirements;
- preserve traceability to governed AI systems, risks, controls, providers, obligations, findings, and corrective actions;
- prevent duplicate or conflicting measures;
- support later target, tolerance, and threshold design;
- provide standardized inputs to Continuous Control Monitoring and the Governance Dashboard; and
- maintain metric definitions as governance needs and operating conditions change.

Completion of this artifact creates the controlled measurement foundation for the Continuous Monitoring capability.

---

## Metrics Catalogue Process

Every governance metric follows a consistent lifecycle.

```mermaid
flowchart LR

A[Continuous Monitoring Strategy]
--> B[Monitoring Need Identified]
--> C[Metric Defined]
--> D[Source and Formula Validated]
--> E[Ownership Assigned]
--> F[Metric Approved]
--> G[Metric Reported]
--> H[Metric Reviewed]
--> I[Metric Updated or Retired]
```

Approved metrics enter the Governance Metrics Catalogue before they are used in formal monitoring, dashboard reporting, KPI or KRI analysis, or governance decisions.

---

## Metrics Principles

Megastar Mortgage manages governance metrics according to the following principles:

- Every metric shall support a defined governance objective, decision, risk, control, obligation, or monitoring requirement.
- Metrics shall be created only where the resulting information is decision-useful.
- Every metric shall have a standardized definition and calculation methodology.
- Every metric shall identify an authoritative source or documented source hierarchy.
- Every metric shall have a Metric Owner and a Data Owner.
- Metric calculations shall be reproducible.
- Metric lineage shall be traceable from reported result to source information.
- Metrics shall distinguish facts from interpretation.
- Metric definitions shall remain consistent across reporting periods unless a controlled change is approved.
- Metrics shall not be represented as KPIs or KRIs unless formally designated through the KPI & KRI Framework.
- Counts, percentages, rates, ratios, durations, statuses, and trends shall be defined explicitly.
- Manual metrics shall identify the responsible preparer and validation approach.
- Estimated or incomplete values shall be labelled clearly.
- Metric limitations shall be documented.
- Metric quality shall be reviewed before the measure supports material governance decisions.
- Duplicate metrics shall be consolidated wherever possible.
- Retired metrics shall remain historically traceable.
- The catalogue shall not become a substitute for the authoritative records from which measures are derived.

---

## Metric Types

The catalogue may contain several types of governance measures.

| Metric Type | Purpose |
|---|---|
| Count | Measures the number of governed objects, events, issues, or obligations. |
| Percentage | Measures the proportion of a defined population meeting a condition. |
| Rate | Measures the frequency of an event relative to a defined exposure or period. |
| Ratio | Compares two related values. |
| Duration | Measures elapsed time, aging, response time, resolution time, or cycle time. |
| Status | Communicates the current state of a governed object or requirement. |
| Coverage Measure | Measures the extent to which a required population is governed, controlled, assured, or monitored. |
| Quality Measure | Measures completeness, accuracy, reliability, or conformance. |
| Trend Measure | Shows direction or change over time. |
| Concentration Measure | Shows dependency or exposure concentrated in a provider, model, platform, domain, or business process. |
| Maturity Measure | Shows progress against a defined capability or operating-state expectation. |
| Composite Measure | Combines multiple approved measures using a documented calculation and governance rationale. |

Composite measures shall be used cautiously because aggregation can hide material underlying conditions.

---

## Base Metrics, KPIs, and KRIs

The Governance Metrics Catalogue records standardized measures.

The KPI & KRI Framework later determines which approved metrics operate as performance or risk indicators.

| Measure Classification | Meaning |
|---|---|
| Base Governance Metric | Provides descriptive or operational governance information. |
| KPI Candidate | May measure progress against an approved governance objective. |
| KRI Candidate | May provide early warning of increasing risk exposure. |
| Confirmed KPI | Formally approved as a Key Performance Indicator through the KPI & KRI Framework. |
| Confirmed KRI | Formally approved as a Key Risk Indicator through the KPI & KRI Framework. |
| Context Metric | Provides supporting information required to interpret another metric or indicator. |

A single metric may support multiple decisions, but its primary governance purpose shall be clear.

---

## Governance Metric Domains

Metrics may be organized across the following governance domains.

### AI System Governance

Examples include:

- total governed AI systems;
- AI systems by lifecycle status;
- systems operating without current assessment;
- systems awaiting reassessment;
- systems with overdue inventory review;
- systems operating outside approved use;
- systems with unresolved ownership;
- systems with third-party dependencies;
- systems in restricted or suspended status;
- systems entering retirement.

### AI Assessment

Examples include:

- impact assessments completed;
- overdue assessments;
- assessment cycle time;
- high-impact systems;
- systems with incomplete classification;
- assessments requiring escalation;
- reassessments triggered by material change.

### AI Risk Management

Examples include:

- open AI risks;
- High and Critical risks;
- risks without completed analysis;
- risks awaiting prioritization;
- risks without approved response strategy;
- overdue risk actions;
- risks without linked controls;
- risks with worsening trend;
- risks requiring escalation;
- risks awaiting residual-risk decision.

### AI Controls

Examples include:

- approved controls;
- implemented controls;
- controls pending implementation;
- controls without assigned owner;
- controls without monitoring;
- overdue control reviews;
- controls with open exceptions;
- controls requiring redesign;
- key controls by control domain;
- control-implementation cycle time.

### AI Assurance

Examples include:

- controls scheduled for testing;
- controls tested;
- controls not tested;
- effective controls;
- partially effective controls;
- ineffective controls;
- assurance findings by classification;
- overdue assurance actions;
- assurance evidence gaps;
- controls requiring retesting;
- assurance coverage.

### Third-Party AI Governance

Examples include:

- active third-party AI relationships;
- providers under due diligence;
- Conditionally Suitable providers;
- providers with expired due diligence;
- providers with expired assurance reports;
- providers with open contractual gaps;
- providers with overdue corrective actions;
- critical provider dependencies;
- provider concentration;
- provider incidents;
- provider changes;
- relationships approaching renewal;
- relationships with inadequate exit readiness.

### Model and Service Performance

Examples include:

- model accuracy;
- extraction accuracy;
- false-positive rate;
- false-negative rate;
- exception rate;
- model drift indicator;
- service availability;
- latency;
- processing failure rate;
- fallback usage;
- performance degradation;
- output rejection rate.

### Data Quality and Data Governance

Examples include:

- incomplete-data rate;
- invalid-data rate;
- missing-field rate;
- duplicate-record rate;
- data-lineage coverage;
- unresolved data-quality issues;
- data-retention exceptions;
- deletion completion;
- unauthorized-data-use events;
- data-drift observations.

### Privacy

Examples include:

- AI systems processing personal information;
- privacy reviews overdue;
- unresolved privacy conditions;
- data-subject request response time;
- privacy-related incidents;
- cross-border processing exceptions;
- retention breaches;
- deletion failures;
- unauthorized secondary-use concerns.

### Security and Access Control

Examples include:

- privileged AI accounts;
- overdue access reviews;
- inactive accounts;
- unauthorized-access attempts;
- access-control exceptions;
- segregation-of-duties conflicts;
- unresolved vulnerabilities;
- unrotated secrets;
- logging coverage;
- security incidents affecting AI systems.

### Human Oversight

Examples include:

- required human reviews completed;
- human-review coverage;
- override rate;
- correct override rate;
- unreviewed outputs;
- reviewer error rate;
- escalation rate;
- reviewer backlog;
- training currency;
- workload capacity.

### Corrective Actions

Examples include:

- open corrective actions;
- overdue corrective actions;
- actions completed on time;
- actions reported complete pending verification;
- blocked actions;
- action aging;
- verification backlog;
- repeated findings;
- closure cycle time.

### Incident Signals

Examples include:

- potential incident signals;
- confirmed incidents;
- incident recurrence;
- incident response time;
- unresolved incidents;
- provider incidents;
- incidents linked to control failure;
- incidents linked to unapproved change.

### Change Signals

Examples include:

- material changes identified;
- changes awaiting assessment;
- unapproved changes;
- emergency changes;
- changes implemented without verification;
- provider changes;
- model-version changes;
- data-source changes;
- control changes.

### Governance Operations

Examples include:

- overdue governance decisions;
- policy exceptions;
- expired waivers;
- committee actions overdue;
- unresolved escalations;
- review completion rates;
- governance-reporting timeliness;
- monitoring coverage;
- metric data-quality failures.

---

## Required Metric Definition

Every catalogue entry shall contain the following information.

| Metric Component | Purpose |
|---|---|
| Metric ID | Provides a unique identifier. |
| Metric Name | Provides the standardized measure name. |
| Metric Description | Explains what the metric measures. |
| Governance Purpose | Explains why the metric is needed and what decision it supports. |
| Monitoring Domain | Identifies the primary governance domain. |
| Metric Type | Defines whether the measure is a count, percentage, rate, duration, status, trend, or another approved type. |
| Classification | Identifies whether the metric is a base metric, KPI candidate, KRI candidate, confirmed KPI, confirmed KRI, or context metric. |
| Governed Object | Identifies the system, risk, control, provider, action, obligation, incident, change, or portfolio being measured. |
| Population | Defines the complete population included in the calculation. |
| Numerator | Defines the numerator where applicable. |
| Denominator | Defines the denominator where applicable. |
| Formula | Defines the calculation method. |
| Unit of Measure | Defines the output format. |
| Reporting Period | Defines the time period represented. |
| Data Source | Identifies the authoritative source. |
| Data Owner | Owns source-data quality and availability. |
| Metric Owner | Owns definition, interpretation, and maintenance. |
| Calculation Owner | Produces or validates the result. |
| Reporting Frequency | Defines how often the metric is calculated or reported. |
| Review Frequency | Defines how often the metric definition remains subject to review. |
| Data-Quality Requirements | Defines minimum conditions for using the result. |
| Segmentation | Defines required breakdowns by system, function, provider, risk, control domain, or other category. |
| Interpretation Guidance | Explains how the result should be understood. |
| Limitation | Identifies known constraints or blind spots. |
| Related KPI or KRI | Links the measure to later indicator governance where applicable. |
| Related Living Record | Identifies the authoritative governance record receiving or supporting the measure. |
| Approval Status | Records the metric’s governance status. |
| Effective Date | Records when the definition became active. |
| Retirement Date | Records when use ended, where applicable. |

---

## Metric Naming Standard

Metric names shall be concise, consistent, and unambiguous.

Preferred patterns include:

- **Number of [governed object]**
- **Percentage of [population] with [required condition]**
- **Rate of [event] per [exposure]**
- **Average time to [governance activity]**
- **Median age of [open item]**
- **Coverage of [monitoring or control requirement]**
- **Status of [defined obligation]**
- **Trend in [risk, performance, or control condition]**

Avoid names such as:

- Governance Health
- AI Risk Score
- Control Quality
- Vendor Risk Level
- AI Compliance

unless the calculation and interpretation are defined precisely.

---

## Metric Calculation Standards

Metric calculations shall be documented sufficiently for independent reproduction.

### Counts

Counts shall define:

- the population;
- inclusion criteria;
- exclusion criteria;
- duplicate-handling rules;
- status date;
- reporting period; and
- treatment of incomplete records.

### Percentages

Percentages shall define:

- numerator;
- denominator;
- population date;
- treatment of not-applicable items;
- treatment of missing data;
- rounding rule; and
- minimum population size where relevant.

### Rates

Rates shall define:

- event;
- exposure unit;
- reporting period;
- normalization method;
- repeated-event treatment; and
- whether the rate is cumulative or period-specific.

### Durations

Duration metrics shall define:

- start event;
- end event;
- calendar-day or business-day treatment;
- pause conditions;
- reopen treatment;
- incomplete-item treatment; and
- aggregation method.

### Trends

Trend metrics shall define:

- comparison period;
- baseline;
- direction;
- minimum number of periods;
- adjustment for seasonality where relevant;
- data-definition consistency; and
- treatment of methodology changes.

### Composite Measures

Composite metrics shall define:

- component measures;
- weights;
- scoring logic;
- aggregation method;
- missing-data treatment;
- limitations;
- validation approach; and
- rationale for combining the measures.

---

## Metric Granularity and Segmentation

A metric may require segmentation to remain decision-useful.

Possible dimensions include:

- AI system;
- business unit;
- business process;
- lifecycle stage;
- impact classification;
- risk category;
- risk priority;
- control domain;
- control owner;
- control effectiveness;
- provider;
- provider criticality;
- region or jurisdiction;
- data category;
- incident severity;
- change type;
- corrective-action priority;
- reporting period; and
- governance status.

Segmentation shall be used where aggregation could hide material concentration, deterioration, or inequality.

Small populations shall be handled carefully to avoid misleading interpretation or inappropriate disclosure.

---

## Metric Sources and Lineage

Every metric shall identify its authoritative source.

Source hierarchy may include:

1. Living governance record.
2. Approved system of record.
3. Controlled operational report.
4. Approved provider report.
5. Validated analytical output.
6. Documented manual attestation.

Where multiple sources exist, the metric definition shall specify:

- primary source;
- secondary or fallback source;
- reconciliation method;
- source owner;
- extraction method;
- transformation steps;
- calculation logic;
- reporting location; and
- retained evidence.

Metric lineage shall support reconstruction from dashboard result to underlying source data.

---

## Metric Ownership

Every metric shall have clear ownership.

| Role | Responsibility |
|---|---|
| Metric Owner | Defines the metric, confirms governance relevance, interprets results, and approves changes. |
| Data Owner | Ensures the source data is governed, available, and fit for purpose. |
| Calculation Owner | Produces or validates the calculated result. |
| Reporting Owner | Publishes the approved result to the intended audience. |
| Governance Reviewer | Reviews material trends, limitations, and potential actions. |
| System Owner | Supports system-specific interpretation where applicable. |
| Risk Owner | Reviews risk-related metric implications. |
| Control Owner | Reviews control-related metric implications. |
| Third-Party Relationship Owner | Reviews provider-related metric implications. |

Metric ownership does not replace ownership of the underlying governed object.

---

## Metric Frequency

The catalogue records both calculation frequency and review frequency.

### Calculation or Reporting Frequency

Possible values include:

- Real Time
- Near Real Time
- Daily
- Weekly
- Monthly
- Quarterly
- Semi-Annual
- Annual
- Event-Driven

### Definition Review Frequency

Metric definitions shall be reviewed periodically and when:

- governance objectives change;
- source systems change;
- calculation logic changes;
- a metric becomes misleading;
- data quality deteriorates;
- monitoring findings reveal a gap;
- a KPI or KRI is redesignated;
- a new regulatory obligation applies;
- system or provider scope changes;
- dashboard audiences change; or
- the metric no longer supports a material decision.

---

## Metric Data Quality

Each metric shall have defined quality requirements.

The review may consider:

- source completeness;
- source accuracy;
- timeliness;
- consistent coding;
- duplicate handling;
- population completeness;
- lineage;
- calculation accuracy;
- reconciliation;
- access control;
- retention;
- source changes;
- manual adjustments; and
- known exclusions.

Metric results may be classified as:

| Metric Quality Status | Meaning |
|---|---|
| Reliable | Data and calculation support normal governance use. |
| Reliable with Limitation | Result is usable with a documented limitation. |
| Provisional | Result requires validation before material reliance. |
| Unreliable | Result should not support governance decisions. |
| Unavailable | Required source or calculation is not available. |

A green or satisfactory result shall not be reported where the underlying metric quality is Unreliable or Unavailable.

---

## Metric Interpretation

Every metric shall include interpretation guidance.

Interpretation should explain:

- what an increase means;
- what a decrease means;
- whether higher or lower is desirable;
- which factors may influence the result;
- whether the result requires segmentation;
- what context metrics are needed;
- whether a threshold exists;
- which governance owner should review the result; and
- what the metric does not prove.

For example:

> A high percentage of controls tested on schedule indicates assurance coverage discipline. It does not demonstrate that the controls were effective.

This distinction prevents activity measures from being mistaken for outcome measures.

---

## Metric Validation

Before approval, each metric shall be validated to confirm that:

- the governance purpose is clear;
- the definition is unambiguous;
- the formula is reproducible;
- the source is authoritative or appropriately controlled;
- the population is defined;
- ownership is assigned;
- reporting frequency is proportionate;
- data-quality requirements are achievable;
- interpretation guidance is complete;
- known limitations are documented;
- duplication has been avoided;
- required segmentation is identified; and
- the metric can support the intended governance decision.

Metrics that cannot be validated shall remain Draft, be revised, or be rejected.

---

## Metric Approval Status

Metrics may progress through the following statuses.

| Metric Status | Meaning |
|---|---|
| Draft | Definition is being developed. |
| Under Validation | Source, formula, ownership, and usefulness are being tested. |
| Approved | Metric is authorized for governance monitoring and reporting. |
| Approved with Limitation | Metric may be used subject to documented constraints. |
| Suspended | Metric use is paused because of quality, source, or interpretation concerns. |
| Retired | Metric is no longer used for current monitoring. |
| Replaced | Metric has been superseded by another approved definition. |

Only Approved or Approved with Limitation metrics should appear in formal governance dashboards.

---

## Catalogue Maintenance

The Governance Metrics Catalogue shall be updated when:

- a new monitoring need is approved;
- a new AI system or provider requires measurement;
- a risk or control requires a new measure;
- a metric is designated as a KPI or KRI;
- a source system changes;
- a formula changes;
- ownership changes;
- reporting frequency changes;
- metric quality deteriorates;
- a metric becomes duplicative;
- a measure becomes misleading;
- governance findings identify a gap;
- monitoring requirements change;
- regulatory obligations change; or
- a metric is suspended, retired, or replaced.

All changes shall preserve version history and effective dates.

---

## Relationship to the KPI & KRI Framework

The Governance Metrics Catalogue defines approved measures.

The KPI & KRI Framework later determines:

- which measures are key;
- which measures indicate performance;
- which measures indicate risk;
- the target;
- the tolerance;
- the warning threshold;
- the breach threshold;
- the critical threshold;
- the required action;
- the escalation authority; and
- the interpretation of trends.

A metric may exist without becoming a KPI or KRI.

Not every measurable condition deserves key-indicator status.

---

## Relationship to Continuous Control Monitoring

Continuous Control Monitoring uses approved catalogue metrics to observe:

- control execution;
- control availability;
- overdue reviews;
- exception rates;
- evidence availability;
- configuration deviation;
- control-health trends;
- improvement actions; and
- monitoring coverage.

The catalogue defines the measure.

Continuous Control Monitoring defines how control-related signals are used over time.

---

## Relationship to the Governance Dashboard

The Governance Dashboard may display only approved measures from the Governance Metrics Catalogue.

Dashboard presentation shall preserve:

- Metric ID;
- metric name;
- reporting period;
- value;
- unit;
- quality status;
- target or threshold where applicable;
- trend;
- owner;
- source; and
- required action.

Dashboard design shall not redefine metric formulas or source logic.

---

## Living Governance Record Relationship

Governance metrics may summarize or enrich existing living governance records.

### Enterprise AI System Inventory

Metrics may support:

- system-review status;
- lifecycle status;
- reassessment status;
- ownership completeness;
- provider-dependency visibility;
- monitoring coverage.

### Enterprise AI Risk Register

Metrics may support:

- current risk condition;
- KRI status;
- risk trend;
- threshold breach;
- overdue risk actions;
- monitoring escalation.

### Enterprise AI Control Register

Metrics may support:

- current control status;
- control health;
- monitoring status;
- overdue review;
- exception rate;
- improvement status;
- threshold breach.

### Enterprise Third-Party AI Register

Metrics may support:

- provider-monitoring status;
- provider KPI or KRI status;
- assurance currency;
- contractual compliance;
- service performance;
- corrective-action status;
- material trend;
- threshold breach.

Metrics do not replace the underlying register fields or source records.

---

## Why This Document Matters

Organizations often accumulate metrics faster than they establish measurement discipline.

Different teams may use the same label for different calculations. Dashboards may display values with no agreed source. Percentages may use inconsistent populations. Activity may be presented as effectiveness. Green status may hide missing data. Repeated reporting may continue long after a metric stops supporting a real decision.

The Governance Metrics Catalogue provides Megastar Mortgage with a controlled measurement language for AI governance.

It ensures that monitoring results are standardized, reproducible, traceable, owned, interpretable, and suitable for later use as KPIs, KRIs, control-health measures, dashboard information, and governance evidence.

---

## Related Artifacts

This document supports:

- Governance Metrics Catalogue Template
- Continuous Monitoring Strategy
- KPI & KRI Framework
- Continuous Control Monitoring
- Governance Dashboard
- Monitoring Findings & Escalation
- Continuous Monitoring Summary
- Enterprise AI System Inventory
- Enterprise AI Risk Register
- Enterprise AI Control Register
- Enterprise Third-Party AI Register

---

## Document Control

| Field | Value |
|---|---|
| Document | Governance Metrics Catalogue |
| Capability | Continuous Monitoring |
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
| 1.0 | July 2026 | Initial release of the Governance Metrics Catalogue artifact. |