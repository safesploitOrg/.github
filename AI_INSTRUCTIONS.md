# AI Contribution Instructions

## Purpose

This organisation contains infrastructure, DevSecOps, homelab, automation and security-focused engineering projects.

AI-assisted changes should improve clarity, reproducibility, security and maintainability.

## General Rules

- Use British English.
- Prefer practical examples over abstract explanations.
- Keep documentation concise and operational.
- Do not invent infrastructure details.
- Do not expose private IP addresses, credentials, hostnames, secrets, tokens or internal-only diagrams unless already present in the target repository.
- Treat public repositories as portfolio-safe outputs.
- Keep private operational details out of public documentation.

## Script Style

For Bash and Python scripts:

- Use global variables in uppercase.
- Use modular functions.
- Include a `main` function.
- Avoid repetition (DRY).
- Fail safely.
- Validate input.
- Use clear logging/output.
- Avoid destructive defaults.

## Security Expectations

- Never commit secrets.
- Use placeholders for sensitive values.
- Prefer least privilege.
- Document security assumptions.
- Highlight risks where commands are destructive or privileged.
- Avoid weakening authentication, TLS, firewalling or access control.

## Documentation Style

Use:

- Clear headings
- Concise bullet points
- Tables where useful
- Practical examples
- Security notes where relevant

Avoid:

- Corporate filler
- Overly broad mission statements
- Unsupported claims
- Excessive emoji usage
    - Emoji usage to improve readability, like prefixing headings is acceptable
- Unnecessary complexity

## Repository Awareness

Each repository should remain self-contained.

Do not assume that organisation-level instructions replace repository-specific documentation such as:

- `README.md`
- `ARCHITECTURE.md`
- `SECURITY.md`
- `CONTRIBUTING.md`