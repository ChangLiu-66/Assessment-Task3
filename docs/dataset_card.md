# Dataset Card

**Name:** Synthetic Patient-Flow Sample  
**Owner:** <Chang Liu> | **Date:** <2025-11-02>

## Summary
Synthetic dataset to illustrate patient-flow KPIs (wait time, LOS, 7-day revisit).

## Composition
- Rows: <e.g., 2,500>
- Time range: <2025-11> to <2025-11>
- Fields: `visit_id*`, `arrival_time`, `triage_level`, `wait_minutes`, `los_days`, `revisit_7d` (proxy)
\* `visit_id` is random synthetic ID.

## Collection Process
Generated programmatically / sourced from public samples; no real PHI.

## De-identification
- Removed names, DOB, addresses, MRNs.
- Time rounded to <day>.
- Small-count suppression for n<5 in published charts.

## Recommended Uses
- Educational analytics demos, KPI calculation, basic charts.

## Out-of-Scope Uses
- Clinical decisions, benchmarking real services.

## Ethical Notes
- Risks: re-identification risk is negligible for synthetic data; still avoid joining with external sources.
- See `docs/disclosure_plain_language.md` for stakeholder-friendly description.
