## Pull Request Title

**Description:**
<!-- Provide a brief summary of the changes introduced by this PR. Include the context and reasoning behind the modifications. -->

**Related Issue:**
<!-- Link any related issues (e.g., Fixes #123) -->

---

## Security Checklist

- [ ] **Input Validation**: All user inputs are properly validated and sanitized to prevent injection attacks.
- [ ] **Authentication & Authorization**: The PR does not introduce unauthorized access, public endpoints or privilege escalation risks.
- [ ] **Secrets Management**: No hardcoded secrets, API keys, or sensitive data are present.
- [ ] **Data Protection**: Sensitive data is encrypted both at rest and in transit where applicable.
- [ ] **Logging & Monitoring**: New features include proper logging and monitoring where necessary, without logging sensitive information.
- [ ] **Security Headers**: If applicable, relevant security headers (CSP, HSTS, X-Frame-Options) are correctly configured.
- [ ] **Error Handling**: Errors do not expose sensitive system details.
- [ ] **Third-Party Services**: Any new third-party integrations follow security best practices (e.g. authentiation, encryption, logging).
- [ ] **Code Review**: The PR has been reviewed for potential security flaws.

---

## Additional Notes
<!-- Provide any additional information reviewers should be aware of. -->

## Checklist

- [ ] I have performed a self-review of my code
- [ ] I have tested the changes locally
- [ ] I have run security tests where applicable
- [ ] This PR follows the coding and security guidelines of the project

---

**Reviewer(s):**
@mention reviewers
