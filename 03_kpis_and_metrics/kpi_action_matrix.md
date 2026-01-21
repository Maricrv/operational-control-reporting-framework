# KPI → Action Matrix
This matrix links **operational KPIs** to **thresholds, statuses, and required actions**.  
It is intentionally concise and decision-driven.

> All thresholds are illustrative. Adjust based on your operation’s context and tolerance for risk.

---

## KPI Status Logic
- **Green**: on track, no action required (monitor)
- **Yellow**: attention required (investigate + minor corrective action)
- **Red**: immediate action required (escalate + corrective action)

---

## KPI → Action Table

| KPI | Definition | Green | Yellow | Red | Primary Owner | Required Action |
|---|---|---:|---:|---:|---|---|
| Completion Rate | % of units completed vs total required | ≥ 99% | 98–98.9% | < 98% | Ops Manager | Yellow: investigate bottlenecks. Red: execute corrective plan + escalate. |
| Schedule Variance | Difference between actual progress vs expected curve | On/above curve | Slightly below curve | Persistently below curve | Monitoring Lead | Yellow: validate reporting + identify impacted sites. Red: corrective plan + escalation. |
| Active Critical Incidents | # of open incidents classified as Critical | 0 | 1 | ≥ 2 | Incident Lead | Yellow: assign priority resources. Red: immediate escalation + contingency. |
| Incident SLA Breach Rate | % incidents exceeding SLA | ≤ 2% | 2–5% | > 5% | Incident Lead | Yellow: rebalance ownership. Red: escalate + root-cause action. |
| Reporting Compliance | % of sites reporting within interval | ≥ 98% | 95–97.9% | < 95% | Monitoring Lead | Yellow: contact + restore reporting. Red: fallback reporting + escalation. |
| Reconciliation Accuracy | % match between expected totals and reported totals | 100% | Minor mismatch | Material mismatch | Control Lead | Yellow: isolate + correct. Red: halt dependent decisions + escalate. |
| Rework / Correction Rate | % items requiring correction after initial processing | ≤ 1% | 1–3% | > 3% | Ops Manager | Yellow: reinforce process guidance. Red: targeted intervention + QA checkpoint. |
| Resource Coverage | % of required coverage filled for critical roles | ≥ 99% | 97–98.9% | < 97% | Ops Manager | Yellow: adjust shifts. Red: mobilize backup resources + escalate. |

---

## Notes
- This matrix supports consistent decision-making and reduces ad-hoc escalations.
- KPIs are designed as a mix of:
  - **Leading indicators** (schedule variance, reporting compliance)
  - **Lagging indicators** (completion rate, SLA breach rate)
- Keep KPIs stable during execution; avoid changing definitions mid-operation.
