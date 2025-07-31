# Endpoint Security Policy

## 1. Purpose

The purpose of this policy is to establish baseline security requirements for all endpoint devices (e.g., laptops, desktops, workstations, and mobile devices) used to access organizational systems and data. This ensures that endpoint devices are configured, monitored, and maintained in a secure manner to reduce the risk of compromise.

> Why this matters: Endpoints are often the weakest link—ransomware, phishing payloads, keyloggers, and unauthorized access usually start here. This policy helps close that gap.

---

## 2. Scope

This policy applies to:
- All employee- or company-owned devices that access internal systems
- Contractor devices if granted access to company networks
- Devices on both managed and BYOD programs (with different enforcement levels)

---

## 3. Policy Statement

All endpoints must meet defined security configurations before being permitted to connect to company systems or data. The organization will enforce endpoint security through a combination of device management, technical controls, and user responsibilities.

---

## 4. Roles and Responsibilities

| Role               | Responsibility                                                   |
|--------------------|------------------------------------------------------------------|
| IT/Security Team   | Configure baseline security controls and deploy updates          |
| Asset Owners       | Ensure assigned devices meet and maintain compliance             |
| Users              | Adhere to acceptable use, report suspicious activity, and avoid circumvention |
| GRC Team           | Validate policy implementation and audit endpoint compliance     |

---

## 5. Policy Requirements

### 5.1 Device Configuration
- All company endpoints must follow a standard configuration baseline (e.g., CIS benchmarks).
- Operating systems and software must be vendor-supported and up to date.
- Local administrator access is prohibited unless explicitly authorized and documented.

### 5.2 Anti-Malware and EDR
- Endpoints must run approved anti-malware or EDR (Endpoint Detection and Response) software.
- EDR tools must be configured to:
  - Run continuous background scans
  - Detect behavioral anomalies
  - Send alerts to a central logging system or SIEM

### 5.3 Patch Management
- Critical patches (OS or third-party) must be applied within **7 days** of release.
- High-risk software (browsers, office suites, VPN clients) must be patched within **72 hours** if actively exploited.

### 5.4 Encryption
- All endpoints must use full disk encryption (e.g., BitLocker for Windows, FileVault for macOS).
- USB drives must be encrypted and approved before use with sensitive data.

### 5.5 Endpoint Logging
- Security logs from endpoints must be sent to the centralized SIEM for analysis.
- Logs should include: login events, privilege escalations, software installs, and suspicious file access.

### 5.6 Mobile Device Security
- All mobile devices accessing email or internal systems must:
  - Use a device passcode
  - Have remote wipe capability
  - Be enrolled in Mobile Device Management (MDM)

---

## 6. Exceptions

Exceptions to these requirements (e.g., developer systems needing admin access) must be:
- Documented in a risk register
- Approved by the GRC or Security Governance team
- Monitored for compensating controls (e.g., network segmentation, increased logging)

---

## 7. Compliance

Violations of this policy may result in device disconnection from the network, access revocation, or disciplinary action.

---

## 8. Control Framework Mapping

### NIST 800-53 Rev. 5
| Control ID | Title                                | Mapping Justification                                    |
|------------|----------------------------------------|----------------------------------------------------------|
| CM-2       | Baseline Configuration                 | Requires standard build configurations for endpoints     |
| CM-6       | Configuration Settings                 | Defines how systems should be securely configured        |
| SI-3       | Malicious Code Protection              | Anti-malware and behavioral threat detection             |
| SI-4       | Information System Monitoring          | EDR/AV must log events and send to SIEM                  |
| SC-12      | Cryptographic Key Establishment        | Tied to full disk encryption and USB device policies     |
| AC-19      | Access Control for Mobile Devices      | Ensures mobile devices meet security posture             |

### ISO/IEC 27001:2022
| Clause     | Title                              | Mapping Justification                                     |
|------------|------------------------------------|------------------------------------------------------------|
| A.8.9      | Configuration Management            | Standard builds for workstations                          |
| A.8.10     | Management of Technical Vulnerabilities | Patch and update enforcement                          |
| A.8.11     | Protection from Malware             | Endpoint anti-malware and EDR                            |
| A.8.12     | Logging and Monitoring              | Logging user and system behavior                         |
| A.5.23     | Use of Cryptography                 | Encryption of data on devices                            |
| A.5.20     | Mobile Device Management            | MDM, passcodes, and remote wipe enforcement              |

---

## 9. Revision History

| Version | Date       | Author    | Description              |
|---------|------------|-----------|--------------------------|
| v1.0    | 2025-07-31 | Wuzzby    | Initial draft created    |

---
