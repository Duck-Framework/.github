# 🔒 Security Policy

## Supported Versions

We take security seriously at Duck Framework. The following table shows which versions of our projects are currently being supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < Latest| :x:                |

**Note:** Individual repositories may have different support policies. Please check the specific repository for version-specific information.

## 🐛 Reporting a Vulnerability

We appreciate your efforts to responsibly disclose your findings and will make every effort to acknowledge your contributions.

### How to Report a Security Vulnerability

**Please do NOT report security vulnerabilities through public GitHub issues.**

Instead, please use one of the following methods:

#### Option 1: GitHub Security Advisory (Preferred)

1. Navigate to the relevant repository
2. Go to the "Security" tab
3. Click "Report a vulnerability"
4. Fill out the advisory form with details

#### Option 2: Email Report

If you prefer email, please send your report to:

- **Security Team**: [Create an issue with "SECURITY" label](../../issues/new)

**Please include the following information:**

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### What to Expect

After you submit a report:

1. **Acknowledgment**: We will acknowledge receipt of your vulnerability report within **48 hours**
2. **Assessment**: Our security team will assess the vulnerability and determine its impact
3. **Updates**: We will keep you informed about the progress of fixing the vulnerability
4. **Resolution**: Once the vulnerability is fixed, we will:
   - Notify you when the fix is deployed
   - Publicly disclose the vulnerability (with your permission)
   - Credit you for the discovery (if you wish)

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days
- **Fix Timeline**: Depends on severity
  - Critical: Within 7 days
  - High: Within 30 days
  - Medium: Within 90 days
  - Low: Best effort

## 🛡️ Security Best Practices

When using Duck Framework projects, we recommend:

1. **Keep Dependencies Updated**: Regularly update to the latest versions
2. **Enable Security Features**: Use all available security features
3. **Follow Documentation**: Adhere to security guidelines in documentation
4. **Review Code**: Conduct regular security reviews of your implementations
5. **Monitor Advisories**: Watch for security advisories and updates

## 🏆 Recognition

We believe in recognizing security researchers who help keep our projects safe:

- Contributors will be credited in release notes (unless anonymity is requested)
- Significant findings may be highlighted in our security acknowledgments
- We maintain a hall of fame for security researchers (coming soon)

## 📋 Scope

This security policy applies to:

- All repositories under the Duck-Framework organization
- Latest stable releases
- Current development branches (main/master)

### Out of Scope

The following are generally considered out of scope:

- Issues in third-party dependencies (please report to the maintainers)
- Social engineering attacks
- Physical attacks
- Attacks requiring physical access to a user's device
- Denial of service attacks

## 📚 Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [GitHub Security Best Practices](https://docs.github.com/en/code-security)
- [Common Weakness Enumeration (CWE)](https://cwe.mitre.org/)

## ⚖️ Safe Harbor

We support safe harbor for security researchers who:

- Make a good faith effort to avoid privacy violations, data destruction, and service interruption
- Only interact with accounts you own or with explicit permission of the account holder
- Do not exploit a security issue beyond what is necessary to demonstrate it
- Report vulnerabilities promptly
- Keep vulnerability details confidential until they are resolved

---

**Thank you for helping keep Duck Framework and our community safe!** 🦆
