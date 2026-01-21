# Executive Dashboard Narrative
This document describes the **executive view** of the operational dashboard and how it supports fast decisions.

The dashboard is designed for:
- Quick comprehension (seconds, not minutes)
- Clear risk signals
- Actionable escalation cues

---

## Executive Questions This Dashboard Must Answer
1. Are we on track to reach **100% completion** within deadline?
2. Where are the **current risks** (by region/site/category)?
3. What issues require **immediate escalation**?
4. What is the operational team doing to recover (corrective actions)?

---

## Recommended Layout (Top to Bottom)

### 1) Overall Status Banner (Top)
- Operation status: **Green / Yellow / Red**
- Current time stamp (last refresh)
- Completion progress summary

**Interpretation**
- Green: proceed as planned  
- Yellow: monitor closely; interventions active  
- Red: escalation required; deadline risk likely  

---

### 2) Completion & Forecast Panel
- Completion rate (current)
- Trend over last intervals
- Forecast completion time (if applicable)

**Decision Use**
- If forecast crosses the deadline → **immediate escalation**

---

### 3) Risk Hotspots Panel
- Top 5 sites/regions with:
  - lowest completion
  - reporting delays
  - critical incidents

**Decision Use**
- Direct attention and resources to hotspots

---

### 4) Incident Overview Panel
- Active incidents by severity
- SLA breach count
- Critical incident list (short)

**Decision Use**
- Confirm incident load is under control
- Trigger contingency if critical incidents stack

---

### 5) Data Integrity / Reconciliation Panel
- Reconciliation status
- Any mismatches (yes/no)
- Impacted scope summary

**Decision Use**
- If mismatch is material → pause dependent decisions until resolved

---

### 6) Actions & Escalations Log (Bottom)
- “What we changed” (corrective actions)
- “What we need” (decisions requested from leadership)

**Decision Use**
- Avoid repeated discussions; show actions already taken
- Provide clear decision asks

---

## Behavioral Rules (How Execs Should Use It)
- The dashboard is a **decision tool**, not a reporting artifact.
- If **Red** appears in any critical KPI panel:
  - Validate quickly (is it data or reality?)
  - Escalate and act within a defined time window
- If **Yellow** persists beyond two cycles:
  - Treat as Red (risk trending)

---

## KPI Mapping
This dashboard is driven by the KPI → Action Matrix:
- `03_kpis_and_metrics/kpi_action_matrix.md`

---

## Design Notes
- Keep it minimal: avoid charts that require long interpretation.
- Prioritize: completion, forecast, critical incidents, reporting compliance.
- Always show last refresh timestamp to support trust in the data.
