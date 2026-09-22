# Suspicious Network Traffic Analysis

**Status:** Planned

## Objective

Analyze a controlled packet capture, identify unusual communication patterns, and explain what the available network evidence does and does not prove.

## Skills demonstrated

- Wireshark filtering and packet inspection
- TCP/IP, DNS, and protocol analysis
- Indicator extraction
- Traffic timeline development
- Evidence-based reporting

## Planned environment and tools

- Isolated virtual lab
- Wireshark
- A sanitized or intentionally generated packet capture
- Optional command-line packet analysis tools

## Investigation plan

1. Capture or obtain authorized, non-sensitive lab traffic.
2. Establish the normal traffic context.
3. Filter by hosts, ports, protocols, DNS queries, and connection patterns.
4. Identify notable or anomalous communications.
5. Record relevant indicators and build a timeline.
6. Assess severity while stating uncertainty and alternative explanations.

## Evidence to collect

- Sanitized packet screenshots
- Display filters used
- Source and destination summary
- Protocol and port observations
- Extracted indicators with context
- Findings, limitations, and recommendations

## Deliverables

- Network investigation report
- Filter reference
- Sanitized evidence images
- Indicator table
- Lessons learned

## Completion checklist

- [ ] Authorized capture selected
- [ ] Baseline described
- [ ] Filters documented
- [ ] Suspicious patterns evaluated
- [ ] Evidence sanitized
- [ ] Report proofread and published

## Safety note

Do not capture traffic from networks or devices without authorization. Do not commit raw captures containing credentials, tokens, personal data, or private communications.
