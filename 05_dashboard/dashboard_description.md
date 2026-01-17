# Dashboard Description

## Purpose
The dashboard provides a centralized view of operational status across all sites, enabling management to:
- monitor progress toward 100% processing completion,
- detect delays early,
- track incidents and escalation needs,
- and confirm readiness for critical milestones.

## Intended Users
- Central Operations Management
- Support and Incident Management Teams
- Regional Operational Leads (read-only or filtered view)

## Core Questions the Dashboard Answers
1. Are all sites on track to reach 100% processing completion on time?
2. Which sites are delayed or at risk?
3. How many incidents are open, and how many are critical?
4. Are providers meeting commitments in sites that are at risk?
5. What is the current status by region and by stage?

## Suggested Layout (Single-Page Dashboard)

### A) KPI Cards (Top Row)
- Overall Processing Completion (%)
- Sites at 100% Completion (count and %)
- Sites At Risk (count)
- Open Incidents (count)
- Critical Incidents (count)

### B) Progress and Risk (Middle)
- Table: Sites with Processing Completion %, Open Incidents, Provider Status
- Chart: Processing Completion % by Site (sorted ascending)
- Chart: Sites by Status (On Track / At Risk / Delayed)

### C) Incident View (Bottom)
- Chart: Open Incidents by Region
- Table: Critical Incidents (Site, Type, Age, Escalation Status)

## Filters (Right Panel)
- Region
- Stage
- Provider Status
- Site

## Data Source
Primary dataset: `04_data/sample_dataset.xlsx`

## Notes
This dashboard is intentionally designed for operational decision-making: clarity and actionability are prioritized over visual complexity.
