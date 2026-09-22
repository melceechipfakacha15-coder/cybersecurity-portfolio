# Failed Login Investigation

**Status:** Planned

## Objective

Investigate repeated failed Windows sign-in attempts in an authorized lab, distinguish likely user error from suspicious activity, and document an evidence-based response.

## Skills demonstrated

- Windows Security log analysis
- Event correlation and timeline building
- Basic PowerShell investigation
- Incident severity assessment
- Clear technical reporting

## Planned environment and tools

- Windows 10 or 11 virtual machine
- Windows Event Viewer
- PowerShell
- Optional SIEM for log ingestion

## Investigation plan

1. Generate controlled successful and failed sign-ins in the lab.
2. Review relevant Security log events, including expected sign-in success and failure event IDs.
3. Compare timestamps, account names, logon types, source addresses, and failure reasons.
4. Build a concise activity timeline.
5. Decide whether the pattern is benign, suspicious, or inconclusive.
6. Recommend proportionate containment and prevention steps.

## Evidence to collect

- Sanitized screenshots of relevant events
- Exported event details with identifiers removed
- Commands or queries used
- Timeline of observed activity
- Explanation of findings and limitations

## Deliverables

- Completed incident report
- Sanitized evidence images
- Investigation notes and commands
- Short lessons-learned summary

## Completion checklist

- [ ] Lab activity generated
- [ ] Evidence collected and sanitized
- [ ] Events correlated
- [ ] Findings supported by evidence
- [ ] Response recommendations documented
- [ ] Report proofread and published

## Safety note

Use only accounts and systems you own or are authorized to test. Never publish real usernames, IP addresses, hostnames, or employer data.
