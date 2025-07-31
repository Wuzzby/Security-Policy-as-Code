# Access Control Policy

## 1. Purpose

The purpose of this policy is to define the requirements and responsibilities for controlling access to information systems and data. Effective access control ensures that only authorized users can access resources appropriate to their role and level of trust, in alignment with the principle of least privilege.

---

## 2. Scope

This policy applies to all employees, contractors, and third-party users who access organizational systems, applications, or data—whether on-premises or remotely.

---

## 3. Policy Statement

The organization must ensure that:
- Access to systems is granted only after formal authorization and approval.
- Each user is assigned a unique user ID and authentication method (e.g., password, MFA).
- Access rights are aligned to job responsibilities and reviewed periodically.
- Privileged access (e.g., administrators, domain admins) is tightly controlled and logged.
- Dormant or inactive accounts are disabled after 30 days of inactivity.
- Access is promptly revoked when employees leave the organization or change roles.


---

## 4. Roles and Responsibilities

| Role                | Responsibility                                                   |
|---------------------|------------------------------------------------------------------|
| IT Security Team    | Implement technical access controls and monitor access logs      |
| HR Department       | Notify IT of employee onboarding/offboarding events              |
| Department Managers | Approve access requests based on job role                        |
| GRC Team            | Review policy compliance and conduct access audits               |

---

## 5. Policy Requirements

### 5.1 Account Creation
- All accounts must be approved through a documented request and authorization process.
- Shared accounts are prohibited except for documented exceptions approved by the GRC team.

### 5.2 Authentication
- All user accounts must be protected by strong authentication methods.
- Multi-Factor Authentication (MFA) is mandatory for administrative or remote access.

### 5.3 Role-Based Access Control (RBAC)
- Access is granted based on the principle of least privilege.
- Users are assigned to security groups or roles that match their job functions.

### 5.4 Access Reviews
- Managers must review user access at least quarterly.
- The GRC team will verify completion of reviews and document findings.

### 5.5 Termination or Role Change
- IT must disable or adjust access within 24 hours of HR notification.

### 5.6 Logging and Monitoring
- All administrative access must be logged and monitored.
- Logs must be retained in accordance with the Logging and Monitoring Policy.

---

## 6. Exceptions

Requests for exceptions to this policy must:
- Be submitted in writing
- Include a business justification
- Be approved by the GRC team
- Be time-bound and documented

---

## 7. Compliance

Failure to comply with this policy may result in disciplinary action, up to and including termination of access or employment.

---

## 8. Control Framework Mapping

### NIST 800-53 Rev. 5
| Control ID | Title                     | Mapping Justification                                 |
|------------|---------------------------|--------------------------------------------------------|
| AC-1       | Access Control Policy     | This document defines the overall access control policy. |
| AC-2       | Account Management        | Covers provisioning, disabling, and auditing accounts. |
| AC-3       | Access Enforcement        | Enforces RBAC, least privilege, and access restrictions. |
| AC-5       | Separation of Duties      | Managers approve access to limit conflict of interest. |
| AC-6       | Least Privilege           | Access is granted only as needed per job function.     |
| IA-2       | Identification & Auth     | MFA, unique IDs, and secure authentication required.   |

### ISO/IEC 27001:2022
| Clause     | Title                              | Mapping Justification                                  |
|------------|------------------------------------|---------------------------------------------------------|
| A.5.15     | Access Control Policy              | This policy sets out control objectives for access.     |
| A.5.18     | Access Rights                      | Establishes procedures for managing access rights.      |
| A.5.16     | User Access Management             | Covers account provisioning, review, and revocation.    |
| A.5.17     | User Responsibilities              | Users must comply with security and access requirements.|
| A.8.3      | Information Access Restriction     | Access to systems and data is based on job roles.       |

---

## 9. Revision History

| Version | Date       | Author    | Description              |
|---------|------------|-----------|--------------------------|
| v1.0    | 2025-07-31 | Wuzzby    | Initial draft created    |

