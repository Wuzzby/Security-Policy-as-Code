# Security Policy-as-Code

This project simulates a lightweight but realistic GRC (Governance, Risk, and Compliance) documentation stack for a security program. It contains modular policies, framework mappings, operational artifacts, and remediation templates to demonstrate GRC knowledge, risk-based thinking, and documentation control.

> Built for both learning and portfolio use.

---

## Project Overview

This lab demonstrates:

- Policy development aligned with NIST 800-53 and ISO/IEC 27001  
- Control mapping traceability  
- Git-based policy version control  
- GRC operational artifacts: audit checklists, risk register, and policy exception workflows  
- Simulation of real-world review cycles using GitHub Issues  
- Internal audit simulation with documented findings and remediation tracking

It’s built to mirror what an entry-level GRC Analyst, Cybersecurity Compliance Analyst, or Policy Coordinator might work on in an actual security program.

---

## Included Policies

| Policy Name              | Description                                                       |
|--------------------------|-------------------------------------------------------------------|
| `access-control.md`      | Defines user provisioning, privilege management, and RBAC rules   |
| `logging-and-monitoring.md` | Specifies logging requirements, log retention, and SIEM use   |
| `incident-response.md`   | Describes IR lifecycle, escalation procedures, and documentation  |
| `endpoint-security.md`   | Sets endpoint protection standards for laptops, VMs, and phones   |
| `acceptable-use.md`      | Clarifies responsible use of corporate systems and data           |

Each policy is:
- Written in Markdown  
- Mapped to NIST/ISO controls  
- Structured for modular reuse in audits and control documentation

---

## Control Framework Mappings

View the full policy-to-framework crosswalk in Excel format:

➡ [GRC_Policy_Framework_Mappings.xlsx](mappings/GRC_Policy_Framework_Mappings.xlsx)

Covers:
- NIST SP 800-53 Rev. 5  
- ISO/IEC 27001:2022 Clauses  

---

## GRC Artifacts

These simulate the tools and documentation a GRC analyst would create or maintain.

| Artifact | Description |
|----------|-------------|
| [`audit-checklist.md`](artifacts/audit-checklist.md) | Questions to validate control implementation against written policies |
| [`policy-exception-request.md`](artifacts/policy-exception-request.md) | Template for documenting approved deviations from policy |
| [`risk-register.xlsx`](artifacts/risk-register.xlsx) | Live tracker of risks, their mitigation status, and mapped control IDs |
| [`internal-audit-report.md`](artifacts/internal-audit-report.md) | Mock internal audit of all policy areas with findings and remediation actions |

---

## Audit Remediation Templates

These artifacts address gaps identified in the internal audit report and simulate how a GRC team would track ongoing compliance and remediation:

| Artifact | Purpose |
|----------|---------|
| [`access-review-log.md`](artifacts/access-review-log.md) | Records quarterly access reviews per department to prove AC-2/AC-6 compliance |
| [`log-review-checklist.md`](artifacts/log-review-checklist.md) | Documents regular log review activity and anomalies |
| [`post-incident-review-template.md`](artifacts/post-incident-review-template.md) | Standardizes lessons-learned documentation after incidents |
| [`patch-tracking-dashboard.xlsx`](artifacts/patch-tracking-dashboard.xlsx) | Tracks patch timelines, SLA compliance, and overdue systems |

---

## GRC Skills Demonstrated

- Policy Drafting & Documentation  
- Framework Control Mapping (NIST, ISO)  
- Control Validation (Audit Checklists)  
- Risk Assessment and Tracking  
- Policy Exception Handling  
- Internal Audit Simulation  
- Remediation Tracking and Evidence Collection  
- Documentation Governance via Git  

---

## Simulated Workflows

- GitHub Issues simulate internal stakeholder review workflows  
- Commit history acts as an audit trail for documentation changes  
- Internal audit report links to remediation templates for a closed-loop compliance process  
- All files are portable and modifiable for use in labs or future environments  

---

## Why This Matters

Security isn’t just about detection—it’s about governance, assurance, and audit-readiness. This project reflects what early-career GRC professionals are expected to understand, and bridges technical knowledge with risk-based decision making.  

By including both policies and evidence-style artifacts, this project demonstrates the *entire lifecycle* of a control — from definition, to audit, to remediation.

---

## License

Licensed under the MIT License. Use and remix freely with attribution.
