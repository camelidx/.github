# Security Policy

## Our Commitment

We take the security of our software products and services seriously, including all source code repositories in our GitHub organizations. We appreciate the security community's efforts in responsibly disclosing vulnerabilities.

## Reporting Security Vulnerabilities

**⚠️ Please do not report security vulnerabilities through public GitHub issues, pull requests, or discussions.**

### How to Report

Send your report via email to: **security@camelidx.com**

We will acknowledge receipt of your report within **48 business hours** and provide regular updates on our progress.

### What to Include in Your Report

To help us understand and address the issue quickly, please include as much of the following information as possible:

#### Vulnerability Details
- **Type of issue** - For example: buffer overflow, SQL injection, cross-site scripting (XSS), authentication bypass, etc.
- **Severity assessment** - Your evaluation of the potential impact
- **Attack scenario** - How an attacker might exploit this vulnerability

#### Location Information
- **Full paths** of affected source file(s)
- **Location** in the codebase (tag/branch/commit hash, or direct URL)
- **Affected versions** or version range

#### Reproduction Steps
- **Step-by-step instructions** to reproduce the issue
- **Special configuration** required (if any)
- **Proof-of-concept or exploit code** (if available)
- **Screenshots or logs** demonstrating the issue (if applicable)

#### Environment Details
- Operating system and version
- Software versions (frameworks, libraries, etc.)
- Browser/client information (if relevant)

### Example Report Structure

```
Subject: [SECURITY] SQL Injection in User Authentication

Vulnerability Type: SQL Injection
Severity: High
Affected Component: /src/auth/login.java (lines 45-52)

Description:
The login endpoint is vulnerable to SQL injection through the username parameter...

Steps to Reproduce:
1. Navigate to /login
2. Enter the following in the username field: admin' OR '1'='1
3. ...

Impact:
An attacker could bypass authentication and gain unauthorized access...

Proof of Concept:
[Code or screenshots]
```

## Questions?

If you have questions about this policy or need to discuss a security concern, please contact us at **security@camelidx.com**.

---

**Last Updated:** January 2026
