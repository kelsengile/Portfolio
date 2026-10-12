# Security Policy

Thank you for helping keep this project and its visitors safe.

---

### Supported Versions

This is a personal portfolio website that is continuously updated. Only the latest version on the `main` branch (the one deployed to the live site) receives security fixes.

### Reporting a Vulnerability

**Please do not report security vulnerabilities through public issues, pull requests, or discussions.**

Instead, report them privately:

1. Use GitHub's **"Report a vulnerability"** option under this repository's **Security** tab (private vulnerability reporting), or
2. Email **kelsengile.dev@gmail.com** with the subject line "Security Report."

Please include as much of the following as you can:

- A description of the issue and its potential impact
- Steps to reproduce it (URLs, inputs, screenshots, or proof of concept)
- The browser, device, or environment where you found it
- Any suggested fix, if you have one

### What to Expect

- **Acknowledgment:** within 3 business days
- **Initial assessment:** within 7 days
- **Fix or mitigation:** as soon as reasonably possible, depending on severity and complexity
- **Credit:** with your permission, you'll be credited for the discovery once the issue is resolved

Updates will be sent to you throughout the process. If a report is declined, you'll receive an explanation.

### Scope

**In scope:**
- Vulnerabilities in the source code of this repository
- Issues on the live portfolio website (e.g., XSS, injection, exposed sensitive data, insecure configuration)
- Exposed secrets, API keys, or credentials in the repository or its history

**Out of scope:**
- Vulnerabilities in third-party services, platforms, or dependencies (please report those to the vendor, though I'd appreciate a heads-up)
- Denial-of-service attacks, spam, or social engineering
- Automated scanner output with no demonstrated impact
- Missing best-practice headers with no practical exploit

### Responsible Disclosure Guidelines

Please:

- Give me reasonable time to fix the issue before sharing it publicly
- Avoid accessing, changing, or deleting data that isn't yours
- Avoid actions that disrupt the site or affect other visitors
- Act in good faith. Research done in line with this policy will not result in legal action.

### Security Tips for Contributors

- Never commit secrets, API keys, passwords, or `.env` files
- Keep dependencies up to date and review new ones before adding them
- Validate and sanitize any user input
- Review any AI-generated code for security issues before submitting it

---

*Last updated: October 2026*