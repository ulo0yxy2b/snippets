# Threat Modeling Checklist

Quick reference for threat modeling sessions.

## Identify Assets
- Data stores, processes, external entities, trust boundaries
- Data flows and entry points
- Authentication/authorization mechanisms

## Enumerate Threats (STRIDE)
- Spoofing, Tampering, Repudiation, Info Disclosure, DoS, Elevation

## Assess Risk
- Likelihood and impact (High/Med/Low)
- Existing controls and mitigations

## Mitigations
- Validate inputs, encrypt in transit/at rest
- Least privilege, audit logging
- Rate limiting and redundancy

## Follow-up
- Document decisions in ADRs
- Revisit after architecture changes
