# Internal GRC Audit Report – Q3

**Auditor:** Wuzzby  
**Date:** 2025-08-11  
**Scope:** Access Control, Logging & Monitoring, Incident Response, Endpoint Security, Acceptable Use  
**Objective:** Evaluate implementation of core policies and identify gaps prior to formal external audit.

---

## Summary of Findings

| Policy Area             | Compliance Score (0–100%) | Key Issues Found                          | Remediation Required? |
|-------------------------|----------------------------|-------------------------------------------|------------------------|
| Access Control          | 80%                        | No formal access review records           | Yes                    |
| Logging & Monitoring    | 90%                        | Log review frequency not consistently documented | Yes              |
| Incident Response       | 95%                        | No evidence of post-incident reviews      | Yes                    |
| Endpoint Security       | 85%                        | Delayed patching of several test systems  | Yes                    |
| Acceptable Use          | 100%                       | No issues identified                      | No                     |

---

## Detailed Findings

### 1. Access Control Policy

**Tested Controls:**
- Unique user ID assignment  
- MFA enforcement for admins  
- Quarterly access review documentation

**Evidence Found:**
- MFA enforced via admin portal screenshot  
- Access control policy uploaded and versioned  
- **Missing:** Documented access review logs

**Finding:**  
No access review logs were available to show periodic validation of user permissions. This weakens AC-2 compliance.

**Recommendation:**  
Create an `access-review-log.md` template to track quarterly access reviews by department.

---

### 2. Logging and Monitoring Policy

**Tested Controls:**
- Log generation from critical systems  
- Centralized log collection  
- Weekly review of logs

**Evidence Found:**
- SIEM configuration documented in lab  
- Logs visible in Elastic dashboard  
- **Partial:** Review dates not consistently tracked

**Finding:**  
Log reviews are occurring but lack a documented schedule or checklist.

**Recommendation:**  
Implement a simple log review schedule (`log-review-checklist.md`) with initials, dates, and system scope.

---

### 3. Incident Response Policy

**Tested Controls:**
- Defined IR team roles  
- Escalation process  
- Post-incident analysis

**Evidence Found:**
- Policy is complete  
- Roles and lifecycle are clear  
- **Missing:** Post-incident review documentation

**Finding:**  
No formal documentation of lessons learned or root cause analysis following simulated incidents.

**Recommendation:**  
Create a `post-incident-review-template.md` for internal IR documentation after each incident or simulation.

---

### 4. Endpoint Security Policy

**Tested Controls:**
- AV/EDR enforcement  
- Patch timelines  
- Encryption policy

**Evidence Found:**
- Endpoint hardening checklist present  
- Simulated patch logs show delays  
- Encryption standards documented

**Finding:**  
Patch application exceeded 7-day SLA on two out of four test systems.

**Recommendation:**  
Add a “patch compliance tracker” to monitor critical updates and enforcement timelines.

---

### 5. Acceptable Use Policy

**Tested Controls:**
- User acknowledgment  
- Acceptable content restrictions  
- Monitoring notification

**Evidence Found:**
- Policy available and clearly worded  
- No major gaps detected

**Finding:**  
No audit exceptions or violations noted at this time.

**Recommendation:**  
Maintain current enforcement. Re-evaluate at next onboarding cycle to verify user training.

---

## Overall Audit Recommendations

| Area                        | Recommendation                             | Owner         | Target Date |
|-----------------------------|---------------------------------------------|----------------|--------------|
| Access Reviews              | Create review log template                 | GRC            | Aug 15, 2025 |
| Log Review Tracking         | Create log-review checklist                | Security Ops   | Aug 20, 2025 |
| IR Post-Mortems             | Add post-incident template                 | IR Team        | Aug 25, 2025 |
| Patch SLA Monitoring        | Create patch-tracking dashboard            | IT/Engineering | Aug 30, 2025 |

---

## Notes

- This internal audit was conducted based on simulated lab data. In a real environment, these findings would be supported with screenshots, tickets, logs, or stakeholder interviews.
- The structure and formatting of this report are based on internal IT control audit templates used in security assessments.
