# Windows Security Event Investigation

**Status:** Planned

## Objective

Investigate a controlled Windows security event by correlating host activity, user context, processes, and network evidence into a defensible timeline.

## Skills demonstrated

- Windows event log analysis
- Process and account context review
- Timeline correlation
- Host-based incident triage
- Remediation planning

## Planned environment and tools

- Windows virtual machine
- Windows Event Viewer
- Microsoft Defender logs
- PowerShell
- Optional Sysmon in an isolated lab

## Investigation plan

1. Generate or select an authorized lab event.
2. Identify the initial alert or notable log entry.
3. Correlate nearby authentication, process, service, and network events.
4. Separate observed facts from hypotheses.
5. Determine scope, likely impact, and confidence level.
6. Recommend containment, recovery, and monitoring actions.

## Evidence to collect

- Sanitized event screenshots
- Relevant event fields and timestamps
- PowerShell commands used
- Process and account timeline
- Findings with confidence and limitations
- Response recommendations

## Deliverables

- Host investigation report
- Event timeline
- Sanitized evidence images
- Command reference
- Lessons learned

## Completion checklist

- [ ] Lab event selected
- [ ] Related logs correlated
- [ ] Timeline completed
- [ ] Findings and assumptions separated
- [ ] Evidence sanitized
- [ ] Report proofread and published

## Safety note

Run experiments only in systems you own or are authorized to use. Remove usernames, device names, IP addresses, tenant details, and any sensitive paths before publishing.
