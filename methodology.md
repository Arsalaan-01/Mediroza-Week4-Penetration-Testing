# Methodology

This page is a reporting framework, not a record of completed testing.

## 1. Preparation
- Confirm current written authorisation and exact in-scope hostnames.
- Record the assessment window and restrictions.
- Use a dedicated lab environment and keep an activity log.

## 2. Reconnaissance and attack-surface review
- Record only in-scope, publicly exposed information.
- Identify relevant application entry points.
- Note the tool, time, request/response context, and observation.
- Avoid disruptive scans or high-volume requests.

## 3. Authentication and input-handling review
- Test only approved workflows and test accounts.
- Record expected versus observed behaviour.
- Avoid accessing, copying, or retaining real patient information.

## 4. Designated document review
- Work only with files explicitly supplied or made available for this exercise.
- Record file properties and protection characteristics.
- Do not upload protected files or recovered contents to a public repository.

## 5. Exposure analysis
- Verify each suspected exposure with the minimum necessary proof.
- Redact personal, medical, salary, shareholder, credential, and session data.
- Do not publish raw datasets.

## 6. Reporting and validation
- Give each finding a unique ID.
- State the evidence, impact, likelihood, severity rationale, and remediation.
- Distinguish confirmed findings from observations and unverified leads.
- Where possible, retest after remediation and record the result.
