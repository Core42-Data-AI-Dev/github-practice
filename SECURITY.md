# Security Policy

## Supported Versions

Security updates are provided only for the versions listed below. Please make sure you are using a supported version before reporting an issue.

| Version        | Supported          |
| -------------- | ------------------ |
| main (latest)  | :white_check_mark: |
| Older branches | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub Issues, Discussions, or Pull Requests.**

To report a vulnerability, use one of the following private channels:

1. **GitHub Private Vulnerability Reporting** – Go to the **Security and quality** tab of this repository and click **Report a vulnerability**.
2. **Email** – Send the details to **<security-contact@yourdomain.com>** with the subject line `[SECURITY] github-practice – <short description>`.

### What to include

- A description of the vulnerability and its potential impact
- Steps to reproduce (proof of concept, screenshots, or logs where possible)
- Affected file(s), branch, or version
- Any suggested fix or mitigation (optional)

### What to expect

| Stage                   | Timeline                                        |
| ----------------------- | ----------------------------------------------- |
| Acknowledgement         | Within **2 business days**                      |
| Initial assessment      | Within **5 business days**                      |
| Status updates          | At least **every 7 days** until resolution      |
| Fix for confirmed issue | Based on severity (Critical/High prioritised)   |

- **If accepted:** We will confirm the issue, work on a fix, and let you know when it is released. With your permission, we will credit you for the report.
- **If declined:** We will explain why the report is not considered a vulnerability or is out of scope.

Please keep the vulnerability confidential until a fix is released.

## Security Best Practices for Contributors

- Never commit secrets, passwords, API keys, tokens, or connection strings to the repository.
- Use environment variables or a secure vault (e.g., Azure Key Vault) for credentials.
- Keep dependencies up to date and address Dependabot alerts promptly.
- Report any accidentally exposed credentials immediately so they can be rotated.

## Contact

For any security-related questions, contact the repository maintainer: **<Maintainer Name – email>**.
