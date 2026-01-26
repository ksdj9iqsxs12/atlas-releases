# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 2.0.x   | :white_check_mark: |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to: security@overlaytrading.com

You should receive a response within 48 hours. If for some reason you do not, please follow up via email to ensure we received your original message.

Please include the following information in your report:

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the issue (if known)
- The location of the affected source code (if known)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

## What We Consider Security Issues

- Remote code execution
- SQL injection or other injection attacks
- Authentication/authorization bypasses
- Sensitive data exposure (API keys, credentials)
- Cross-site scripting (XSS)
- Denial of service vulnerabilities
- Trading execution bugs that could cause financial loss

## What We Don't Consider Security Issues

- Missing security headers on landing pages
- Issues requiring physical access to the device
- Social engineering attacks
- Attacks requiring the user to install malware

## Acknowledgements

We appreciate the security research community's efforts in helping keep Overlay and its users safe. Responsible disclosure of vulnerabilities helps us ensure the security and privacy of our users.

Researchers who report valid security issues will be acknowledged in our security hall of fame (with permission).
