# Policy Audit Checklists

These checklists are designed to help audit or self-assess the implementation of the security policies in this repository. Each checklist maps directly to the requirements described in the policy files.

---

## Access Control Policy Audit Checklist

**Policy Reviewed:** `access-control.md`  
**Reviewer Name:** ___________________  
**Review Date:** _____________________  

| Audit Item                                                                 | Status (✔ / X / N/A) | Notes |
|----------------------------------------------------------------------------|------------------------|-------|
| Is there a formally documented Access Control Policy?                      |                        |       |
| Are all user accounts uniquely assigned (no shared accounts)?             |                        |       |
| Is there a defined process for account creation and deactivation?         |                        |       |
| Is MFA enforced for administrative and remote access?                     |                        |       |
| Are access permissions reviewed at least quarterly?                       |                        |       |
| Are privileged access assignments documented and approved?                |                        |       |
| Are dormant accounts automatically disabled after 30 days of inactivity?  |                        |       |
| Are logs of access events being captured and reviewed?                    |                        |       |
| Are exceptions to access control documented and approved?                 |                        |       |

---

> _Tip: You can duplicate this section to create separate checklists for Logging, IR, Endpoint Security, etc._

---

## Template: Create Your Own Checklist

Copy and paste this template to build checklists for other policies:

```markdown
## [Policy Name] Audit Checklist

**Policy Reviewed:** `file-name.md`  
**Reviewer Name:** ___________________  
**Review Date:** _____________________  

| Audit Item                                         | Status (✔ / X / N/A) | Notes |
|----------------------------------------------------|------------------------|-------|
| ...                                                |                        |       |
| ...                                                |                        |       |
