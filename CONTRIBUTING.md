# Contributing to Lantern Protocol

Thank you for your interest in contributing.

Lantern Protocol work often touches trust, provenance, resilience, civic data, emergency-condition data, and adversarial environments. Contributions should therefore be precise, reviewable, and explicit about security and protocol impact.

## Contribution lanes

Use the right lane before opening a pull request:

- **Bug report** — something documented or implemented is not working as intended.
- **Feature request** — a bounded capability request.
- **Protocol proposal** — a change to semantics, trust boundaries, interoperability, schemas, verification, or evidence handling.
- **Security research** — a vulnerability, abuse path, bypass, or harmful failure mode.

## Pull request expectations

Every pull request should describe:

1. What changed.
2. Why it changed.
3. What risk it introduces or reduces.
4. What tests, documentation, or validation were performed.
5. Whether the change affects protocol behavior, security posture, data integrity, or deployment operations.

## Design-first rule

Protocol-impacting changes should start as an issue or proposal before implementation. Avoid landing protocol semantics solely through code.

## Review standard

Maintainers may request changes for unclear threat boundaries, insufficient validation, incomplete documentation, unsafe defaults, or changes that make evidence/provenance behavior harder to audit.