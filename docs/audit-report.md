# Accessibility & Architecture Audit

## Website Audited
Wikipedia — https://www.wikipedia.org/

## Accessibility Score
Lighthouse Accessibility Score: 92/100

## Findings

### 1. Form elements do not have associated labels
- Type: Accessibility
- Severity: Medium
- Priority: High
- Evidence: Lighthouse Accessibility audit
- Remediation: Associate every form control with a descriptive label or accessible name.

### 2. Touch targets do not have sufficient size or spacing
- Type: Accessibility
- Severity: Medium
- Priority: Medium
- Evidence: Lighthouse Best Practices audit
- Remediation: Increase the clickable area of controls and provide sufficient spacing between touch targets.

### 3. Accessibility verification requires manual testing
- Type: Accessibility / Process
- Severity: Medium
- Priority: Medium
- Evidence: Lighthouse provides additional manual accessibility checks.
- Remediation: Include keyboard navigation and focus testing in the accessibility test process.

### 4. Client-side JavaScript is part of the page architecture
- Type: Architecture
- Severity: Medium
- Priority: Medium
- Evidence: Browser DevTools shows JavaScript assets loaded by the Wikipedia page.
- Remediation: Keep JavaScript modules well separated and monitor client-side dependencies and loading performance.

### 5. Multiple frontend assets require ongoing maintenance
- Type: Architecture
- Severity: Medium
- Priority: Medium
- Evidence: Browser DevTools shows multiple scripts/styles/assets loaded by the public page.
- Remediation: Maintain clear asset ownership, documentation, dependency management, and performance monitoring.
