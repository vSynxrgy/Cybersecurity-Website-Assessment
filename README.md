# FABA Web Application Security Assessment

> A cybersecurity assessment of the publicly accessible attack surface of the Find A Black Agent (FABA) platform, focused on authentication, identity verification, application security, privacy practices, and overall security posture.

> **Disclaimer:** This repository contains a sanitized version of the assessment that was approved for public release. No confidential information, proprietary data, or reproducible exploit details are included.

---

## Executive Summary

This project documents an external, grey-box cybersecurity assessment of the Find A Black Agent (FABA) platform. The assessment evaluated publicly accessible portions of the application using passive reconnaissance and non-intrusive security testing techniques.

The review focused on authentication workflows, account onboarding, privacy controls, website security configuration, user input validation, and organizational trust indicators. Testing was conducted without bypassing authentication, exploiting vulnerabilities, or attempting unauthorized access.

The assessment concluded that the platform demonstrates a solid baseline security posture while identifying opportunities to strengthen identity verification, onboarding governance, and browser security hardening.

---

## Objectives

- Assess the platform's public security posture
- Evaluate authentication and account management workflows
- Review privacy practices and legal transparency
- Assess website security configuration
- Identify security weaknesses and business risks
- Produce actionable remediation recommendations

---

## Skills Demonstrated

- Web Application Security Assessment
- Authentication Testing
- Identity & Access Management Analysis
- Risk Assessment
- Security Documentation
- Vulnerability Analysis
- OWASP Security Principles
- Technical Report Writing
- Security Configuration Review
- Privacy & Compliance Review

---

## Technologies & Methodologies

- Grey-Box Assessment
- Passive Reconnaissance
- Authentication Testing
- Input Validation Testing
- Browser Security Header Analysis
- Cross-Site Scripting (XSS) Validation
- Risk Prioritization
- Security Reporting

---

## Assessment Scope

The assessment examined publicly accessible components of the platform, including:

- Website Architecture
- Authentication System
- Account Registration
- Password Recovery
- Contact Forms
- Identity Verification
- Privacy Policy
- Terms & Conditions
- Browser Security Configuration
- Organizational Trust Indicators

---

## Assessment Methodology

The engagement followed a structured security review consisting of five phases:

### Phase 1 — Website Reconnaissance

- Reviewed public-facing pages
- Identified available functionality
- Mapped the application's attack surface

---

### Phase 2 — Documentation Review

- Privacy Policy
- Terms & Conditions
- Organizational transparency
- Public disclosures

---

### Phase 3 — Authentication Testing

- Registration workflow
- Login validation
- Password recovery
- Account lifecycle
- User enumeration observations

---

### Phase 4 — Application Security Testing

- Input validation
- Contact forms
- Basic XSS validation
- Error message analysis

---

### Phase 5 — Security Configuration Review

- HTTPS configuration
- HSTS
- Security headers
- Cookie security
- Browser protections

---

## Key Findings

### Strengths

- HTTPS enforced
- HSTS enabled
- Secure cookie configuration
- Generic authentication error messaging
- Privacy and legal documentation
- Basic input validation
- XSS payloads did not execute during testing

---

### Opportunities for Improvement

- Mandatory email verification
- Stronger realtor identity verification
- Administrative onboarding approval
- Multi-factor authentication
- Rate limiting
- Browser security headers (CSP, X-Frame-Options, X-Content-Type-Options)
- Formal vulnerability disclosure policy

---

## Risk Summary

The assessment identified **no critical vulnerabilities** during testing.

The primary risks centered around business trust and identity assurance rather than exploitable technical vulnerabilities. The most significant recommendations involved strengthening onboarding governance, identity verification, and public profile validation to reduce opportunities for impersonation and fraudulent account creation.

---

## Repository Contents

```
.
├── README.md
├── report/
│   └── FABA_Cybersecurity_Assessment_Report.pdf
└── images/
    ├── authentication-testing.png
    ├── registration-workflow.png
    ├── security-headers.png
    ├── risk-matrix.png
    └── recommendations.png
```

---

## What I Learned

This assessment strengthened my understanding of:

- Web application security
- Authentication systems
- Identity assurance
- Security risk analysis
- Technical communication
- Professional cybersecurity reporting

It also reinforced the importance of balancing technical security controls with business risk, user trust, and secure application design.
