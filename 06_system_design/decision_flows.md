# Decision Flows
This document defines **decision-oriented operational flows** used during time-critical execution.  
It focuses on **what triggers action**, **who decides**, and **what happens next**.

> Note: The flows below are generic and fully anonymized. They can be adapted to any large-scale, distributed operation.

---

## Flow A — Progress Deviation (Schedule Risk)
### Trigger
- Progress completion rate drops below the expected curve (leading indicator), or
- Projected completion time exceeds the non-negotiable deadline.

### Decision Owner
- Operations Manager (primary)
- Executive Lead (if escalation threshold is reached)

### Steps
1. **Detect** deviation (dashboard alert or monitoring team flag).
2. **Validate**: confirm it is not a reporting/data issue.
3. **Assess Impact**: identify affected sites and severity level.
4. **Identify Cause** (quick classification):
   - Staffing / capacity
   - Process bottleneck
   - Technology / connectivity
   - External dependency delay
5. **Select Corrective Action**:
   - Reallocate resources
   - Activate backup procedures
   - Increase support coverage
   - Apply fast-track process
6. **Set Checkpoint**:
   - Re-evaluate in 30/60 minutes (time window depends on operation criticality).
7. **Escalate** if deviation persists or worsens.

### Output
- Corrective action plan + new checkpoint time + escalation status

---

## Flow B — Site Not Reporting (Visibility Risk)
### Trigger
- A site has not reported status within the allowed reporting interval.

### Decision Owner
- Monitoring Lead (primary)
- Operations Manager (if unresolved)

### Steps
1. **Detect** missing report.
2. **Attempt Contact** (standard channel).
3. **Confirm Site Status**:
   - Operational but delayed reporting
   - Connectivity issue
   - Local disruption
4. **Apply Response**:
   - Technical support engagement
   - Switch to fallback reporting method
   - Assign backup supervisor contact
5. **Escalate** if:
   - No contact within threshold, or
   - Site status cannot be confirmed.

### Output
- Confirmed status or escalation ticket + fallback method used

---

## Flow C — Incident Management (SLA + Criticality)
### Trigger
- A new incident is logged, or
- Incident exceeds SLA, or
- Incident is high-impact/critical.

### Decision Owner
- Incident Lead / Operations Manager

### Steps
1. **Log Incident** with classification:
   - Category (process / tech / external / people)
   - Severity (Low / Medium / High / Critical)
2. **Assign Owner** and target resolution time.
3. **Mitigate** (temporary workaround) if needed.
4. **Resolve** and record resolution notes.
5. **Verify** resolution effectiveness.
6. **Escalate** immediately if:
   - Critical severity, or
   - SLA breach without workaround.

### Output
- Resolved incident record OR escalation summary and decision request

---

## Flow D — Data Integrity / Reconciliation Alert (Quality Risk)
### Trigger
- Inconsistency between expected totals vs reported totals, or
- Duplicate/missing records detected.

### Decision Owner
- Control & Monitoring Lead
- Operations Manager for corrective actions

### Steps
1. **Detect** reconciliation mismatch.
2. **Validate** data source/version and timestamp.
3. **Isolate** impacted sites/units.
4. **Investigate** root cause (system/reporting/process).
5. **Correct** via:
   - Re-run validation
   - Request re-submission
   - Apply approved correction procedure
6. **Confirm** reconciliation returns to expected state.
7. **Escalate** if mismatch persists or affects deadline/credibility.

### Output
- Reconciled status + corrective actions log

---

## Escalation Rules (Generic)
Escalate to the next level when any of the following occurs:
- **Deadline risk**: forecast indicates the deadline may be missed
- **Loss of visibility**: multiple sites not reporting
- **Critical incident**: high impact, wide scope, or safety/compliance risk
- **Repeated deviations**: same site/issue repeats within a short time window
