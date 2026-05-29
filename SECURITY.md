# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.5.x   | :white_check_mark: |
| 2.0.x beta | :white_check_mark: |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to: security@atlasdesktop.app

You should receive a response within 48 hours. If you do not, please follow up by email to ensure we received your original message.

Please include the following information in your report:

- Type of issue, such as buffer overflow, SQL injection, cross-site scripting, credential exposure, or execution bypass.
- Full paths of source file(s) related to the issue, if known.
- The location of the affected source code, if known.
- Any special configuration required to reproduce the issue.
- Step-by-step instructions to reproduce the issue.
- Proof-of-concept or exploit code, if possible.
- Impact of the issue, including how an attacker might exploit it.

## What We Consider Security Issues

- Remote code execution.
- SQL injection or other injection attacks.
- Authentication or authorization bypasses.
- Sensitive data exposure, including API keys, credentials, tokens, or account configuration.
- Cross-site scripting (XSS).
- Denial of service vulnerabilities.
- Trading execution bugs that could cause unintended orders, incorrect sizing, or financial loss.
- Vulnerabilities in model-provider credential handling or ATLAS AI access controls.

## What We Don't Consider Security Issues

- Missing security headers on marketing or documentation pages.
- Issues requiring physical access to the device.
- Social engineering attacks.
- Attacks requiring the user to install malware.
- AI model output that is inaccurate, speculative, or unsuitable as trading advice; those concerns should be reported as product safety or quality issues unless they expose a security vulnerability.

## Trading Safety and AI Risk Disclosure

ATLAS Desktop App includes AI-assisted trading, strategy research, and automation workflows. Security controls and risk controls reduce certain operational risks, but they do not guarantee profits, prevent all losses, or make AI output reliable. Users are responsible for account security, API key management, broker access, order confirmation settings, risk limits, and all trading decisions.

## Acknowledgements

We appreciate the security research community's efforts in helping keep ATLAS Desktop App and its users safe. Responsible disclosure of vulnerabilities helps us improve security and privacy for traders using AI-assisted workflows.

Researchers who report valid security issues may be acknowledged in our security hall of fame with permission.
