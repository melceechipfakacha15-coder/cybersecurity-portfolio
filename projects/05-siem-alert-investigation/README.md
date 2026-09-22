# SIEM Alert Investigation

**Status:** Planned

## Objective

Triage a simulated SIEM alert, validate it against supporting telemetry, and document a clear escalation or closure decision.

## Skills demonstrated

- SIEM search and filtering
- Alert triage
- Log correlation
- False-positive analysis
- Incident escalation writing

## Planned environment and tools

- Splunk, Microsoft Sentinel, or another authorized lab SIEM
- Sample or self-generated logs
- Query language appropriate to the selected platform
- Incident report template

## Investigation plan

1. Review the alert rule, severity, entities, and triggering evidence.
2. Validate the time range and data sources.
3. Search for related account, host, IP, process, and network activity.
4. Build a timeline and compare behavior with the expected baseline.
5. Classify the alert as true positive, benign positive, false positive, or inconclusive.
6. Document the decision, confidence level, and next actions.

## Evidence to collect

- Sanitized alert screenshot
- Queries used
- Supporting event samples
- Entity and timeline summary
- Classification rationale
- Escalation or tuning recommendations

## Deliverables

- SIEM triage report
- Query reference
- Sanitized evidence images
- Timeline and entity table
- Lessons learned

## Completion checklist

- [ ] Alert context reviewed
- [ ] Queries documented
- [ ] Related telemetry correlated
- [ ] Classification justified
- [ ] Sensitive data removed
- [ ] Report proofread and published

## Safety note

Use only lab, public training, or explicitly authorized data. Never publish customer, tenant, employee, or internal security information.
