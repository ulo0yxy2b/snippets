# Threat Modeling Snippets

Quick references for threat modeling activities.

## STRIDE

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

Use STRIDE per element: external entity, process, data store, data flow.

## Common Questions

- Can an attacker spoof this identity?
- Can data be modified in transit or at rest?
- Can an action be denied after the fact?
- Is sensitive data exposed to unauthorized users?
- Can the service be overwhelmed or crashed?
- Can a low-privilege user gain more access?

## DREAD (risk rating)

- Damage potential
- Reproducibility
- Exploitability
- Affected users
- Discoverability

Score each 1-10 and average for a rough risk rating.
