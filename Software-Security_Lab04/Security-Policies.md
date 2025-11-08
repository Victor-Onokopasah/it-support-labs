### Complete Formatted `Security-Policies.md`

```markdown
Author: Victor Onokopasah
Lab: 04 - Security Policies
Date: [Current Month] 2024

# Lab 04: - Security Policies

Objective: To establish comprehensive security policies addressing the root cause of the malware infection documented in `Malware-Removal.md`. This document outlines proactive security controls, user privilege management, and organizational training requirements to mitigate future security incidents and strengthen the organization's security posture. These policies directly support business continuity by reducing system downtime, protecting sensitive data, and maintaining operational integrity.

This exercise develops core IT support competencies required in enterprise environments:

*   Security Incident Analysis: Conducting root cause analysis of security breaches.
*   Policy Development: Creating enforceable, clear security policies aligned with business objectives.
*   Access Control Implementation: Applying the Principle of Least Privilege (PoLP) in operational contexts.
*   Security Awareness: Developing effective user training and documentation.
*   Risk Mitigation: Designing preventative controls to improve organizational security posture.

### Key Skills

*   Security Policy Creation & Documentation
*   Root Cause Analysis & Incident Response Planning
*   User Education Program Development
*   Access Control Management (PoLP)
*   Software Management Lifecycle
*   Compliance Framework Alignment

### Tools & Frameworks Used

*   Documentation: Markdown
*   Security Frameworks:
    -   NIST Cybersecurity Framework Alignment
    -   Principle of Least Privilege (PoLP)
    -   Defense-in-Depth Strategy
*   Policy Types:
    -   Acceptable Use Policy (AUP)
    -   Software Management Policy
    -   User Access Control Policy

---

## 1. Root Cause Analysis

### Security Incident Post-Mortem

Incident Reference: Malware infection detailed in `Malware-Removal.md`.

Primary Root Cause: Unauthorized installation of unvetted third-party software ("freeware" application) containing bundled Adware and Potentially Unwanted Programs (PUPs).

Contributing Factors:
- Excessive User Privileges: The user account was configured with administrative rights.
- Lack of Software Controls: No formal software vetting or approval process was in place.
- Security Awareness Gap: The user was unaware of risks associated with unofficial software sources.
- Preventative Control Failure: Absence of application whitelisting or restriction policies.

Business Impact:** System performance degradation, potential data exposure risk, and IT support resource expenditure for remediation.

---

## 2. Proposed Security Policies

### Policy 1: Acceptable Use Policy (AUP) for Software Management

Policy Statement: All software installations on organizational assets must comply with the approved software management lifecycle, including proper vetting, approval, and deployment through authorized channels.

Requirements & Guidelines:
- *oftware Request Process: All software must be requested through the IT Service Management portal.
- Vetting Procedure:*The IT security team will assess software for vulnerabilities, licensing, and business necessity.
- Approved Sources: Software may only be installed from organizational software repositories or vendor-approved distribution channels.
- Prohibited Activities: Downloading and installing software from unofficial websites, peer-to-peer networks, or unverified sources is strictly prohibited.
- Audits: Regular audits of installed software will be conducted against an approved catalog.

---

### Policy 2: Implementation of the Principle of Least Privilege (PoLP)

Policy Statement: User accounts shall be granted the minimum levels of access—or permissions—needed to perform their job functions.

Technical Controls:
- Standard User Accounts: All users will operate with standard user privileges by default.
- Administrative Access: Separate administrative accounts are required for system changes, subject to managerial approval and Just-in-Time (JIT) principles.
- Role-Based Access Control (RBAC): Permissions will be assigned based on defined job function requirements.
- ccess Reviews: User access rights will be reviewed quarterly.

Business Justification: This policy reduces the attack surface, contains malware propagation, and supports compliance requirements.

---

### Policy 3: Mandatory User Security Awareness Training

Policy Statement: All employees must complete comprehensive security awareness training annually, with additional targeted training based on role-specific risks and emerging threats.

Core Curriculum:
- Safe software installation practices and approved sources.
- Social engineering and phishing recognition.
- Password hygiene and multi-factor authentication.
- Data handling and classification requirements.
- Incident reporting procedures and escalation paths.

Compliance Enforcement:
- Training completion will be tracked in HR systems.
- Quarterly phishing simulations will be conducted to measure effectiveness.
- Management will receive reports on departmental compliance rates.

---

## 3. Implementation Roadmap & Success Metrics

### Implementation Phases
- **Phase 1 (30 Days): Communicate new policies; begin user access review and privilege reduction.
- **Phase 2 (90 Days): Implement software request workflow and application control solutions.
- **Phase 3 (Ongoing): Conduct quarterly access reviews, compliance audits, and continuous training updates.

### Key Performance Indicators (KPIs)
- Reduction in unauthorized software installations (>80% within 6 months).
- Decrease in malware incidents attributed to user actions (>50% within 12 months).
- Security training completion rate (>95% compliance).

---

Document Classification: Internal Use Only 
This document follows enterprise security policy standards and aligns with industry best practices.
```
