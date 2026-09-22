# Incident Investigation: [Short descriptive title]

**Status:** Draft  
**Date:** YYYY-MM-DD  
**Analyst:** [Name or GitHub handle]  
**Environment:** Authorized lab or simulation  
**Severity:** Informational / Low / Medium / High / Critical

## Executive summary

Explain what happened, the likely impact, and the recommended action in three to five sentences.

## Scenario and objective

- What triggered the investigation?
- What question must the investigation answer?
- What systems and time window are in scope?

## Lab environment

Describe the operating systems, virtual machines, network layout, accounts, and data sources used. Do not publish secrets or identifying information.

## Tools used

- Tool:
- Purpose:

## Evidence reviewed

| Evidence | Source | Relevant time | Why it matters |
|---|---|---|---|
| [Example] | [Log or capture] | [Timestamp] | [Reason] |

## Investigation process

Record the steps taken in order. Include commands and queries that another learner could reproduce safely.

## Findings

State what the evidence supports. Separate confirmed facts from hypotheses.

## Indicators

| Indicator | Type | Context |
|---|---|---|
| [Sanitized value] | IP / domain / hash / account / event ID | [Meaning] |

## Severity and impact

Explain the severity rating, affected assets, potential business impact, and confidence level.

## Response and escalation

- Immediate containment:
- Evidence preservation:
- Escalation decision:
- Stakeholders to notify:
- Recovery steps:

## Recommendations

List prioritized, practical steps that would reduce the likelihood or impact of recurrence.

## Lessons learned

Explain what became clearer, what was difficult, and what you would improve next time.

## Evidence-safety check

- [ ] Lab or simulated data only
- [ ] Credentials and tokens removed
- [ ] Personal and organizational identifiers sanitized
- [ ] Screenshots reviewed and cropped
- [ ] Raw packet captures and logs excluded
