# Networkwalks — Week 4: Mediroza General Hospital

**Batch:** B083  
**Project type:** Black-box penetration testing and vulnerability assessment  
**Scenario duration:** 5 days  
**Target stated in the training brief:** `https://medirozahospital.com`  
**Prepared by:** Arsalan Yousuf Dar

> **Status:** Portfolio structure and project documentation prepared from the Networkwalks Week 4 brief. Technical testing results have not yet been entered. Do not describe any vulnerability as confirmed until it has been reproduced and documented with evidence.

## Overview

This repository documents the authorised educational penetration-testing exercise described in the Networkwalks Week 4 brief. The exercise is organised around four milestones:

1. **M1 — Initial Access:** reconnaissance, exposed entry points, authentication and input-handling review, and evidence of access to the three designated test PDF reports.
2. **M2 — Data Extraction:** analyse the protection applied to the three designated files and document successful recovery of their contents where authorised.
3. **M3 — Critical Data Exposure:** inspect permitted file properties and server-side exposure indicators; document the assigned salary and shareholder-data exposure without publishing personal or confidential records.
4. **M4 — Penetration Test Report:** prepare an executive summary, scope and methodology, evidence-backed findings, risk ratings, and remediation recommendations.

## Scope and rules

The supplied brief specifies:
- Testing is limited to the named target domain and agreed scope.
- No social engineering.
- No denial-of-service testing.
- No testing outside the agreed scope.
- Written authorisation is stated in the training brief.

Only perform testing while the authorisation remains valid and only against the exact assets and activities approved by the programme. Stop if scope or authorisation is unclear.

## Repository structure

```text
.
├── README.md
├── .gitignore
├── docs/
│   ├── project-scope.md
│   ├── methodology.md
│   ├── findings-register.md
│   └── final-report-template.md
├── evidence/
│   ├── M1-initial-access/
│   ├── M2-data-extraction/
│   ├── M3-data-exposure/
│   └── M4-report/
└── notes/
    └── activity-log.md
```

## Evidence handling

- Add only screenshots and notes that you are permitted to share.
- Redact names, patient identifiers, medical details, credentials, tokens, session cookies, and other sensitive data.
- Do not commit the three patient PDFs, recovered confidential contents, employee salary records, shareholder personal details, password lists, or secrets.
- Keep original sensitive evidence in an approved private location; publish only redacted proof and a high-level summary.
- Record the date, test step, expected result, observed result, and evidence filename for each activity.

## Current completion status

| Milestone | Status |
|---|---|
| M1 — Initial Access | Pending evidence |
| M2 — Data Extraction | Pending evidence |
| M3 — Critical Data Exposure | Pending evidence |
| M4 — Final Report | Template prepared; findings pending |

Update this table only after completing each milestone and retaining verifiable evidence.

## Disclaimer

This repository is an educational portfolio record. It does not provide permission to test any system. Never apply these techniques to systems without explicit written authorisation from the owner.
