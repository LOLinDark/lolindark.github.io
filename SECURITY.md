# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it **privately** to avoid exposing the issue publicly before it can be fixed.

### How to Report

1. **Do NOT** create a public GitHub issue
2. **Email** your security report to: `security@lolindark.dev`
3. Include:
   - Description of the vulnerability
   - Steps to reproduce (if applicable)
   - Potential impact
   - Suggested fix (if you have one)

### Response Timeline

- **Initial Response**: Within 48 hours
- **Assessment**: Within 1 week
- **Fix/Release**: Dependent on severity
- **Public Disclosure**: After fix is deployed (coordinated timing)

## Severity Levels

### Critical
- Remote code execution
- Authentication bypass
- Data breach/unauthorized access
- Active exploitation in the wild

**Response Time**: Urgent (24 hours max)

### High
- Privilege escalation
- Information disclosure
- Denial of service

**Response Time**: 1-3 days

### Medium
- Security weaknesses that could lead to vulnerabilities
- Best practice violations
- Deprecated dependency usage

**Response Time**: 1-2 weeks

### Low
- Minor security improvements
- Documentation updates
- Non-critical issues

**Response Time**: Next release cycle

## Supported Versions

| Version | Status | Security Updates |
|---------|--------|------------------|
| Latest | Active | ✅ Yes |
| Previous | Limited | ⚠️ Case-by-case |
| Older | End of Life | ❌ No |

## Disclosure Policy

This project follows **Coordinated Vulnerability Disclosure (CVD)**:

1. **Private Report** → We acknowledge receipt within 48 hours
2. **Assessment** → We evaluate severity and impact
3. **Fix Development** → We create and test a patch
4. **Coordination** → We agree on a disclosure timeline with you
5. **Public Release** → We release the fix publicly
6. **Credit** → We acknowledge your report (if you wish)

### Embargo Period

- **Critical**: 0-7 days (immediate to urgent)
- **High**: 7-14 days
- **Medium/Low**: 30-60 days

We'll request an extension only if necessary and will communicate clearly about timelines.

## Security Practices

### Current Measures

- ✅ Dependency scanning via GitHub Dependabot
- ✅ GitHub Security Advisories enabled
- ✅ Regular security updates
- ✅ Code review process

### Future Improvements

- 🔄 Automated security testing in CI/CD
- 🔄 OWASP compliance review
- 🔄 Security documentation expansion

## Dependencies & Supply Chain

We aim to:
- Keep dependencies up-to-date
- Use only trusted, well-maintained packages
- Monitor for known vulnerabilities
- Review dependency licenses

Check `package.json` for current dependencies.

## Best Practices for Users

If you're using LOLinDark projects:

1. **Keep Updated** - Regularly pull the latest changes
2. **Review Code** - This is open source; audit what matters to you
3. **Report Issues** - Use this security policy for vulnerabilities
4. **Contribute** - Security improvements are welcome via pull requests

## Questions?

Have questions about this security policy? Open an issue or contact `security@lolindark.dev`.

---

**Last Updated**: April 22, 2026
**Policy Version**: 1.0.0
