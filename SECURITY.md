# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

Please report (suspected) security vulnerabilities to **[INSERT EMAIL OR SECURITY POLICY URL]**. You will receive a response within 48 hours. If the issue is confirmed, we will release a patch as soon as possible depending on complexity but historically within a few days.

### How to Report

1. **Do not** open a public GitHub issue
2. Email the maintainers or use GitHub's private vulnerability reporting feature
3. Include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### What to Expect

- We will acknowledge receipt of your report within 48 hours
- We will provide a detailed response within 7 days
- We will keep you informed of the progress toward fixing the vulnerability
- We will notify you when the vulnerability has been fixed

## Security Best Practices

When using Engage360, please follow these security best practices:

- Keep your dependencies up to date
- Review code changes before merging
- Use secure authentication methods
- Don't commit sensitive information (API keys, tokens, etc.)
- Regularly update your Expo and React Native versions

## Known Security Considerations

- This app may handle user-generated content - ensure proper sanitization
- Network requests should use HTTPS
- Store sensitive data securely using appropriate React Native libraries
- Follow platform-specific security guidelines for iOS and Android

---

**Thank you for helping keep Engage360 and our users safe!**

