# Phishing Email Investigation

**Status:** Planned

## Objective

Triage a simulated phishing message by examining its headers, sender context, links, attachment metadata, and social-engineering techniques.

## Skills demonstrated

- Email header analysis
- URL and domain assessment
- Phishing indicator identification
- Risk classification
- User-focused remediation guidance

## Planned environment and tools

- Simulated or public training email sample
- Text editor or header analyzer
- Safe reputation sources
- Optional isolated analysis environment

## Investigation plan

1. Preserve the simulated message and document its source.
2. Review sender, reply-to, routing, authentication results, and timestamps.
3. Inspect displayed links and actual destinations without opening unsafe content.
4. Review attachment names and metadata without executing files.
5. Identify urgency, impersonation, credential theft, or payment themes.
6. Assign a severity and recommend response actions.

## Evidence to collect

- Sanitized message screenshot
- Relevant header fields
- URL and domain observations
- Social-engineering indicators
- Severity rationale
- Containment and awareness recommendations

## Deliverables

- Phishing triage report
- Indicator table
- Annotated sanitized screenshots
- User guidance summary
- Lessons learned

## Completion checklist

- [ ] Safe sample selected
- [ ] Headers reviewed
- [ ] Links and attachments assessed safely
- [ ] Indicators documented
- [ ] Severity justified
- [ ] Report proofread and published

## Safety note

Use only simulated or authorized samples. Never open unknown attachments or visit suspicious links on a normal workstation, and never publish victim information or live malicious links.
