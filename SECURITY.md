# Security Policy

## Supported Versions

This project is maintained for internal use. Security updates are applied to the latest version available in the repository.

| Version        | Supported |
| -------------- | --------- |
| Latest         | ✅         |
| Older Versions | ❌         |

---

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly.

### Examples of Security Issues

* Unauthorized access to employee data
* Data leakage through Google Apps Script
* Cross-Site Scripting (XSS)
* Form validation bypass
* Exposure of sensitive employee information
* Misconfigured Google Apps Script permissions
* API endpoint abuse

### How to Report

Please contact the project maintainer with:

1. Description of the vulnerability
2. Steps to reproduce
3. Potential impact
4. Suggested remediation (if available)

Do not publicly disclose security vulnerabilities until they have been reviewed and addressed.

---

## Data Protection

This form may collect employee information including:

* Full Name
* Employee Code
* Date of Birth
* Gender
* Dependent Information
* Employee Consent

Repository contributors should ensure:

* Sensitive data is never committed to GitHub.
* Production Google Apps Script URLs are protected appropriately.
* Access permissions are restricted to authorized personnel.
* Submitted employee data is stored securely.

---

## Google Apps Script Security

When deploying the Google Apps Script backend:

* Restrict access where possible.
* Review deployment permissions regularly.
* Avoid exposing confidential information in client-side code.
* Monitor submission logs for suspicious activity.

---

## Responsible Usage

This project is intended for internal HR and Mediclaim enrollment purposes only.

Users and administrators are responsible for:

* Maintaining secure access controls
* Protecting employee information
* Following applicable privacy and data protection policies

---

## Security Updates

Security-related fixes will be applied as needed to the latest version of the project.
