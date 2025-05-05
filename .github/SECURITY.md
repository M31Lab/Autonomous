# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the severity of the vulnerability.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0.0 | :x:                |

## Reporting a Vulnerability

Please report (suspected) security vulnerabilities through our [dedicated security issue form](https://github.com/m31lab/Autonomous/security/advisories/new), not through public GitHub issues.

You should receive a response within 48 hours. If for some reason you do not, please follow up via email to security@m31lab.github.io to ensure we received your original message.

Please include the following information in your report:

- Type of issue (e.g. buffer overflow, SQL injection, XSS, etc.)
- Location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

## Disclosure Policy

When we receive a security bug report, we will:

1. Confirm the issue and determine the affected versions
2. Audit code to find any potential similar issues
3. Prepare fixes for all supported versions
4. Release fixes as soon as possible

## Comments on this Policy

If you have suggestions on how this process could be improved, please submit a pull request. 