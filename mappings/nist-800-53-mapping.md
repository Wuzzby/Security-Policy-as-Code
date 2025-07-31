# NIST 800-53 Rev. 5 Mapping

This document outlines how each policy in this repository maps to selected control families from NIST Special Publication 800-53 Revision 5. This mapping demonstrates alignment with key federal cybersecurity standards and supports audit readiness and compliance.

---

## Access Control Policy

| Control ID | Title                    | Rationale                                                    |
|------------|--------------------------|---------------------------------------------------------------|
| AC-1       | Access Control Policy    | This document defines the access control policy itself.       |
| AC-2       | Account Management       | Covers user provisioning, disabling, and account review.      |
| AC-3       | Access Enforcement       | Enforces RBAC and access restrictions.                        |
| AC-5       | Separation of Duties     | Managers approve access to limit conflict of interest.        |
| AC-6       | Least Privilege          | Grants minimum access required for role.                      |
| IA-2       | Identification & Auth    | Requires unique IDs and MFA for all users.                    |

---

## Logging and Monitoring Policy

| Control ID | Title                             | Rationale                                                    |
|------------|-----------------------------------|---------------------------------------------------------------|
| AU-2       | Audit Events                      | Specifies which events must be logged.                        |
| AU-6       | Audit Review, Analysis, Reporting | Outlines review frequency and monitoring requirements.        |
| AU-9       | Protection of Audit Info          | Logs are secured and tamper-proof.                            |
| AU-11      | Audit Record Retention            | Defines retention minimums and storage requirements.          |
| IR-5       | Incident Monitoring                | Supports detection and correlation with IR efforts.           |

---

## Incident Response Policy

| Control ID | Title                           | Rationale                                                    |
|------------|----------------------------------|---------------------------------------------------------------|
| IR-1       | Incident Response Policy         | This document serves as the formal IR policy.                |
| IR-4       | Incident Handling                | Describes response process from detection to recovery.        |
| IR-5       | Incident Monitoring              | Monitoring tools and alerts support detection.                |
| IR-6       | Incident Reporting               | Defines reporting timelines and escalation paths.             |
| IR-8       | Incident Response Plan           | Structured response phases and team responsibilities.         |
| AU-6       | Audit Log Review                 | Logs are used in detection and investigation.                 |

---

## Endpoint Security Policy

| Control ID | Title                          | Rationale                                                    |
|------------|----------------------------------|---------------------------------------------------------------|
| CM-2       | Baseline Configuration          | Requires secure system configuration standards.              |
| CM-6       | Configuration Settings          | Applies consistent security settings to all endpoints.        |
| SI-3       | Malicious Code Protection       | Requires AV/EDR deployment on all endpoints.                  |
| SI-4       | System Monitoring               | EDR logs endpoint activity and suspicious behavior.           |
| SC-12      | Cryptographic Key Establishment | Supports disk and data encryption at rest.                    |
| AC-19      | Mobile Device Access Control    | Controls access from mobile platforms.                        |

---

## Acceptable Use Policy

| Control ID | Title                           | Rationale                                                    |
|------------|----------------------------------|---------------------------------------------------------------|
| PL-4       | Rules of Behavior               | Defines appropriate user behavior and restrictions.           |
| PS-6       | Access Agreements               | Requires user acknowledgment of responsibilities.             |
| AC-8       | System Use Notification         | Users are warned about monitoring and expected use.           |
| AU-12      | Audit Generation                | Supports logging of end-user activity.                        |

---

## Summary Table

| Policy                   | Total Mapped Controls |
|--------------------------|-----------------------|
| Access Control           | 6                     |
| Logging & Monitoring     | 5                     |
| Incident Response        | 6                     |
| Endpoint Security        | 6                     |
| Acceptable Use           | 4                     |

---

> Note: This mapping does not cover all possible NIST controls. It demonstrates relevant, realistic coverage for an entry-level GRC portfolio project. A complete audit-level mapping would require deeper scoping and control tailoring.
