# CYRA — complaints.md

## Complaint Taxonomy

Contains:
- Complaint IDs
- Symptoms
- Severity
- Related modules
- Escalation conditions
- Confidence levels
- Source references

### Included Sections
- PWR-001 to PWR-008
- BAT-001 to BAT-003
- TMP-001 to TMP-006
- FAN-001 to FAN-003
- PHV-001 to PHV-007
- IMG-001 to IMG-003
- PRB-001 to PRB-003
- STR-001 to STR-005
- IO-001 to IO-006
- CP-001 to CP-007
- DSP-001 to DSP-004
- ECG-001 to ECG-002
- GEL-001 to GEL-004
- SW-001 to SW-002

## Example Structure

```md
# IMG-001 — No Echo in Ultrasound Image

## Symptom
Probe recognized but no echo return.

## Related Modules
- TR64 Board
- PHV Board
- Probe Board

## Severity
High

## Escalation
Escalate if unresolved after board replacement.
```
