# Dashboard Description

## Monitoring Approach
Operational monitoring was not handled through a single dashboard.

Due to the time-bound and phase-based nature of the electoral operation,
different monitoring views were used depending on the operational stage.
Each phase had distinct objectives, risks, and decision needs.

The dashboard described below represents the **Processing Phase**
(Election Day and post-election), where national-level monitoring
focused on ensuring timely and complete processing of electoral records.

---

## Purpose
During the processing phase, the dashboard provides a centralized,
national-level view of operational progress across all Computing Centers (CC),
enabling management to:

- monitor progress toward 100% processing of electoral records and resolutions,
- detect delays or deviations from expected processing timelines,
- identify Computing Centers at risk of missing deadlines,
- track operational incidents requiring escalation,
- and support timely decision-making under strict, non-negotiable deadlines.

---

## Intended Users
- Central Operations Management (national level)
- Central Support and Incident Coordination Teams
- Regional Operational Leads (aggregated or filtered views)

---

## Core Questions the Dashboard Answers
1. Is the operation on track to achieve 100% processing within the established timeline?
2. Which Computing Centers are delayed or at risk of missing processing deadlines?
3. How much time remains to complete processing at a national level?
4. Where are critical operational issues requiring immediate intervention?
5. Which regions or centers require escalation or resource reallocation?

---

## Scope Clarification
This dashboard focuses exclusively on **operational processing control**.

It does **not** include:
- electoral results or vote-count outcomes,
- candidate or party performance,
- software-level metrics of the electoral system,
- individual operator or digitizer performance indicators.

ONPE’s institutional responsibility during this phase is to ensure
that **100% of electoral records and resolutions are processed accurately
and within the established timelines**, regardless of electoral outcomes.

---

## Suggested Layout (Processing Phase Dashboard)

### A) KPI Cards (Top Row)
- National Processing Completion (%)
- Computing Centers at 100% Completion (count)
- Computing Centers At Risk (count)
- Time Remaining to Deadline
- Critical Operational Issues (count)

---

### B) Processing Progress and Risk (Middle Section)
- Table: Computing Centers with Processing Completion %, Status, and Risk Level
- Chart: Processing Completion Trend (Actual vs Expected)
- Chart: Computing Centers by Status (On Track / At Risk / Delayed)

---

### C) Operational Issues and Escalation (Bottom Section)
- Chart: Operational Issues by Region
- Table: Critical Issues (CC, Issue Type, Age, Escalation Status)

---

## Filters
- Region
- Operational Status
- Risk Level
- Computing Center

---

## Data Source
Primary dataset used for illustrative purposes:
`04_data/sample_dataset.xlsx`
