# Data Handling SOP (v1.1)

**Owner:** <Chang Liu>  | **Date:** <2025-11-02>  | **Repo:** <repo [URL](https://github.com/ChangLiu-66/Assessment-Task3/new/main)>

## 1. Purpose & Scope
This SOP governs handling of de-identified/synthetic analytics data used for patient-flow style metrics in educational contexts.

## 2. Roles & Responsibilities
- Data Owner: <Chang Liu> – approves access, retention, disposal.
- Contributor(s): <Names, if any> – follow this SOP and PR review rules.

## 3. Collection & De-identification
- Data origin: synthetic or public sample. No direct identifiers.
- Minimisation: only fields needed for KPIs are retained: `<list fields>`.
- De-identification: removed `<direct IDs>`, aggregated time to `<day/week>`.

## 4. Storage & Access Control
- Local storage encrypted disk / cloud private bucket.
- GitHub: public code, **no raw sensitive data** in repo.
- Secrets: never commit; rotate if exposed.

## 5. Sharing & Third Parties
- Only share derived charts/metrics; not raw sensitive data.
- External sharing requires owner approval and README disclosure.

## 6. Logging & Audit
- PR reviews required on `main`.
- Actions runs archived in GitHub Actions tab.

## 7. Backup, Retention & Disposal
- Retain derived artefacts (PDFs, charts). Delete raw data monthly.
- Securely delete (shred/empty trash).

## 8. Exceptions & Approvals
- Any exception requires a PR and explicit comment/approval.

## 9. Version Control
- This SOP version: 1.1. Changes tracked via git history.
