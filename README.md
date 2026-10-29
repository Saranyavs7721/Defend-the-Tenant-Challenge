# Defend-the-Tenant-Challenge
**SecureM365: Security Hardening and Strategic Roadmap**

A practical Microsoft 365 project combining security control implementation, automated validation, and risk-based security planning.

**Overview**

This project consists of two phases:

**Phase 1:** Implement and assess 10 Microsoft 365 security controls.
**Phase 2:** Develop a prioritized security plan for a 100-user organization with two administrators and Microsoft 365 E7 licenses.
**Phase 1: Implementation and Assessment**

The following controls were implemented and assessed:

MFA for administrators
MFA for all users
Block legacy authentication
MFA for elevated sign-in risk
Remediation for high user risk
Prevent ordinary-user application consent
Restrict Teams lobby bypass to invited users
Limit Teams presenters to organizers
Prevent anonymous Teams meeting access
Enable SSPR for all users

The assessment results and supporting evidence are available in hardening-results.txt.

**Phase 2: Security Hardening Plan**

The security plan recommends five broader priorities:

Identity security: MFA, phishing-resistant authentication, Conditional Access, legacy authentication blocking, admin separation, and application identity governance.
External access governance: Guest reviews, cross-tenant access settings, expiration policies, and SharePoint and Teams sharing controls.
Endpoint security: Intune, Defender for Endpoint, BitLocker, Windows LAPS, vulnerability management, and Attack Surface Reduction rules.
Automated threat response: Defender XDR, email protection, automated investigation, attack disruption, and incident response runbooks.
Data protection and resilience: Sensitivity labels, DLP, retention, versioning, and tested recovery.

The complete recommendations, rollout approach, trade-offs, success measurements, and 90-day roadmap are available in Microsoft_365_Security_Hardening_Plan.docx.

Repository Files
hardening-results.txt: Phase 1 assessment evidence
Microsoft 365 Security Hardening Plan.docx: Phase 2 security hardening plan
README.md: Project overview

Important: This repository is intended for learning and demonstration purposes. Test all configurations before applying them to a production tenant.
