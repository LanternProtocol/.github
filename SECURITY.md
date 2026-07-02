# Security Policy

Lantern Protocol treats security, adversarial-resilience, evidence integrity, and provenance failures as core project concerns.

## Reporting a vulnerability

Do not open a public GitHub issue for vulnerabilities or abuse paths.

Use GitHub's private vulnerability reporting or a private maintainer communication channel when available. Include enough detail for maintainers to reproduce and assess the issue safely.

Useful report details include:

- Affected repository, branch, commit, or release.
- Description of the vulnerability or failure mode.
- Preconditions and attacker capabilities.
- Expected impact on confidentiality, integrity, availability, provenance, evidence validity, trust decisions, or emergency-condition behavior.
- Reproduction steps, proof-of-concept, or logs, if safe to share.
- Suggested mitigation, if known.

## Scope

Security reports may include:

- Authentication or authorization failures.
- Secret exposure or unsafe credential handling.
- Supply-chain compromise paths.
- Evidence/provenance forgery or replay.
- Sensor, signal, or metadata spoofing failure modes.
- Unsafe defaults in CI/CD, deployment, or dependency handling.
- Protocol downgrade, ambiguity, or verification bypasses.

## Coordinated disclosure

Maintainers will make a good-faith effort to acknowledge reports, assess severity, coordinate fixes, and publish advisories when appropriate.

## Researcher conduct

Avoid destructive testing, data exfiltration, persistence, lateral movement, denial of service, or testing against systems you do not own or have permission to assess.