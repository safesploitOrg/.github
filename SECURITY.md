# Security Policy

## Reporting Security Issues

If you identify a security issue in a public safesploitOrg repository, please do not open a public issue containing exploit details, credentials, private endpoints or sensitive configuration.

Use GitHub private vulnerability reporting where it is available:

1. Open the affected repository on GitHub.
2. Go to **Security**.
3. Select **Report a vulnerability**.
4. Include only the details needed to understand and reproduce the issue.

If private vulnerability reporting is not available for the affected repository, raise a minimal public issue stating that a security concern exists and ask for a preferred private contact route. Do not include exploit details, secrets, private endpoints, hostnames or sensitive configuration in the public issue.

## Scope

This policy applies to public repositories under safesploitOrg.

Private homelab infrastructure, internal hostnames, private IP addressing, firewall rules and secrets are out of scope for public disclosure.

## Secrets

If secrets, tokens, private keys or credentials are accidentally committed, they should be considered compromised and rotated immediately.

Do not attempt to reuse, validate or disclose exposed credentials beyond what is needed to report the issue safely.
